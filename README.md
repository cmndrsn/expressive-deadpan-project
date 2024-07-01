# Expressive/Deadpan Project

## Overview

This paper contains the data, code, and figures in Anderson, Ling, & Schutz (under review). We performed analyses using *R* version 4.2.3 (2023-03-15) on Windows 10 operating system (version 22H2).

## File organization

Analysis code is in .qmd and .r files within the repository. 

- Data are contained in `/Data`.  
- *R* dependencies and custom functions are viewable in `/R`.
  - `Libraries.R` contains all dependencies required for the analysis code to run.
  - `Functions.R` contains custom functions written for this project.
  - `Preprocessing.R` includes additional code for figure formatting, as well as additional data processing to reduce the bloat in the analysis qmd file.
- Figures from the analyses are viewable in `/Figures`.
- `Analysis/Analysis.qmd` contains the analyses from the manuscript. 

# Getting started

- To get started, open `/R/Libraries.R` and ensure all libraries are installed. The *R* package to install a library is `install.packages()`.
- Once all dependencies are installed, open `Expressive-Deadpan.Rproj` from the repository, and then `Analysis/Analysis.qmd` to reproduce analyses.
