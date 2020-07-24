---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
date: {{ .Date }}
categories:
- category
- subcategory
tags:
- 
- 
keywords:
- 
#thumbnailImage: //example.com/image.jpg

output:
  html_document:
    code_folding: "hide"
    fig_height: 5
    fig_width: 10
    toc: yes
    toc_depth: 3
    toc_float: yes

---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo=F, fig.align = "center", message=F, warning=F, fig.height = 5, fig.widget = 5, cache=T, dpi = 300)
```

---

<!--more-->
