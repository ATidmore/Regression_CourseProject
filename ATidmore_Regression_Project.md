---
title: "Analysis of Factors Contributing to Vehicle MPG"
author: "Austin Tidmore"
date: "September 26, 2015"
output: pdf_document
---

As an analyst for Motor Trend magazine I am providing this report as an analysis of factors contributing to vehicle fuel efficiency (i.e. "MPG"). The analysis herein has been compiled from a dataset of 32 vehicles from 1973-74. 

My research found that while a Manual transmission (as opposed to Autmatic) results in significantly better fuel efficiency, there were other variables in the data which explain the relationship with MPG better than just transmission type.

REVISIT ME

# Exploring the Data


```r
summary(cars)
```

```
##      speed           dist       
##  Min.   : 4.0   Min.   :  2.00  
##  1st Qu.:12.0   1st Qu.: 26.00  
##  Median :15.0   Median : 36.00  
##  Mean   :15.4   Mean   : 42.98  
##  3rd Qu.:19.0   3rd Qu.: 56.00  
##  Max.   :25.0   Max.   :120.00
```

You can also embed plots, for example:

![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-2-1.png) 

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
