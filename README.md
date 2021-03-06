
[![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/epiflows)](https://cran.r-project.org/package=epiflows)

Welcome to the *epiflows* package!
==================================

`epiflows` is a package for predicting and visualising spread of infectious diseases based on flows between geographical locations, e.g., countries. `epiflows` provides functions for calculating spread estimates, handling flow data, and visualization.

Installing the package
----------------------

To install the current stable, CRAN version of the package, type:

``` r
install.packages("epiflows")
```

To benefit from the latest features and bug fixes, install the development, *github* version of the package using:

``` r
devtools::install_github("reconhub/epiflows")
```

Note that this requires the package *devtools* installed.

What does it do?
================

The main features of the package include:

-   `epiflows`: an S3 class for storing flow data, as well as country metadata
-   `make_epiflows`: a constructor for `epiflows`
-   `add_coordinates`: add latitude/longitude to the linelist in an `epiflows` object using `ggmap::geocode()`
-   `fn_number_cases_spread`: calculate estimates (point estimate and 95% CI) for disease spread from flow data
-   `get_flow_data`: return flow data to and/or from specified location
-   `get_location_data`: return metadata for specified location(s)
-   `x[i]`: subset an `epiflows` object to location(s) *i*
-   `plot`: plot flows from an `epiflows` object on a *leaflet* world map
-   `print`: print a summary for an `epiflows` object

Resources
=========

Vignettes
---------

An overview and examples of *epiflows* are provided in the vignettes:

...

Getting help online
-------------------

Bug reports and feature requests should be posted on *github* using the [*issue*](http://github.com/reconhub/epiflows/issues) system. All other questions should be posted on the **RECON forum**: <br> <http://www.repidemicsconsortium.org/forum/>

Contributions are welcome via **pull requests**.

Please note that this project is released with a [Contributor Code of Conduct](CONDUCT.md). By participating in this project you agree to abide by its terms.
