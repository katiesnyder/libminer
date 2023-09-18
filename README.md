
<!-- README.md is generated from README.Rmd. Please edit that file -->

# libminer

<!-- badges: start -->
<!-- badges: end -->

The goal of libminer is to provide an overview of your R library set up.
It is a toy package created as part of a workship and not meant for
serious use!

## Installation

You can install the development version of libminer from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("katiesnyder/libminer")
```

## Example

To get a count of installed packages in each of your libraries,
optionally with the total size, use `lib_summary()`.

``` r
library(libminer)
## basic example code
lib_summary(sizes = TRUE)
#>                                                                       Library
#> 1                                          C:/Program Files/R/R-4.3.0/library
#> 2 C:/Users/posituser/AppData/Local/Temp/2/Rtmp4aHvn7/temp_libpath180464e52aea
#>   n_packages  lib_size
#> 1        400 825597505
#> 2          1     13360
```
