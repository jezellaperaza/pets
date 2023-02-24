
<!-- README.md is generated from README.Rmd. Please edit that file -->

# pets

The goal of pets is to provide a simple means for people to express
their feelings about pets. At present, the package only contains one
function: `cats()`.

## Installation

You can install the development version of pets like so:

``` r
if(!require("devtools")) {
  install.packages("devtools")
}
devtools::install_github("jezellaperaza/pets")
```

## Example

Here are two simple examples that allow you to express your feelings
about cats.

``` r
library(pets)

## if you like cats
cats(TRUE)
#> [1] "I love cats!"

## if you don't like cats
```

cats(FALSE)
