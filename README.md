長庚大學 大數據分析方法 作業二
================

數值變數運算
------------

``` r
num1<-3561
num2<-5851
num1+num2
```

    ## [1] 9412

``` r
num1-num2
```

    ## [1] -2290

``` r
num1*num2
```

    ## [1] 20835411

``` r
round(num1/num2, digits = 2)
```

    ## [1] 0.61

檢查總覽資料
------------

``` r
str(iris)
```

    ## 'data.frame':    150 obs. of  5 variables:
    ##  $ Sepal.Length: num  5.1 4.9 4.7 4.6 5 5.4 4.6 5 4.4 4.9 ...
    ##  $ Sepal.Width : num  3.5 3 3.2 3.1 3.6 3.9 3.4 3.4 2.9 3.1 ...
    ##  $ Petal.Length: num  1.4 1.4 1.3 1.5 1.4 1.7 1.4 1.5 1.4 1.5 ...
    ##  $ Petal.Width : num  0.2 0.2 0.2 0.2 0.2 0.4 0.3 0.2 0.2 0.1 ...
    ##  $ Species     : Factor w/ 3 levels "setosa","versicolor",..: 1 1 1 1 1 1 1 1 1 1 ...

輸出系統現在日期
----------------

``` r
dateBook<-Sys.Date()
dateBook
```

    ## [1] "2017-03-20"

字串比大小
----------

``` r
"A">"a"
```

    ## [1] TRUE

``` r
"B">"A"
```

    ## [1] TRUE

運作環境資訊擷取
----------------

``` r
sessionInfo()
```

    ## R version 3.3.2 (2016-10-31)
    ## Platform: x86_64-w64-mingw32/x64 (64-bit)
    ## Running under: Windows 10 x64 (build 14393)
    ## 
    ## locale:
    ## [1] LC_COLLATE=Chinese (Traditional)_Taiwan.950 
    ## [2] LC_CTYPE=Chinese (Traditional)_Taiwan.950   
    ## [3] LC_MONETARY=Chinese (Traditional)_Taiwan.950
    ## [4] LC_NUMERIC=C                                
    ## [5] LC_TIME=Chinese (Traditional)_Taiwan.950    
    ## 
    ## attached base packages:
    ## [1] stats     graphics  grDevices utils     datasets  methods   base     
    ## 
    ## loaded via a namespace (and not attached):
    ##  [1] backports_1.0.5 magrittr_1.5    rprojroot_1.2   tools_3.3.2    
    ##  [5] htmltools_0.3.5 yaml_2.1.14     Rcpp_0.12.10    stringi_1.1.2  
    ##  [9] rmarkdown_1.3   knitr_1.15.1    stringr_1.2.0   digest_0.6.12  
    ## [13] evaluate_0.10
