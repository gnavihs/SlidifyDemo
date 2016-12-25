---
title       : Fatalities and Injuries Due to Different Types Of Storms
subtitle    : 
author      : Shivang Agarwal
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
github:
  user: gnavihs
  repo: SlidifyDemo
---

## Synopsis
> Storms and other severe weather events can cause public health problems for communities and municipalities. Many severe events can result in fatalities and injuries and preventing such outcomes to the extent possible is a key concern.

> This presentation explores the U.S. National Oceanic and Atmospheric Administration's (NOAA) storm database. This database tracks characteristics of major storms and weather events in the United States, including when and where they occur, as well as estimates of any fatalities and injuries.


--- .class #id 


## Shiny Application

I found out 7 most harmful storms and summarized the number of fatalities and injuries caused by them every year since 1992 in United States of America.
Here is a brief summary of the data:


```
##       Year               Event.Type   Fatalities        Injuries      
##  Min.   :1992   EXCESSIVE HEAT:18   Min.   :  0.00   Min.   :   0.00  
##  1st Qu.:1997   FLASH FLOOD   :19   1st Qu.: 20.25   1st Qu.:  22.25  
##  Median :2002   FLOOD         :19   Median : 36.00   Median : 215.50  
##  Mean   :2002   HEAT          :13   Mean   : 57.21   Mean   : 407.25  
##  3rd Qu.:2006   LIGHTNING     :19   3rd Qu.: 57.25   3rd Qu.: 437.50  
##  Max.   :2011   TORNADO       :19   Max.   :687.00   Max.   :6163.00  
##                 TSTM WIND     :15
```

--- .class #id 

## Shiny Application
The app creates a bubble plot for year versus fatalities. Each type of storm is coloured differently. The size of the bubble indicates the number of people injured. Thus, making it a 4 dimensional plot. As you hit play on the slider, the year gets incremented and you can see the fatality impact each year by each storm(given the data is available).


--- .class #id 

### Thank You!




