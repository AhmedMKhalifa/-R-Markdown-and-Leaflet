---
title: "Ahmed Khalifa"
output:
  html_document: default
  pdf_document: default
date: "Nov 11, 2019"
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```



```{r}
my_map <- leaflet() %>%
  addTiles() %>%  
  addMarkers(lng =30.029299, lat= 31.122983, popup="Alexandria")
my_map 
```
