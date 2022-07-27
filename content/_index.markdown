---
title: Home
---


[<img src="https://simpleicons.org/icons/github.svg" style="max-width:15%;min-width:40px;float:right;" alt="Github repo" />](https://github.com/yihui/hugo-xmin)

# Raclette 2 Project

# Does Imagery share similar neural mechanisms with the actual movement?

## Abstract

Imagined motor movement (“Imagery”) plays a crucial role in preparing actual movements and learning of complex motor skills. Miller et al (2010) have shown that the spatial distribution of activities in the primary motor area for imagery and actual movements does not overlap in high frequency (76-100Hz), but in low frequency band (8-32Hz). However, the neural substrates and neural representations of imagery still remain largely unknown.  

The present study examined whether imagery shares similar mechanisms with actual movement at different levels. With electrocorticography (ECoG) dataset in seven human subjects during actual movement and kinesthetic imagery of the same motion type (hand & tongue), we investigated the channel-level mechanisms by looking at the differences between actual movement and imagery in the power of specific frequency bands (i.e. alpha/beta/gamma). Furthermore, we investigated the population-level mechanism by performing the multivariate classification and the neural trajectory analysis. Specifically, we trained the classifier on actual movement/imagery and tested it on imagery/actual movement to see whether the decoding can be generalized to each other. Also, using t-SNE, we examined whether the imagery and actual movement activated in the same sequence at the neural subspace. 
Our results (may) suggest that in addition to common neural substrates shared by imagery and actual movements, there also exists imagery-specific neural substrates at both the channel level and the population level.

Keyword: electrocorticography (ECoG) | time frequency analysis | multivariate classification | neural trajectory analysis 


<!-- in this way you could embed a google slide -->
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQ0kKJB_M_bQMyuAQMtbWsVwZMUk0nbnsgRSf3-B3gWh_sPxFId-fI7mWnKUdkwBmQB36UXy_Z4tq92/embed?start=false&loop=false&delayms=30000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>


<!-- in this way you could insert a code -->
```bash
find . -not -path '*/exampleSite/*' \( -name '*.html' -o -name '*.css' \) | xargs wc -l
```

```
       5 ./layouts/404.html
      12 ./layouts/_default/single.html
      20 ./layouts/_default/list.html
      13 ./layouts/_default/terms.html
       0 ./layouts/partials/foot_custom.html
       0 ./layouts/partials/head_custom.html
       9 ./layouts/partials/footer.html
      20 ./layouts/partials/header.html
      51 ./static/css/style.css
       7 ./static/css/fonts.css
     137 total
```

I can certainly further reduce the code, for example, by eliminating the CSS, but I believe a tiny bit of CSS can greatly improve readability. You cannot really find many CSS frameworks that only contain 50 lines of code.

Although it is a minimal theme, it is actually fully functional. It supports pages (including the home page), blog posts, a navigation menu, categories, tags, and RSS. With [a little bit customization](https://github.com/yihui/hugo-xmin/blob/master/exampleSite/layouts/partials/foot_custom.html), it can easily support LaTeX math expressions, e.g.,

<!-- in this way you could insert a math function -->
`$${\sqrt {n}}\left(\left({\frac {1}{n}}\sum _{i=1}^{n}X_{i}\right)-\mu \right)\ {\xrightarrow {d}}\ N\left(0,\sigma ^{2}\right)$$`

<!-- in this way you could insert a video -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9RRQtNnq3s0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

All pages not under the root directory of the website are listed below. You can also visit the list page of a single section, e.g., [posts](/post/), or [notes](/note/). See the [About](/about/) page for the usage of this theme.
