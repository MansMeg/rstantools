<a href="http://mc-stan.org">
<img src="https://raw.githubusercontent.com/stan-dev/logos/master/logo.png" width=200 alt="Stan Logo"/>
</a>

# rstantools

[![Travis-CI Build Status](https://travis-ci.org/stan-dev/rstantools.svg?branch=master)](https://travis-ci.org/stan-dev/rstantools)
[![codecov](https://codecov.io/gh/stan-dev/rstantools/branch/master/graph/badge.svg)](https://codecov.io/gh/stan-dev/rstantools)
[![CRAN_Status_Badge](http://www.r-pkg.org/badges/version/rstantools?color=blue)](http://cran.r-project.org/web/packages/rstantools)

 The __rstantools__ package provides tools for developing R packages interfacing with [Stan](http://mc-stan.org/).   
 Guidelines for developers are included with the package as a vignette:

* [Guidelines for Developers of R Packages Interfacing with Stan](https://cran.r-project.org/package=rstantools/vignettes/developer-guidelines.html)

## Installation


* Install from CRAN:

```r
install.packages("rstantools")
```

* Install latest development version from GitHub (requires [devtools](https://github.com/hadley/devtools) package):

```r
if (!require("devtools"))
  install.packages("devtools")
  
devtools::install_github("stan-dev/rstantools", build_vignettes = TRUE)
```

## Getting help

* [File an issue on GitHub](https://github.com/stan-dev/rstantools/issues)
* [Ask a question at The Stan Forums](http://discourse.mc-stan.org)
