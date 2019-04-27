
<!-- README.md is generated from README.Rmd. Please edit that file -->

## Overview

**dbdataset** is a data package the contains 74 different dataset parsed
from [DrugBank](https://www.drugbank.ca) XML database using
[dbparser](https://dainanahan.github.io/dbparser/) r package.

These datasets can be used easily as R dataframes to ease the drugs
development research process that might use **DrugBank** database.

However; it also can be used to in Machine Learning in many sub-fields
such as:

  - Natural Language Processing (NLP)
  - Web Scrapping
  - Visualization

### Installation

As the package size exceedes CRAN limit it will be hosted on Github only
right now. Hence it could be installed via the following command

``` r
devtools::install_github("Dainanahan/dbdataset")
```

Then the datasets will be available after the following running the
following command

``` r
library(dbdataset)
```
