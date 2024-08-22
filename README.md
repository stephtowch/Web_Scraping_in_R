# Web Scraping in R <img src="https://media.giphy.com/media/1oGT95WukVFcRO1OFZ/giphy.gif" width="50">

[![](https://img.shields.io/badge/Language-R-blue)](http://cran.r-project.org/)

<sub>*Last updated 2024-03-21.*</sub>

This GitHub repository contains R code for web scraping course information on the Essex Summer School Website, as part of my exam for the Web Scaping and Data Management module on the MA Social Science Data Analytics course.

**Web Scraping and Data Management using [`rvest`](https://cran.r-project.org/web/packages/rvest/index.html)**. 
## :telescope: Overview

The repository is organised into the following sections:

- **[1.0 User Guide](/1.0_User_Guide))**: This is a procedure guide for using the `rvest` package for web scraping, as well as `tidyverse`, `stringr` and `purrr` for some data wrangling.
- **[2.0 Instruction Sheet](/2.0_Instruction_Sheet)**: This is the instruction sheet for the exam that details what to web scrap and report.
- **[3.0 Data File](3.0_Data_File)**: This is the.csv output file to review course information at the Essex Summer School including the course names, URLs and descriptions.

## :scroll: Notes

This repository assumes basic competence in R (setting working directory, loading packages, etc) and contains only materials relating to *Web Scraping and Data Management in R*. So the focus will be generally on the application and not on the theory.  

## :hammer_and_wrench: Setup

To run the code, you will need:

1. A fresh installation of [**`R`**](https://cran.r-project.org/) (preferably version 4.4.1 or above).
4. [RStudio IDE](https://www.rstudio.com/products/rstudio/download/) (optional but recommended).
5. Install the required packages by running:

   ```R
   # Load the package
   install.packages(c("rvest", "tidyverse", "stringr", "pacman", "purrr")).
   ```

<details>
<summary>
<i>Package Versions</i>
</summary>
   
Run on Windows 11 x64 (build 22621), with R version 4.3.2.

The packages used here:

- `revtools` 	1.0.4(*CRAN*)
- `tidyverse` 2.0.0(*CRAN*)
- `stringr`   1.5.1(*CRAN*)
- `purrr`     1.0.2(*CRAN*)
  
</details>

Feel free to adjust this based on your preferences and specific details about your code and setup.
