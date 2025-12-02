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

# Install packages
install.packages('BFHcharts')
install.packages('BFHtheme')
install.packages('BFHllm')
```

## Packages

- **[BFHcharts](https://github.com/johanreventlow/BFHcharts)** - SPC visualization for healthcare quality improvement
- **[BFHtheme](https://github.com/johanreventlow/BFHtheme)** - Hospital branding theme for ggplot2
- **[BFHllm](https://github.com/johanreventlow/BFHllm)** - LLM integration framework for AI-driven insights

## Dashboard

View package status and documentation at: https://johanreventlow.r-universe.dev

## About

This universe automatically builds and distributes R packages from GitHub. Packages are built on multiple platforms (Windows, macOS, Linux) and updated automatically when changes are pushed.

---

**Registry maintained by:** Johan Reventlow
**Powered by:** [R-universe](https://r-universe.dev)
