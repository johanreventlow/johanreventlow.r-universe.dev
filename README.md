# Johan Reventlow's R-universe

This repository is the registry for my R-universe, which provides CRAN-like package installation for my R packages.

## Installation

Install packages from this universe using:

```r
# Enable this universe
options(repos = c(
  johanreventlow = 'https://johanreventlow.r-universe.dev',
  CRAN = 'https://cloud.r-project.org'
))

# Install BFHcharts
install.packages('BFHcharts')

# Install BFHtheme
install.packages('BFHtheme')
```

## Packages

- **[BFHcharts](https://github.com/johanreventlow/BFHcharts)** - SPC visualization for healthcare quality improvement
- **[BFHtheme](https://github.com/johanreventlow/BFHtheme)** - Hospital branding theme for ggplot2

## Dashboard

View package status and documentation at: https://johanreventlow.r-universe.dev

## About

This universe automatically builds and distributes R packages from GitHub releases. Packages are built on multiple platforms (Windows, macOS, Linux) and updated automatically when new releases are tagged.

---

**Registry maintained by:** Johan Reventlow
**Powered by:** [R-universe](https://r-universe.dev)
