AMECO dataset
=============

This package contains the entire [European Commission Annual macro-economic (AMECO) database](http://ec.europa.eu/economy_finance/db_indicators/ameco/index_en.htm) in a format amenable to analysis in R.

The AMECO database was last updated: 5 May 2015.

Install it from github with:

``` r
devtools::install_github("expersso/ameco")
```

``` r
library(ameco)
head(ameco)
```

``` r
'data.frame':   1842297 obs. of  8 variables:
 $ code       : chr  "EU28.1.0.0.0.NPTD" "EU15.1.0.0.0.NPTD" "EA19.1.0.0.0.NPTD" ...
 $ country    : chr  "European Union" "European Union (15 countries)" "Euro area" ...
 $ sub.chapter: chr  "01 Population" "01 Population" "01 Population" "01 Population" ...
 $ title      : chr  "Total population (National accounts)" ...
 $ unit       : chr  "1000 persons" "1000 persons" "1000 persons" "1000 persons" ...
 $ cntry      : chr  "EU28" "EU15" "EA19" "EA12" ...
 $ year       : num  1960 1960 1960 1960 1960 1960 1960 1960 1960 1960 ...
 $ value      : num  409087 316746 265004 252331 299392 ...
```

This package is not affiliated with, nor endorsed by, the European Commission. I aim to update it whenever the AMECO database is updated. If you ever see that it is out-of-date, don't hesitate to send a pull request and/or remind me to update it.
