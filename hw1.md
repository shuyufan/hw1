---
title: "Homework 1"
author: '[Student Name]'
date: "01-29-2020"
output: 
  html_document:
    keep_md: yes
---



## Task 0

These are some examples for checking Armstrong numbers. 
Please remove this portion in your final submission.


```r
1 ^ 1 == 1
5 ^ 1 == 5
2 ^ 2 + 6 ^ 2 == 26
1 ^ 3 + 5 ^ 3 + 3 ^ 3 == 153
2 ^ 3 + 1 ^ 3 + 0 ^ 3 == 210
```

```
[1] TRUE
[1] TRUE
[1] FALSE
[1] TRUE
[1] FALSE
```

## Task 1


```r
is.armstrong <- function() {
  
  # body of your function goes here...
  
}
```


## Task 2

<i>
Be sure to remove chunk option `eval=FALSE` in the below code chunks
once you create function `is.armstrong()`. Do not include this italicized
text in your final submission.
</i>

#### Valid inputs


```r
is.armstrong(x = 1)
is.armstrong(x = 153)
is.armstrong(x = 154)
is.armstrong(x = c(153, 154, NA))
is.armstrong(x = c(1, 33, 999))
```

#### Invalid inputs


```r
is.armstrong(x = -2)
is.armstrong(x = 1011)
is.armstrong(x = c(pi, 6))
is.armstrong(x = "a")
```

## Task 3

Write-up goes here...
