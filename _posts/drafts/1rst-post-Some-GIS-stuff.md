---
title: "Primer post: Some GIS stuff"
date: 2021-05-01T15:34:30-04:00
header:
  overlay_image: /assets/images/agua2.png
  caption: "Photo credit: pablo mandolesi"
  actions:
    - label: "Learn more"
      url: "https://github.com/"
categories:
  - Layout
tags:
  - GIS
  - image
  - layout
---

Esa imagen es un trabajo bastante grande que hice sobre teledeteccion de espejos de agua en la provincia de buenos aires. El trabajo se hizo mayormente en ENVI. El periodo de estudio abarcó 23 años desde 1996 a 2019, se procesaron 2 imagenes por año, buscando captar las temporadas secas y humedas, siempre que la disponibilidad de imagenes libres de nubes lo permitiera(despues busco los detalles de la superficies y cantidad de imagens procesadas). Por medio de una simple matematica de bandas se haci la clasificación binaria entre "agua" y "no agua", se definia un umbral  y el analisis por observación de cada imagen

You'll find this post in your `_posts` directory. 

Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

```python
def print_hi(name):
    print('Hi, '+ name)
    
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
```