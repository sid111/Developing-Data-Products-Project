Developing Data Products Course Project
========================================================
author: Shaaz Siddiqi
date: April 24,2016
autosize: true

Source And Purpose
==========================================================

This Shiny App is for searching and visualizating LEGO Sets information.    
The dataset is from [Rebrickable](http://rebrickable.com/) that contains the basic information of each set (set id, year, number of pieces, theme, set name).  
Data Source: http://rebrickable.com/downloads 

Initializing Lego Dataset
========================================================


```r
head(data)
```

```
                                                                     
1 function (..., list = character(), package = NULL, lib.loc = NULL, 
2     verbose = getOption("verbose"), envir = .GlobalEnv)            
3 {                                                                  
4     fileExt <- function(x) {                                       
5         db <- grepl("\\\\.[^.]+\\\\.(gz|bz2|xz)$", x)              
6         ans <- sub(".*\\\\.", "", x)                               
```

Published App On Slidify
========================================================


The Application developed for analysis of lego data set is available at [My Lego Data Analysis Application](https://sid101.shinyapps.io/Developing-Data-Products-Project/)



Github Repo Containing Scripts
========================================================

The source code server and its ui for analysis of lego data set is available at [My Developing Data Products Project Repository](https://github.com/sid111/Developing-Data-Products-Project)

