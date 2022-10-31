---
title: "Introduction to R-spatial with geocomputation with R"
published: true
morea_id: experience-spatial-r-gis-1
morea_type: experience
morea_summary: "spatial packages, terra,  sf,  dplyr"
morea_sort_order: 1
morea_labels:
  - Reference
  - Textbook
---




Here you find an appetizer. Work your way through the foundations and start with phic data
and are important and should be at least cross-read and present. [Geographic Data in R](https://geocompr.robinlovelace.net/intro.html). Also the chapters Geographic data in R, Attribute data operations, Spatial data operations, Geometry operations, Reprojecting geogra.      

<iframe width='100%' height='300' src='https://rdrr.io/snippets/embed/?code=library(%22sf%22)%0Alibrary(%22spData%22)%0Aplot(world)%20%20%20%20%20%20%20%20%20%20%20%20%20%20%0Aplot(world%5B%22continent%22%5D%2C%20reset%20%3D%20FALSE)%0Acex%20%3D%20sqrt(world%24pop)%20%2F%2010000%0Aworld_cents%20%3D%20st_centroid(world%2C%20of_largest%20%3D%20TRUE)%0Aplot(st_geometry(world_cents)%2C%20add%20%3D%20TRUE%2C%20cex%20%3D%20cex)' frameborder='0'></iframe>





