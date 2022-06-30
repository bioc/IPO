# IPO

[![How long since the package was first in a released Bioconductor version (or is it in devel only).](https://bioconductor.org/shields/years-in-bioc/IPO.svg)](https://bioconductor.org/packages/IPO/)
[![Percentile (top 5/20/50% or 'available') of downloads over last 6 full months. Comparison is done across all package categories (software, annotation, experiment).](http://bioconductor.org/shields/downloads/IPO.svg)](https://bioconductor.org/packages/stats/bioc/IPO/)
[![Project Status: Unsupported – The project has reached a stable, usable state but the author(s) have ceased all work on it. A new maintainer may be desired.](http://www.repostatus.org/badges/latest/unsupported.svg)](http://www.repostatus.org/#unsupported)

Latest release: 
[![Build Status Biocondcutor Release](http://bioconductor.org/shields/build/release/bioc/IPO.svg)](http://bioconductor.org/packages/release/bioc/html/IPO.html)
Devel: 
[![Build Status Biocondcutor Devel](http://bioconductor.org/shields/build/devel/bioc/IPO.svg)](http://bioconductor.org/packages/devel/bioc/html/IPO.html)
[![codecov](https://codecov.io/gh/Bioconductor-mirror/IPO/branch/master/graph/badge.svg)](https://codecov.io/gh/Bioconductor-mirror/IPO/)
@master: 
[![Build Status Travis-CI](https://travis-ci.org/rietho/IPO.svg?branch=master)](https://travis-ci.org/rietho/IPO)


IPO (‘Isotopologue Parameter Optimization’) is a tool for automated Optimization of [XCMS](http://bioconductor.org/packages/xcms/) Parameters. It is a fast and free of labeling steps, and applicable to data from different kinds of samples and data from different methods of liquid chromatography - high resolution mass spectrometry and data from different instruments.

Find out more about the usage in the [package vignette](https://bioconductor.org/packages/devel/bioc/vignettes/IPO/inst/doc/IPO.html) (Biocondcutor development version). The publication is available from http://www.biomedcentral.com/1471-2105/16/118.

## Installation

Get the latest release version from [Bioconductor](http://bioconductor.org/packages/IPO/):
```{r}
## try http:// if https:// URLs are not supported
if (!requireNamespace("BiocManager", quietly=TRUE))
    install.packages("BiocManager")
BiocManager::install("IPO")
````

Or the development version from [Github](https://github.com/rietho/IPO/):

```R
# install.packages("devtools")
devtools::install_github("rietho/IPO") 
```
