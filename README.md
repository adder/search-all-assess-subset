# search-all-assess-subset
An implementation of the Search All, Asses Subset strategy for FDR estimation in shotgun proteomics.

A user-friendly GUI version of saas is hosted [here](http://iomics.ugent.be/saas/).

## Installation

 You first need to install the [devtools](https://cran.r-project.org/package=devtools) package.

```r
install.packages("devtools")
```

Then install saas using the `install_github` function in the
[devtools](https://cran.r-project.org/package=devtools) package.
```r
library(devtools)
install_github("compomics/search-all-assess-subset")
```

## Running the saas GUI

When saas is installed, you can easily launch the GUI from R.
By default, you can see the GUI by visiting [http://127.0.0.1:3320](http://127.0.0.1:3320)
```r
library(saas)
saas_gui()
```
Or if you want to run saas immediately from the terminal.
```r
 R -e "library(saas);saas_gui()"
```
