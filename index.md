---
title       : Coursera Developing Data Products
subtitle    : Course Project
author      : Timo Grossenbacher
job         : Data journalist
framework   : revealjs        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : default      # 
revealjs:
  theme: default
  transition: none
  center: "true"
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

###  Coursera Developing Data Products Course Project

## An interactive, exploratory analysis of election results

Timo Grossenbacher

[@grssnbchr](http://twitter.com/grssnbchr)

Presentation available under [grssnbchr.github.io/cddp](grssnbchr.github.io/cddp)


---

### About me

Data journalist for [SRF Data](http://srf.ch)


---


### Swiss Federal Elections 2015

.fragment Goal: We need a way to find out which parties are strongest in which regions (districts).

.fragment Shiny is the way to go! 

---

### Prototype:

<img src="assets/img/screen.png" width="600">

The final application will have 1551 district-year combinations: 11 years, 141 districts.

---

#### One last hint:

### Automate EVERYTHING!

<img src="assets/img/automate.gif" width="600">

<small>Source: giphy.com</small>

<h3>...and make it reproducible.</h3>
