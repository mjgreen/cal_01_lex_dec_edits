--- 
title: "CaL Lexical Decision Task Edits"
subtitle: "for week 2"
author: "the CaL Teaching Team"
date: "Friday 18 February 2022 at 18:58:06"
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
file.copy('LexDecTaskCopy.zip', 'docs/LexDecTaskCopy.zip', overwrite = TRUE)
#> [1] TRUE
```


# About

This site explains the student challenges for the lexical decision task.

::: {.rmdnote}
Make sure you have installed `PsychoPy` on your own computer from this link before attempting the challenges: [**PsychoPy download**](https://www.psychopy.org/download.html) 
:::

::: {.rmdnote}
* Download a copy of the PsychoPy experiment at this link
  * [**LexDecTaskCopy.zip**](./LexDecTaskCopy.zip)
  
* Extract the files from that zip folder (right click -> extract all on Windows)

![](images/zipFileContents.png){width="100%"}

* Double click on `LexDecTaskCopy.psyexp`
:::

::: {.rmdnote}
* Complete the challenges, which are:
  1. Increase the stimulus duration from 3 to 5 seconds - see Chapter \@ref(stimdur) for the solution
  2. Change the screen colour to white, and the text colour to black, throughout the experiment- see Chapter \@ref(colours) for the solution
  3. Turn off feedback in the experimental (but not the practice) block - see Chapter \@ref(feedback) for the solution
:::
