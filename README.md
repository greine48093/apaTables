apaTables
================

Version 2.0.0

A common task faced by researchers is the creation of APA style (i.e., American Psychological Association style) tables from statistical output. In R a large number of function calls are often needed to obtain all of the desired information for a single APA style table. As well, the process of manually creating APA style tables in a word processor is prone to transcription errors. This package creates Word files (.doc files) containing APA style tables for several types of analyses. Using this package minimizes transcription errors and reduces the number commands needed by the user.

The development version of apaTables R package is hosted here on Github. Current stable version is on the CRAN, see apaTables [here.](https://cran.r-project.org/web/packages/apaTables/index.html)

### Install Stable CRAN Version

``` r
install.packages("apaTables",dep=T)

library(apaTables)
```

### Install Development Version

``` r
install.packages("devtools")

devtools::install_github("dstanley4/apaTables")

library(apaTables)
```

Tutorial
--------

You can learn how to use apaTables [here](https://dstanley4.github.io/apaTables/articles/apaTables.html).
