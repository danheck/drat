# Repository for R packages

Currently, source and binary versions of the following packages are provided:

* metaBMA
* multinomineq
* rPorta

### Example: Installing `metaBMA`

```{r}
# install dependencies:
install.packages(c("rstan", "rstantools", "bridgesampling","LaplacesDemon", 
                   "logspline", "mvtnorm", "coda", "knitr", "methods"))

# install newest version from Github repository:
install.packages("drat")
drat::addRepo("danheck")
install.packages("metaBMA", repos = "https://danheck.github.com/drat/")
``` 