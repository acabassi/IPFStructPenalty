# IPFStructPenalty

`IPFStructPenalty` fits Lasso, elastic and tree-lasso methods with penalty factors for different data sources, and uses the Efficient Parameter Selection via Global Optimization (EPSGO) algorithm to optimize multiple penalty parameters.

## R package instruction

You can download and install this package locally, or install it from github directly with:

```{r setup, include=FALSE}
devtools::install_github("zhizuio/IPFStructPenalty/IPFStructPenalty")
```
See the file `Test.R` for s simple start with simulated data. The scripts `Sim_reg.R` and `GDSC_reg.R` are for simulation studies and analyzing real data, respectively.
