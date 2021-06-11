# Homework 03: Exploring and wrangling data

Homework in which we visualized U.S. Supreme Court decisions and wrangled an example dataset.

## Files in this repository

 - [scotus.md](https://github.com/arrudafranco/Homework-3/blob/master/scotus.md) is a Markdown file showing visualizations produced of data available in the [Supreme Court Database](http://scdb.wustl.edu/), including the code necessary to produce them.
 - [dadmom.md](https://github.com/arrudafranco/Homework-3/blob/master/dadmom.md) is a Markdown file showing the process to wrangle an example dataset.

## Required packages

You should have the following packages installed:

```r
library(tidyverse)
library(gapminder)
library(rcfss)
```

[`rcfss`](https://github.com/uc-cfss/rcfss) can be installed from GitHub using the command:

```r
if (packageVersion("devtools") < 1.6) {
  install.packages("devtools")
}

devtools::install_github("uc-cfss/rcfss")
```
