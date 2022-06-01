# Programming Workshops
## by Derek Sollberger

In this repository, I plan on maintaining my programming workshops.  Most of the workshops are in the R programming language (for Python links, please scroll down)

# R

## Installation Instructions

1. Install `R` and `RStudio` (two separate programs).  Instructions: [link](https://libguides.ucmerced.edu/software-carpentry/r/install)
2. Install additional packages (to ease programming) by copy-and-pasting the following code into the console of RStudio (i.e. open RStudio and then find the console in the lower-left pane) one line at a time, and press `enter` after each line to run the code.

```
package_list <- c("corrplot", "forcats", "ggsignif", "infer", "janitor", "skimr", "tidyverse")
install.packages(package_list)
```

We will be practicing our coding skills on data from [TidyTuesday](https://github.com/rfordatascience/tidytuesday).  *To avoid 'file does not exist' errors later*:

* make a folder on your desktop and call it something like "programming workshops"
* download and place the following script and data files into that folder (i.e. right-click and 'Save Link As"):
    * [Introduction_to_Data_Analysis_in_R-template.rmd](R/Introduction_to_Data_Analysis_in_R-template.rmd?raw=1)
    * [Introduction_to_Data_Analysis_in_R-template.rmd](R/Introduction_to_Data_Analysis_in_R-template.rmd?raw=1)
    * [reputation.csv](R/reputation.csv?raw=1)
    * [reputation_wide.csv](R/reputation_wide.csv?raw=1)

Videos (will be uploaded after sessions take place):
* Day 1: [Introduction to Data Analysis in R](https://www.youtube.com/watch?v=J9sKSCvPx8c)
* Day 2: Intermediate Data Analysis in R

# Python

## Installation Instructions

1. I advise new learners to install the Anadonca distribution ([link to instructions](https://libguides.ucmerced.edu/software-carpentry/python/install)) to ease their Python learning experience.
2. To start the program, search for "Anaconda" in your Windows search or Mac Finder, and start a Jupyter Lab session.
