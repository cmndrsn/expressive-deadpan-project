# Expressive/Deadpan Project

## Overview

This paper contains the data, code, and figures from Anderson, Ling, & Schutz (under review). We performed analyses using *R* (version 4.2.3) on the Windows 10 operating system (version 22H2). To use this code, you must first install *R* and *RStudio*. [Here](https://rstudio-education.github.io/hopr/starting.html) is a guide showing how to do this. 

## File organization

Analysis code is organized in .qmd and .r files within the repository. 

- Data are contained in the `/Data` folder.  
- *R* dependencies and custom functions are viewable in the `/R` folder. It contains the following files:
  - `Libraries.R`. Module containing all dependencies required for the analysis code to run.
  - `Functions.R` Module containing custom functions written for this project.
  - `Preprocessing.R` Script including additional code for figure and data formatting.
- Figures from the analyses are viewable in the `/Figures` folder.
- `Analysis/Analysis.qmd` contains the analyses from the manuscript. 

# Getting started

- To get started, open `/R/Libraries.R` and ensure all libraries are installed. 
  - The *R* command to install a package is `install.packages()`. For example, to install the dplyr package, run the following line of code:
 `install.packages('dplyr')`

- Once all dependencies are installed, open `Expressive-Deadpan.Rproj` in RStudio. From the file navigator, open `Analysis/Analysis.qmd` from within the RStudio  to reproduce analyses.
