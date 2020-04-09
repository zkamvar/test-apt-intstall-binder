# Test repository for making resources available to Carpentries Learners

To openthis repository with either RStudio or Jupyter Lab, click on one of these
buttons:

Jupyter Lab: [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/zkamvar/test-apt-intstall-binder/master?urlpath=lab)    
RStudio: [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/zkamvar/test-apt-intstall-binder/master?urlpath=rstudio)

# About

This repository can be built into a Binder repo by clicking on one of the 
buttons above. The software installed is listed in the following files

 - apt.txt: apt packages to be installed (currently nano)
 - environment.yml: python packages to be installed via anaconda (currently
   matplotlib, numpy, and pandas).
 - install.R: R script to install required packages (currently "here")

Please modify these packages for your workshop (especially R packages) because
some of these require extra apt repositories and may take a long time to compile.

Additionally, you will want to change the URL for the buttons so that the 
learners have the correct lesson to work with. 


