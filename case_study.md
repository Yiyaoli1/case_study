case study
================
Yiyao LI

``` r
library(tidyverse)
```

    ## -- Attaching packages ------------------------------- tidyverse 1.3.0 --

    ## √ ggplot2 3.3.2     √ purrr   0.3.4
    ## √ tibble  3.0.3     √ dplyr   1.0.2
    ## √ tidyr   1.1.2     √ stringr 1.4.0
    ## √ readr   1.3.1     √ forcats 0.5.0

    ## -- Conflicts ---------------------------------- tidyverse_conflicts() --
    ## x dplyr::filter() masks stats::filter()
    ## x dplyr::lag()    masks stats::lag()

``` r
library(p8105.datasets)
data(nyc_airbnb)
```

## Brainstorm some questions

1.  What’s the best Airbnb in staten island for\< $100
2.  What price range is popular in each borough? most rented?
3.  What apartment features are related to price?
4.  cheapest room type in each neighborhood?
5.  hosts have higher ratings?
