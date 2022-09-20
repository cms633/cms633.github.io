---
layout: post
published: true
category: datasets
title: Data exploration in OpenRefine of Marvel Comics & Characters Data
author: Danny Kessler
---
## Marvel Characters and Comic Books

While I was unable to download this dataset from the Canvas link, I was able to find it [online](https://datahub.io/five-thirty-eight/comic-characters#data). This data is arranged by the name of the character with the character's real name (e.g., Bruce Wayne) in parentheses. The "id" describes whether the name is a real name (public identity or secret identity). The database also describes the characters' physical characteristics, living status (e.g., "deceased character"), number of comic appearances, and when they first appeared. This dataset was fairly clean already, but I was able to remove unnecessary spacing at the end of strings as well as split the "first appearance" category into two columns (the year and month). The "year" cell was then redundant (e.g., two columns with the same year information), so I removed one of these columns. 