---
layout: post
published: true
category: updates
title: Web Scraping Activity_Elva Si
author: Elva Si
---
I used Octoparse to scrap data from Harvard Art Museum Chinese collection (https://harvardartmuseums.org/collections?culture%5B%5D=Chinese). It was pretty cool to see the software scrapping artworks' titles, URLs, images, date, and classification in seconds. However, Octoparse seemed to stop extracting data when people need to click the "load more" button to reveal more collections. Therefore, I only got 48 sets of data scrapped while there should be 5,663 works available in the museum collection. While the museum website could not show all results on one page, I wonder if I could tell the software to scrap all data with automatic scrolling. 

Of the 48 sets of data being scrapped, the exported data was already pretty clean on the Octoparse end. I could use Open Refine to further clean up the data with text facet, knowing how many items of a particular classification (calligraphy, drawing, ritual implements, sculpture, textile arts, vessels, etc.) are available in the museum collection. 