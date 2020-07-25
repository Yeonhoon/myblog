---
title: R markdown 연습
author: JYH
date: '2020-07-25'
slug: r-markdown-연습
categories:
  - R
tags: []
keywords:
  - 
summary: R markdown(.Rmarkdown) 연습 중입니다. 건드리지 마세요. 얘는 .Rmd랑 다른 놈입니다.
thumbnailImage: https://lh3.googleusercontent.com/proxy/Hh9BKsUlNZTbV3Jd0oQs73vZaSeMcosSMovz0nZrx6iC4KVNqs0oTX1CHN66QUq0zrB3NEm2X0bIHrE_N1EfSdRmt-fkco19Osr0TT9TM3JqhCMhgdXwsUsc78Rnx9Wyy_w
thumbnailImagePosition: right
output:
  html_document:
    code_folding: hide
    fig_height: 5
    fig_width: 10
    toc: yes
    toc_depth: 3
    toc_float: yes
---



---

<!--more-->

{{< wide-image src="//d1u9biwaxjngwg.cloudfront.net/tag-plugins-showcase/car-1.jpg" title="Mercedes SLS" >}}

<!-- toc -->

# Alert

Read documentation to know how to use [Alert tag](https://github.com/kakawait/hugo-tranquilpeak-theme/blob/master/docs/user.md#alert)

{{< alert info >}}
이것은 정보입니다.
{{< /alert >}}

{{< alert success >}}
정답입니다!
{{< /alert >}}

{{< alert warning >}}
조심하세요.
{{< /alert >}}

{{< alert danger >}}
위험합니다.
{{< /alert >}}

# Block Quote

Read documentation to know how to use [Block Quote tag](https://hexo.io/docs/tag-plugins.html#Block_Quote)

**Normal blockquote**

> Praesent diam elit, interdum ut pulvinar placerat, imperdiet at magna.

**Quote from a book**

{{< blockquote "David Levithan" "Wide Awake" >}}
Do not just seek happiness for yourself. Seek happiness for all. Through kindness. Through mercy.
{{< /blockquote >}}


```r
library(tidyverse)
head(mtcars)
```

```
##                    mpg cyl disp  hp drat    wt  qsec vs am gear carb
## Mazda RX4         21.0   6  160 110 3.90 2.620 16.46  0  1    4    4
## Mazda RX4 Wag     21.0   6  160 110 3.90 2.875 17.02  0  1    4    4
## Datsun 710        22.8   4  108  93 3.85 2.320 18.61  1  1    4    1
## Hornet 4 Drive    21.4   6  258 110 3.08 3.215 19.44  1  0    3    1
## Hornet Sportabout 18.7   8  360 175 3.15 3.440 17.02  0  0    3    2
## Valiant           18.1   6  225 105 2.76 3.460 20.22  1  0    3    1
```

