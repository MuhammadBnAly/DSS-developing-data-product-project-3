Shiny Application and Reproducible Pitch
========================================================
author: Muhammad Ali
date: 19 December 2018
autosize: true

Introduction
========================================================
- This project was created as part of the Developing Data Products course of the Coursera [Data Science Specialisation](https://www.coursera.org/specializations/jhu-data-science).

- The goal of the project is to create a web page presentation using R Markdown that features a plot created with Plotly, and to host the resulting web page on either GitHub Pages, RPubs, or NeoCities.

- This presentation adresses the second part of the course project.
The app developed for the first part of the assignment is avalilable at [Rpubs](https://rpubs.com/bnaly/rpres-3)

- Source code for ui.R and server.R files are available on the [GitHub](https://github.com/MuhammadBnAly/DSS-developing-data-product-project-3)


Code
========================================================


```r
library( graphics , ggplot2 , plotly )
library(car)
```

Plot
========================================================

Here we can see the relationship between three variables: miles per gallon (mpg), displacement (disp).

![plot of chunk unnamed-chunk-2](rpres-3-figure/unnamed-chunk-2-1.png)
