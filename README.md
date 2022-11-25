
<!-- README.md is generated from README.Rmd. Please edit that file -->

# json2aRgs

<!-- badges: start -->

[![R-CMD-check](https://github.com/VForWaTer/json2aRgs/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/VForWaTer/json2aRgs/actions/workflows/R-CMD-check.yaml)
[![codecov](https://codecov.io/github/VForWaTer/json2aRgs/branch/main/graph/badge.svg?token=aHZ4sfqKGj)](https://codecov.io/github/VForWaTer/json2aRgs)
<!-- badges: end -->

## Parse Parameters Inside a Docker Container (tool)

The function get_parameters() is intended to be used within a docker
container with a certain file structure to read keyword arguments from
the file `/in/parameters.json` automagically. The file `/src/tool.yaml`
contains specifications on these keyword arguments, which are then
passed as input to containerized R tools in the [tool-runner
framework](https://github.com/hydrocode-de/tool-runner).

A template for a containerized R tool, which can be used as a basis for
developing new tools, is available at the following URL:
<https://github.com/VForWaTer/tool_template_r>.

## Installation

You can install the development version of json2aRgs from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("VForWaTer/json2aRgs")
```
