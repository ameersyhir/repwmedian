#repwmedian
**repwmedian** is an R package for handling missing data. It includes functions to detect missing values and replace missing values with median.

## Installation

To install from Github, use the 'dectools' package:

```r
# Install devtools if you haven't already
install.package("devtools")

# Install repwmedian for Github
devtools::install_github("ameersyhir/repwmedian")

# Detects missing values in each column
detectna()

# Replaces missing values in numeric columns with the median
repwmedian()
