
<!-- README.md is generated from README.Rmd. Please edit that file -->

# pets

<!-- badges: start -->

<!-- badges: end -->

# Background

The `{pets}` package was designed to allow people to express their
feelings about pets. At present, the package is rather cat-centric, in
that it only contains one function: `cats()`.

# Usage

To use `{pets}`, first load the package and then call the function
`cats()` with a logical/boolean argument. For example,

``` r
## load pets package
library(pets)

## if you love cats
cats(TRUE)
#> [1] "I love cats!"

## if you're not a big fan of cats
cats(FALSE)
#> [1] "I am not a cat person."
```

## Installation

You can install the development version from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("markusmin/pets")
```

## Error reporting

If you find an error or bug, please file an issue.

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(pets)
## basic example code
```
