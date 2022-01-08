---
title: 'Academic Paper'
subtitle: 'An Academic Paper'
author: 'Orion Leidl Wilson'
date: 'January 8th 2022'
bibliography: references.bib # See https://github.com/jgm/pandoc-citeproc/blob/master/man/pandoc-citeproc.1.md for more formats.

toc-title: 'Table of Contents'
toc: false # Table of contents
toc_depth: 2
lof: false # List of figures

documentclass: turabian-researchpaper # See https://www.ctan.org/topic/class
classoption: [onecolumn, openany]
geometry: [letterpaper]

# LaTeX snippets
header-includes:
  - |
    ```{=latex}
    % keep figures where there are in the text
    \usepackage{float} 
    \floatplacement{figure}{H}
    ```
---

## Title

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis tristique enim eu lacus semper, sed ultrices dui volutpat. Sed hendrerit purus non sapien accumsan, ut dictum elit tristique. Vestibulum in justo ante. Ut vitae dignissim nunc. Duis elementum dui at odio sollicitudin maximus. Donec mollis ac risus non sollicitudin. Etiam id finibus est. Aenean vel nunc id ligula tincidunt mattis. Duis sapien eros, laoreet sed viverra et, volutpat ac mi. [@jones2016]

Maecenas vel cursus eros. Donec a lobortis justo. Praesent pulvinar augue nec rhoncus porta. In ut purus nec felis euismod fringilla non eu risus. Proin eros ex, pellentesque a sodales in, elementum id quam. Etiam bibendum dolor eget diam posuere, quis congue est pretium. Nullam sit amet ipsum at est iaculis ullamcorper. Donec lorem sapien, feugiat ac nunc ut, pretium vehicula leo. In fermentum pretium justo, id dictum justo placerat et. Nullam euismod efficitur erat. Sed convallis enim quis sapien egestas, sit amet pretium metus fermentum. Donec scelerisque tincidunt nisl in pellentesque. Fusce ex leo, gravida eget enim nec, commodo feugiat tellus.[@jones2016]

Duis et metus non ex gravida sagittis dictum malesuada nunc. Praesent dictum lectus tincidunt elit sagittis, quis fringilla sapien sodales. Nulla facilisi. Donec quis vehicula erat. Suspendisse potenti. Phasellus dolor velit, efficitur non arcu ut, venenatis efficitur velit. Etiam a sem lectus. Maecenas consectetur ante ac dolor fringilla, in vestibulum purus gravida. Proin ipsum lacus, tristique id accumsan vitae, tempor ac sem. Integer vel nisl in leo mollis euismod vitae eu eros.[@sahle2015]

Donec eu fringilla leo. Praesent quis feugiat ante, ut condimentum sem. Nullam vel felis enim. Integer commodo molestie libero, nec sollicitudin elit convallis sit amet. Sed mattis ullamcorper auctor. Ut posuere turpis eu massa bibendum, quis interdum nunc vulputate. Suspendisse condimentum, arcu sed dapibus ornare, dui purus pulvinar felis, a ultricies neque elit condimentum nisi. Nunc diam ante, tempor in leo sed, ultrices ultrices leo. Morbi eget augue ac purus aliquam porta. Vivamus venenatis elit accumsan lacus egestas viverra. Pellentesque turpis nisl, iaculis sit amet pulvinar ut, faucibus eu nulla. Integer eu lectus in nisl vulputate pharetra non elementum lectus.[@sahle2015]

Mauris rutrum dignissim ante nec rutrum. Duis convallis neque lectus, id mollis nunc fermentum in. Nulla in ornare sapien. Nulla diam elit, iaculis non lorem ut, malesuada hendrerit metus. Aliquam nulla libero, pretium in vehicula non, porta non odio. In eget auctor enim. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam lectus elit, fermentum et diam at, finibus condimentum augue.[@lorenz2015]

## References
