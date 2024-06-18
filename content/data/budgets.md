---
title: "Municipal Budget Reports" 
date: 2024-06-17
lastmod: 2024-06-17
tags: ["corruption","Philippines","machine learning"]
author: ["Blaine Finstein"]
summary: "This dataset contains budget reports from the past 12 years for all municipal and city governments in the Philippines."
editPost:
    URL: "https://github.com/blainefinstein/crowdout-and-corruption"
    Text: "GitHub repository"
showToc: true
disableAnchoredHeadings: false

---

## Overview

This dataset contains budget reports from the past 12 years for all municipal and city governments in the Philippines.

---

## Download

---

## Source of data

Philippine budget reports are published yearly by the Commission on Audit and publicly available [here](https://www.coa.gov.ph/reports/annual-audit-reports/aar-local-government-units/).

---

## Description of variables

---

## Using data with R

All data processing has been conducted in R using RStudio, which is available for download [here](https://posit.co/download/rstudio-desktop/).

### Start R:

Load the necessary packages.

```r
library(readr)
library(modelsummary)
```

#### Read data:

Read data.

```r
dat <- readr(path = "file path here")
```

##### Display summary statistics:

Modelsummary is an excellent package for computing and displaying summary statistics.

```r
datasummary_skim(dat)
```
