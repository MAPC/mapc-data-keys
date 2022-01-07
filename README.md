# ``` {mapcdatakeys} ```

This data package obains standardized data keys for different geographic levels in Massachusetts.

Currently, data keys for the 351 towns and cities in Massachusetts are available in a few different combinations depending on the type of data keys.

Efforts are on way to develop a ful-fledged preiodically updated data package with all relevant geographic levels as well as keys.

## Installation

You can install the released version of mortgager with:

``` r
devtools::install_github("MAPC/mapcdatakeys")
```

## mortgager

Load the  package with this line:

``` r
library(mapcdatakeys)
```

## Available Data Keys:

### The Entire Set

```mapcdatakeys::muni_data_keys()```

### Census FIPS Codes

```mapcdatakeys::census_muni_keys()```

### MAPC Sub Regions and Coalition Affiliations

```mapcdatakeys::mapc_data_keys()```

### MAPC Community Types

```mapcdatakeys::community_type()```

### RPA Affiliations

```mapcdatakeys::rpa_data_keys()```

### MBTA and RTA Affiliations

```mapcdatakeys::mbta_data_keys()```
