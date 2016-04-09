---
title       : "Final Project for Developing Data Products"
subtitle    : "Shiny App Development: Global Phones by Regions"
author      : Remydozie
date        : '09 April, 2016'
job         : Student, Cousera Data Science Specialization 
framework   : io2012 #{io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Content

1. Introduction
2. Steps for Development of ui.R Codes for the Shiny App
3. Steps for Development of server.R Codes for the Shiny App
4. Conclusion

---  
## Introduction

### This presentation is a brief on creation of a Shiny application.

### The presentation also provides a hpyperlink of the application as deployed on Rstudio's servers.

### The application created is about a graphical view world telepnones statistics with datafrom R Studio Library:The World's Telephones Prepared by AT&T (1961).

---
## Steps for Development of ui.R Codes for the Shiny App

1. Load neccessary parkages 

2. Indicated data(library) for the App

3. Define the overall UI(fluid Boostrapp layout was used)

4. Povide the page a title ("Telephones  by World Regions")
    
5. Generate a row with a sidebar & Define the sidebar with one input

6. Create a spot for the barplot
     
7. Actual code could be found on the Github link below

https://github.com/remydozie/DataProducts/blob/master/ui.R

---
## server.R Codes for the Shiny App

1. Load neccessary parkages 

2. Indicated data(library) for the App

3.  Define a server for the Shiny app

4. Fill in the spot created on ui.R for a plot

5. Render a barplot

6. Actual code could be found on the Github link below
   
https://github.com/remydozie/DataProducts/blob/master/server.R

---
## Conclusion 

1. Shiny App for Developing Data Products Cousera Course

2. This app is adopted from app gallery of Shiny by Rstudio (Jeff Allen).The Gitnub link to the App is provided below:

3. https://remydozie.shinyapps.io/worlphones

---



