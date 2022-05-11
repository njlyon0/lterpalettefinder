
<!-- README.md is generated from README.Rmd. Please edit that file -->

# lterpalettefinder

<!-- badges: start -->
<!-- badges: end -->

The goal of `lterpalettefinder` is to provide high quality color
palettes derived from photos at LTER sites. This allows users to create
beautiful graphics that have close visual ties to photos from the places
where data were collected. This package also allows users to generate
their own palettes from any photo (.PNG only) if the current palettes in
the function do not meet their needs.

## Installation

You can install the development version of `lterpalettefinder` from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("lter/lterpalettefinder")
```

## Functions

This package currently includes a few functions

-   **`palette_find()`** returns “official” palette(s) that we have
    already created that criteria you specify

-   **`palette_extract()`** extracts 25 colors’ hexadecimal codes from a
    picture of your choosing (only PNG, TIFF, and JPEG formats are
    currently supported)

-   **`palette_sort()`** sorts output of `palette_extract()` by hue and
    saturation to approximate how human eyes group colors (this can be
    done either inside `palette_extract()` with an optional argument or
    separately)

-   **`palette_demo()`** creates an exploratory graph of the colors
    returned by either `palette_extract()` or `palette_sort()` and
    provides an option to export that plot if desired

## Palette Examples

This part of the README is in development so stay tuned!
