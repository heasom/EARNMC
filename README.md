Empirically Adjusted Reproductive Number - Manuscript Companion (EARNMC)
=========================================================================

This is an R package and collection of scripts to document and reproduce the methods 
employed in the paper: "An Empirically Adjusted Approach to Reproductive Number Estimation for Stochastic Compartmental Models:\\ A Case Study of Two Ebola Outbreaks" by [Grant Brown](http://grantbrown.github.io), [Jacob Oleson](http://www.public-health.uiowa.edu/people/jacob-oleson/), and [Aaron Porter](http://inside.mines.edu/~aporter/).

Included in the EARNMC package are:

* Incidence data for the 1995 Ebola Outbreak in Kikwit, DRC, as analyzed by [Lekone and Finkenstadt (2006)](http://onlinelibrary.wiley.com/doi/10.1111/j.1541-0420.2006.00609.x/abstract#.VK6fzhuaiSY).
* Incidence data for the 2014-2015 Ebola Epidemic in West Africa, organized by volunteers and collected [here](https://github.com/cmrivers/ebola).
* Analysis functions which employ our open source [libSpatialSEIR](https://github.com/grantbrown/libspatialSEIR) epidemic modeling software to analyze both epidemics. 
* Scripts to generate the graphics and tables present in the manuscript. 
* Raw and processed MCMC output from our own analyses. 

Also included in this repository is a manuscript pre-print, which has been submitted for consideration in [Biometrics](http://onlinelibrary.wiley.com/journal/10.1111/%28ISSN%291541-0420). 


Installation
-------------
To replicate our analyses, you will need first to install [libSpatialSEIR](https://github.com/grantbrown/libspatialSEIR). The latest instructions are available [here](https://github.com/grantbrown/libspatialSEIR/wiki/Installation). We also depend on [ggplot2](https://github.com/hadley/ggplot2) for some of the figures. Once you have the prerequisites prepared, the R package can be installed from a command prompt running in the repository root:

    R CMD INSTALL EARNMC

Use
-------------
To generate the figures and tables featured in the manuscript, simply run the "GenerateManuscriptFigures.R" file in the scripts folder. To replicate the analyses, please see the files in /scripts/analyses

