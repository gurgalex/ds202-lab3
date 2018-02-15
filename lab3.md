---
title: "lab3"
author: "Alex Gurganus"
date: "February 15, 2018"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```


```{r}
data(happy, package="productplots")
head(happy)
```

load serialized exerpt from cource website
```{r}
HAPPY <- readRDS("data/HAPPY.rds")
```