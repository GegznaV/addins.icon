
<!-- 

TO DO: 

1. Create an interactive addin, that enables to select icon:
    a. include icon preview;
    b. search posibility;
    c. icon options as in, e.g.,`icon::fa()`
    d. "remembers" several last used icons.

-->

<!-- README.md is generated from README.Rmd. Please edit that file -->

[![MIT
licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/addins.icon)](https://cran.r-project.org/package=addins.icon)
[![GitHub
version](https://img.shields.io/badge/GitHub-0.0.1-brightgreen.svg)](https://github.com/GegznaV/addins.icon)
[![Travis-CI Build
Status](https://travis-ci.org/GegznaV/addins.icon.png?branch=master)](https://travis-ci.org/GegznaV/addins.icon)
[![Updated-on](https://img.shields.io/badge/Updated%20on-2018--08--27-yellowgreen.svg)](/commits/master)
<!-- [![Research software impact](http://depsy.org/api/package/cran/addins.icon/badge.svg)](http://depsy.org/package/r/addins.icon) -->

<!-- [![Rdoc](http://www.rdocumentation.org/badges/version/addins.icon)](http://www.rdocumentation.org/packages/addins.icon) -->

<!--

-->

-----

<img src="http://gegznav.github.io/addins.icon/logo.png" align="right" width="15%" height="15%"/>

# R package **addins.icon**

Package `addins.icon` is an *R* package that provides a set of *RStudio*
addins for *R Markdown*. The main purpose of this package is to
alleviate learning process of *R Markdown* syntax.

<!-- 
1) **format text in R Markdown documents**: 
    - **enclose** either selected text or selected rows with special symbols and text gets inerpreted in a special way when rendered with R Markdown (e.g., converts "bold" into "\*\*bold\*\*"
that is interpreted as "**bold**").
2) **insert** text (e.g., operators `%>%`, `<<-`, `%$%`) at the cursor position; 
3)  **replace** symbols in selected
pieces of text (e.g., convert backslashes to forward slashes which results 
in strings like `"c:\data\"` converted into `"c:/data/"`). 
-->

## Install package

<!-- Install released version from CRAN: -->

<!-- ```{r Install package from CRAN, eval=FALSE} -->

<!-- install.packages("addins.icon") -->

<!-- ``` -->

Install development version from GitHub:

``` r
if (!require(devtools)) 
    install.packages("devtools")

devtools::install_github("GegznaV/addin.tools")
devtools::install_github("GegznaV/addins.icon")
```

<!-- Recommended workflow and a few examples -->

<!-- ----------------------------------------------------- -->

<!-- Get started online http://gegznav.github.io/addins.icon/articles/v1_workflow.html -->

<!-- And offline: -->

<!-- ```{r, eval=FALSE} -->

<!-- vignette("v1_workflow", package = "addins.icon") -->

<!-- ``` -->

<!-- browseVignettes("addins.icon") -->

# How to use the add-ins

Below you can find a few examples how to use the add-ins of the package.

## Convert text into headings

![**Demonstration 1: headings.** Place a cursor with a mouse and use a
necessary
add-in.](https://raw.githubusercontent.com/GegznaV/addins.icon/master/docs/figs/demo-headings-1.gif)

<br>

![**Demonstration 2: headings.** Notice that, if needed, a blank line
above the selection is
added.](https://raw.githubusercontent.com/GegznaV/addins.icon/master/docs/figs/demo-headings-2.gif)

<br><br>

## Basic text formatting

![**Demonstration 3: basic formatting.** Before using this type of
add-in, select a piece of text that should be
formatted.](https://raw.githubusercontent.com/GegznaV/addins.icon/master/docs/figs/demo-formatting-1.gif)

<br><br>

## Create lists

![**Demonstration 4: lists.** The lists can be numbered and unnumbered.
They can have several
levels.](https://raw.githubusercontent.com/GegznaV/addins.icon/master/docs/figs/demo-lists-1.gif)

# Pandoc’s Markdown

*R Markdown* syntax is based on Pandoc’s Markdown syntax. Read more if
you need more advanced formatting options:

  - <https://pandoc.org/MANUAL.html#pandocs-markdown>

-----

More information at <http://gegznav.github.io/addins.icon/>
