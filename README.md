# Programming Workshops
## by Derek Sollberger

In this repository, I plan on maintaining my programming workshops.  Most of the workshops are in the R programming language (for Python links, please scroll down)

# R

## Installation Instructions

1. Install `R` and `RStudio` (two separate programs).  Instructions: [link](https://libguides.ucmerced.edu/software-carpentry/r/install)
2. Install additional packages (to ease programming) by copy-and-pasting the following code into the console of RStudio (i.e. open RStudio and then find the console in the lower-left pane) one line at a time, and press `enter` after each line to run the code.

```
package_list <- c("corrplot", "forcats", "janitor", "skimr", "tidyverse")
install.packages(package_list)
```
