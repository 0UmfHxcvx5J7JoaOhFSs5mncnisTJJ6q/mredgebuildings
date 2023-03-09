# Prepare data to be used by the EDGE-Buildings model

R package **mredgebuildings**, version **0.1.5**

[![CRAN status](https://www.r-pkg.org/badges/version/mredgebuildings)](https://cran.r-project.org/package=mredgebuildings)  [![R build status](https://github.com/pik-piam/mredgebuildings/workflows/check/badge.svg)](https://github.com/pik-piam/mredgebuildings/actions) [![codecov](https://codecov.io/gh/pik-piam/mredgebuildings/branch/master/graph/badge.svg)](https://app.codecov.io/gh/pik-piam/mredgebuildings) [![r-universe](https://pik-piam.r-universe.dev/badges/mredgebuildings)](https://pik-piam.r-universe.dev/builds)

## Purpose and Functionality

Prepare data to be used by the EDGE-Buildings model.


## Installation

For installation of the most recent package version an additional repository has to be added in R:

```r
options(repos = c(CRAN = "@CRAN@", pik = "https://rse.pik-potsdam.de/r/packages"))
```
The additional repository can be made available permanently by adding the line above to a file called `.Rprofile` stored in the home folder of your system (`Sys.glob("~")` in R returns the home directory).

After that the most recent version of the package can be installed using `install.packages`:

```r 
install.packages("mredgebuildings")
```

Package updates can be installed using `update.packages` (make sure that the additional repository has been added before running that command):

```r 
update.packages()
```

## Questions / Problems

In case of questions / problems please contact Robin Hasse <robin.hasse@pik-potsdam.de>.

## Citation

To cite package **mredgebuildings** in publications use:

Hasse R, Führlich P, Levesque A (2023). _mredgebuildings: Prepare data to be used by the EDGE-Buildings model_. R package version 0.1.5, <URL: https://github.com/pik-piam/mredgebuildings>.

A BibTeX entry for LaTeX users is

 ```latex
@Manual{,
  title = {mredgebuildings: Prepare data to be used by the EDGE-Buildings model},
  author = {Robin Hasse and Pascal Führlich and Antoine Levesque},
  year = {2023},
  note = {R package version 0.1.5},
  url = {https://github.com/pik-piam/mredgebuildings},
}
```
