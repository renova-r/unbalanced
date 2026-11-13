# unbalanced

Methods for unbalanced classification: resampling (SMOTE, undersampling, CNN, ENN, NCL, OSS, Tomek) and racing to select among them.

Compatibility updates by Renova.

Version 2.0.9001 renames the package-level constant `.Random.seed` to `.unbalancedRandomSeed`, declares the `stats` imports in `NAMESPACE` and `DESCRIPTION`, replaces an invalid `\keyword` in the package help page with `\concept` entries, and updates `DESCRIPTION` metadata (an `Authors@R` entry equivalent to the existing authors and maintainer, and removal of the stale optional `Date` field).

## Install

```r
install.packages("unbalanced", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

Or install this exact release from its tag:

```r
install.packages("remotes")
remotes::install_github("renova-r/unbalanced@renova-2.0.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

unbalanced is by Andrea Dal Pozzolo (maintainer), Olivier Caelen and Gianluca Bontempi; the original project is at <http://mlg.ulb.ac.be>. License: GPL (>= 3); see [COPYING](COPYING).
