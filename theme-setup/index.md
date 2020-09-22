---
layout: page
title: Website Build
description: "Walkthrough for website build"
image:
  feature: yellowstone-complement-blue.jpg
share: true
modified: 2020-09-20
---

This website is built with GitHub Pages and Jekyll. There are two sources that deserve credit for the template design
of this site. For the site I used [William Barbour's](https://barbourww.github.io/) derivative of 
[Michael Rose's](https://mademistakes.com) `hpstr-jekyll-theme`. Michael Rose's template is available 
on [his Github](https://github.com/mmistakes/hpstr-jekyll-theme).

Please feel free to clone or download these website materials and adapt as you see fit. For A detailed set of 
instructions on using these materials see William Barbour's [theme-setup](https://barbourww.github.io//theme-setup/).
Please make sure to give credit to Michael Rose (the original template) and if using my derivative, William Barbour as well.

The only major change I made to the template was I added a publication list on the research
page. To use this feature simply replace the _bibliography/refs.bib file with your
own latex bibliography file. Also make sure to include gem "jekyll-scholar" in the Gemfile,
and in _config.yml include "jekyll-scholar" in the plugins section.