
<!-- README.md is generated from README.Rmd. Please edit that file -->

# unhcrtemplate

<!-- badges: start -->

[![Project Status: Active – The project has reached a stable, usable
state and is being actively
developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
[![R-CMD-check](https://github.com/unhcr-dataviz/unhcrtemplate/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/unhcr-dataviz/unhcrtemplate/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

## Overview

`unhcrtemplate` provides a custom [pkgdown](https://pkgdown.r-lib.org)
template for UNHCR packages. Please don’t use it for your own package.

Inspired by [tidytemplate](https://github.com/tidyverse/tidytemplate/)
and [rotemplate](https://github.com/ropensci-org/rotemplate).

## Templates

For all sites, ensure that `DESCRIPTION` contains:

    Config / Needs / website:unhcr - dataviz / unhcrtemplate

and that `_pkgdown.yml` contains:

``` yaml
template:
  package: unhcrtemplate
  bootstrap: 5
```
