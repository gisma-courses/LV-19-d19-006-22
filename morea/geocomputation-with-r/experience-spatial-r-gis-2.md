---
title: "Introduction to R-spatial with geocomputation with R"
published: true
morea_id: experience-spatial-r-gis-2
morea_type: experience
morea_summary: "spatial packages, terra, sf - data IO"
morea_sort_order: 24
morea_labels:
  - Reference
  - Textbook
---




 The chapter [Geographic Data IO](https://geocompr.robinlovelace.net/intro.html) is of course of elementary importance for the entire reading and writing out of data and should be worked through in any case. .   

<iframe width='100%' height='300' src='https://rdrr.io/snippets/embed/?code=world3%20%3D%20sf%3A%3Ast_read(system.file(%22shapes%2Fworld.gpkg%22%2C%20package%20%3D%20%22spData%22))%0Aplot(world3%5B%22subregion%22%5D)' frameborder='0'></iframe>