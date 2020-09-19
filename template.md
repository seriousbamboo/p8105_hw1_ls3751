p8105\_hw1\_ls3751
================

*Load required packages*

``` r
library(tidyverse)
library(palmerpenguins)
```

## Problem 1

Here’s a **code chunk** that samples from a *normal distribution*:

``` r
samp = rnorm(100)
length(samp)
```

    ## [1] 100

## Problem 2

#### 2.1 Load the pengins dataset

``` r
data("penguins", package = "palmerpenguins")
```

#### 2.2 Description of the penguins dataset

##### Overview

> The penguins dataset has 8 variables, including species, island,
> bill\_length\_mm, bill\_depth\_mm, flipper\_length\_mm, body\_mass\_g,
> sex, year.

  - The variable **species** is a factor variable, with 3 levels:
    Adelie, Chinstrap, Gentoo.
  - The variable **island** is a factor variable, with 3 levels: Biscoe,
    Dream, Torgersen.
  - The variable **bill\_length\_mm** is a numeric variable (Max: 59.6,
    Min: 32.1, Mean: 43.92, Median: 44.45).
  - The variable **bill\_depth\_mm** is a numeric variable (Max: 21.5,
    Min: 13.1, Mean: 17.15, Median: 17.3).
  - The variable **flipper\_length\_mm** is a integer variable (Max:
    231, Min: 172, Mean: 200.92, Median: 197).
  - The variable **body\_mass\_g** is a integer variable (Max: 6300,
    Min: 2700, Mean: 4201.75, Median: 4050).
  - The variable **sex** is a factor variable, with 2 levels: female,
    male.
  - The variable **year** is a integer variable (Max: 2009, Min: 2007,
    Median: 2008).

##### 

I can take the mean of the sample, too\! The mean is 0.2379025.
