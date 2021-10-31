
<!-- README.md is generated from README.Rmd. Please edit that file -->

## drat

<!-- badges: start -->
<!-- badges: end -->

This repo uses Dirk Eddelbuettel’s excellent `drat` package for creating
a personalised CRAN-like repository.

**Setup**

First install `drat` using the usual method, then run
`drat::addRepo("hfshr")` to add this repository to your list of urls.

    # install.packages("drat")
    drat::addRepo("hfshr")

**Usage**

You can now install any of my packages that are not available on CRAN
using `install.packages()`, or update one of these packages with
`update.packages()`.

**Available packages**

Last updated: 2021-10-31 10:13:28

| Package | Version | Imports                          | NeedsCompilation |
|:--------|:--------|:---------------------------------|:-----------------|
| qbr     | 0.0.2   | dplyr, htmlwidgets, rlang, shiny | no               |
