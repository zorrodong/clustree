clustree <img src="man/figures/logo.png" align="right" />
=======================================================

[![Project Status](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)
[![Lifecycle](https://img.shields.io/badge/lifecycle-maturing-blue.svg)](https://www.tidyverse.org/lifecycle/#maturing)
[![Travis-CI Build Status](https://travis-ci.org/lazappi/clustree.svg?branch=master)](https://travis-ci.org/lazappi/clustree)
[![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/lazappi/clustree?branch=master&svg=true)](https://ci.appveyor.com/project/lazappi/clustree)
[![Coverage Status](https://img.shields.io/codecov/c/github/lazappi/clustree/master.svg)](https://codecov.io/github/lazappi/clustree?branch=master)
[![CRAN Status](http://www.r-pkg.org/badges/version/clustree)](https://cran.r-project.org/package=clustree)
[![CRAN Monthly Downloads](https://cranlogs.r-pkg.org/badges/clustree)](https://cran.r-project.org/package=clustree)
![CRAN Downloads](http://cranlogs.r-pkg.org/badges/grand-total/clustree)

Deciding what resolution to use can be a difficult question when approaching a
clustering analysis. One way to approach this problem is to look at how samples
move as the number of clusters increases. This package allows you to produce
clustering trees, a visualisation for interrogating clusterings as resolution 
increases.

## Installation

You can install the release version of clustree from CRAN with:

``` r
install.packages("clustree")
```

If you want to use the development version that can be installed from GitHub
using the `remotes` package:

``` r
# install.packages("remotes")
remotes::install_github("lazappi/clustree")
```

To also build the vignettes use:

``` r
# install.packages("remotes")
remotes::install_github("lazappi/clustree", dependencies = TRUE,
                         build_vignettes = TRUE)
```

**NOTE:** Building the vignettes requires the installation of additional
packages.

## Documentation

The documentation for clustree is available from CRAN at 
https://cran.r-project.org/package=clustree.

To view the vignette and all the package documentation for the development
version visit http://lazappi.github.io/clustree.

## Citing clustree

If you use clustree or the clustering trees approach in your work please cite
our publication ["Zappia L, Oshlack A. Clustering trees: a visualization for 
evaluating clusterings at multiple resolutions. Gigascience. 2018;7. 
DOI:gigascience/giy083][paper].

```
citation("clustree")
 
   Zappia L, Oshlack A. Clustering trees: a visualization for
   evaluating clusterings at multiple resolutions. Gigascience.
   2018;7. DOI:gigascience/giy083
 
A BibTeX entry for LaTeX users is
 
   @Article{,
     author = {Luke Zappia and Alicia Oshlack},
     title = {Clustering trees: a visualization for evaluating clusterings at
              multiple resolutions},
     journal = {GigaScience},
     volume = {7},
     number = {7},
     month = {jul},
     year = {2018},
     url = {http://dx.doi.org/10.1093/gigascience/giy083},
     doi = {10.1093/gigascience/giy083},
   }
```

## Contributors

Thank you to everyone who has contributed code to the clustree package:

* @andreamrau - added the `edge_arrow_ends` option
* @mojaveazure - added support for Seurat v3 objects

[paper]: https://doi.org/10.1093/gigascience/giy083
