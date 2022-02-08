--- 
title: "CaL Lexical Decision Task Edits"
subtitle: "for week 2"
author: "CaL Teaching Team"
date: "Tuesday 08 February 2022 at 13:55:44"
site: bookdown::bookdown_site
documentclass: book
bibliography: [book.bib, packages.bib]
url: https://cal20212022.github.io/cal_01_lex_dec_edits/
# cover-image: path to the social sharing image like images/cover.jpg
description: |
  This is for the student challenges for editing the lexical decision task experiment.
biblio-style: apalike
csl: chicago-fullnote-bibliography.csl
---


```r
file.copy('LexDecTaskCopy.psyexp', 'docs/LexDecTaskCopy.psyexp', overwrite = TRUE)
#> [1] TRUE
```


# About

This site explains the student challenges for the lexical decision task.

* First, download a copy of the PsychoPy experiment at this link
  * [**LexDecTaskCopy.psyexp**](./LexDecTaskCopy.psyexp)

* Then, complete the challenges, which are:
  1. Change the screen colour to white, and the text colour to black, throughout the experiment
  2. Increase the stimulus duration from 3 to 5 seconds
  3. Turn off feedback in the experimental (but not the practice) block.
  4. At the end, instead of having the participant press a key to end the experiment, make the experiment finish automatically after 2 seconds
