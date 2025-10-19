
<!-- README.md is generated from README.Rmd. Please edit that file -->

# `{D4CAE.dashboard}`

<!-- badges: start -->

<!-- badges: end -->

## Installation

You can install the development version of `{D4CAE.dashboard}` like so:

``` r
# FILL THIS IN! HOW CAN PEOPLE INSTALL YOUR DEV PACKAGE?
```

## Run

You can prepare to run the app by running: library(“devtools”)
library(“golem”) golem::document_and_reload() source(“./dev/01_start.R”)
run_app() \# ie D4CAE_dashboard::run_app()

You can launch the application by running:

``` r
D4CAE.dashboard::run_app()
```

## About

You are reading the doc about version : 0.0.0.9000

This README has been compiled on the

``` r
Sys.time()
#> [1] "2025-10-19 20:54:30 BST"
```

Here are the tests results and package coverage:

``` r
devtools::check(quiet = TRUE)
#> ℹ Loading D4CAE.dashboard
#> ── Attaching core tidyverse packages ──────────────────────── tidyverse 2.0.0 ──
#> ✔ dplyr     1.1.4     ✔ readr     2.1.5
#> ✔ forcats   1.0.0     ✔ stringr   1.5.1
#> ✔ ggplot2   3.5.2     ✔ tibble    3.3.0
#> ✔ lubridate 1.9.4     ✔ tidyr     1.3.1
#> ✔ purrr     1.0.4     
#> ── Conflicts ────────────────────────────────────────── tidyverse_conflicts() ──
#> ✖ dplyr::filter() masks stats::filter()
#> ✖ dplyr::lag()    masks stats::lag()
#> ℹ Use the conflicted package (<http://conflicted.r-lib.org/>) to force all conflicts to become errors
#> Rows: 1820 Columns: 3
#> ── Column specification ────────────────────────────────────────────────────────
#> Delimiter: ","
#> chr (2): Timestamp, rain_station
#> dbl (1): rainfall_in_mm
#> 
#> ℹ Use `spec()` to retrieve the full column specification for this data.
#> ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.
#> Rows: 364 Columns: 2
#> ── Column specification ────────────────────────────────────────────────────────
#> Delimiter: ","
#> chr (1): Timestamp
#> dbl (1): Value
#> 
#> ℹ Use `spec()` to retrieve the full column specification for this data.
#> ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.
#> WARNING: Rtools is required to build R packages, but is not currently installed.
#> 
#> Please download and install Rtools 4.5 from https://cran.r-project.org/bin/windows/Rtools/.
#> 
#> WARNING: Rtools is required to build R packages, but is not currently installed.
#> 
#> Please download and install the appropriate version of Rtools for 4.5.1 from
#> https://cran.r-project.org/bin/windows/Rtools/.
#> Error: Could not find tools necessary to compile a package
#> Call `pkgbuild::check_build_tools(debug = TRUE)` to diagnose the problem.
```

``` r
covr::package_coverage()
#> D4CAE.dashboard Coverage: 0.00%
#> R/app_config.R: 0.00%
#> R/app_ui.R: 0.00%
#> R/run_app.R: 0.00%
```

# Warnings

# package covr not installed
