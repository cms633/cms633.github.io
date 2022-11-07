---
layout: post
published: true
category: updates
title: Self-study_ Working With Data - Joshua Mbogo
author: Qingyu Cai
---
Doing the self study work was very interesting. It has been a minute since I have used P5.js and it was my first time requesting data from an API using the framework. The homework instructions made the process very smooth and I was able to visualize the percentages pertaining to gender (uknown, male, female) recoded in the 'person' api. I create an animation effect by displaying the visulization of the data while the data is being parsed so that the red, green, and blue recetangles visulaizing uknown, male, female respectively shift up and down. Once the animation is finished it is apparent that uknown entries (red) are most common which could be a point of contention when thinking about consisitsency of data records especially when the purpose of the person api is to fgive data about a person. Beloow is a copy of my code
```
// Author:    Joshua Mbogo
// Framework: P5.js
var persons = [];
var unknown = 0
var male = 0;
var female = 0;
var index = 0;
function preload() {
  var API_KEY = 'ff23251e-fd52-450d-86e3-cfea258bf662';
  var query = 'person';
  var params = '&size=100';
  var url = 'https://api.harvardartmuseums.org/' + query + '?apikey=' + API_KEY + params;
  
  function gotResponse(response) {
    var totalPages = response.info.pages
    for (var currentPage = 1; currentPage <= totalPages; currentPage += 1) {
      loadJSON(url + '&page=' + currentPage, gotPages);
    }
  }

  function gotPages(response) {
    persons = persons.concat(response.records);
  }
  
  loadJSON(url, gotResponse)
}

function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(220);
  var gender = persons[index].gender
  if (gender === 'unknown') {
    unknown += 1;
  } else if (gender === 'male') {
    male += 1;
  } else if (gender === 'female') {
    female += 1;
  }
  index += 1;
  fill(255, 0, 0);
  stroke(255, 0, 0);
  rect(0, 0, 40, 400 * unknown / index);
  fill(0, 255, 0);
  stroke(0, 255, 0);
  rect(60, 0, 40, 400 * male / index);
  fill(0, 0, 255);
  stroke(0, 0, 255);
  rect(120, 0, 40, 400 * female / index);
  
  fill(0);
  noStroke();
  text('Count: ' + index, 330, 380);
}
```
