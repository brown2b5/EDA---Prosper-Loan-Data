# Exploratory Data Analysis - Prosper Loan Data
Prosper is a peer-to-peer lending marketplace in the United States which provides a platform for borrowers and lenders (1).  Borrowers can apply for a fixed-rate, fixed-term loan of between $2,000 and $35,000 and individuals/institutions can invest in loans which generate attractive returns (1).  Data is available on Prosper loans (2).  This data includes interest rates, borrower employment status, borrower income, loan amount, borrower credit history and many other variables (3).  The purpose of this project is to explore the data to determine which conditions might be associated with whether a borrower will be successful in paying back the original loan amount and interest.  I expect to see which borrower employment status, credit score, debt to income ratio and other loan variables are most associated with those who default on their loans and who successfully complete their loan payments.

# Programming Environment
This project is completed using [R](https://www.r-project.org/) in [RStudio](https://www.rstudio.com/).  Users wanting to contribute will need to download both software ([R](https://cran.r-project.org/) version 3.4.4 and [RStudio](https://www.rstudio.com/products/rstudio/download/)).  The primary files will be an R markdown file (RMD) and the dataset (prosperLoanData.csv).  Three of the packages I will be using heavily in this project are the ggplot2 package for generating plots, the knitr package for converting the R markdown file to an HTML file and the dplyr package for summarizing data and modifying dataframes.  Before contributing to this project, users will need to install these packages in R using the following commands at the command line:   
```
install.packages("ggplot2", dependencies = T)
install.packages("knitr", dependencies = T)
install.packages("dplyr", dependencies = T)
```
Finally, users will need to load the libraries with the following commands:

```
library(ggplot2)
library(knitr)
library(dplyr)
```
I refer users to the documentation on [R](https://cran.r-project.org/manuals.html), [ggplot2](http://ggplot2.tidyverse.org/reference/), [dplyr](https://dplyr.tidyverse.org/) and [knitr](https://yihui.name/knitr/demo/manual/) for help understanding and using any of the commands I have in the R markdown file to generate plots, transform/summarize the data and put the R markdown document into HTML format.

# How to make contributions
I am certainly open to contributions from others as this project moves forward.  To contribute, first clone the repository onto your local machine by running the following command in git:
```
git clone https://github.com/brown2b5/EDA---Prosper-Loan-Data
```
After making changes to the project, submit a pull request and we will discuss the possibility of merging the changes to the master branch.

# License and copyright

### R
Copyright (C) 1989, 1991 Free Software Foundation, Inc.
                       59 Temple Place, Suite 330, Boston, MA  02111-1307  USA

Licensed under the Free Software Foundation's [GNU General Public License](https://github.com/brown2b5/EDA---Prosper-Loan-Data/blob/master/R%20License.txt).

### RStudio
© Copyright 2018 RStudio

Licensed under the [RStudio End User License](https://github.com/brown2b5/EDA---Prosper-Loan-Data/blob/master/RStudio%20License.pdf).

### ggplot2
© Copyright 2018 Hadley Wickham; RStudio

Licensed under the Free Software Foundation's [GNU General Public License](https://github.com/brown2b5/EDA---Prosper-Loan-Data/blob/master/ggplot2%20License.txt).

### knitr

© Yihui Xie 2005 - 2018

Licensed under [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License](https://github.com/brown2b5/EDA---Prosper-Loan-Data/blob/master/knitr%20License.txt).

### dplyr

Copyright © 2013-2015 RStudio and others

Licensed under [The MIT License](https://github.com/brown2b5/EDA---Prosper-Loan-Data/blob/84b067728d43b0f6aacc9f12aa1d598cee047f87/dplyr%20License.txt).

#                       **References**
Reference 1: https://www.prosper.com/home/about

Reference 2: https://www.kaggle.com/jschnessl/prosperloans/feed

Reference 3: https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0
