# RiTMIC
The __RiTMIC__ R Package performs virtual increasing from your RNAseq data simulation on RNAseq,a personalized differential analysis of omics data with `penda` analysis and provides tools for visualization.

## Installation
To get the current development version from github:
```
git clone https://github.com/bcm-uga/RiTMIC.git
cd RiTMIC 
R
```

## Build vignette 
```
setwd("vignettes")
rmarkdown::render("simulation.Rmd")
```