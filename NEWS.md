# unbalanced 2.0.9001

Renova release, based on CRAN unbalanced 2.0 (archived on CRAN 2022-05-23).

- `R/unbalanced-internal.R`: the stored package object `.Random.seed` (a constant seed vector) was renamed `.unbalancedRandomSeed`, so it no longer shadows R's own random seed name.
- `NAMESPACE` and `DESCRIPTION` (`Imports`): added `importFrom("stats", ...)` for `p.adjust`, `pchisq`, `predict`, `qt`, `quantile`, `runif`, `sd`, `t.test` and `wilcox.test`, and `stats` to `Imports`.
- `man/unbalanced-package.Rd`: the invalid `\keyword{unbalanced datasets, imbalanced learning}` became `\concept{unbalanced datasets}` and `\concept{imbalanced learning}`.
- `DESCRIPTION`: the free-text `Author` was replaced by an equivalent `Authors@R` entry (Andrea Dal Pozzolo author and maintainer, Olivier Caelen and Gianluca Bontempi authors) and the stale optional `Date: 2015-06-25` field was removed (metadata only).
- `DESCRIPTION`: `Version` set to `2.0.9001`; "Compatibility updates by Renova." appended to `Description`.
- The stale `MD5` file was removed.
- `COPYING` (GNU GPL text) was added; the `License` field is unchanged.
- `README.md` was added and `.Rbuildignore` keeps `README.md` and `NEWS.md` out of the built package.
