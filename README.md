# dhsage R Package

## Overview
The dhsage R package is designed to analyze age heaping in demographic and health surveys. It provides functions to calculate the Whipple index, a measure of age heaping, for a given dataset. The package includes data from 70 waves of demographic and health surveys across 19 Asian countries.

## Usage
To use this package, follow these steps:

##**Installation**: Install the package from CRAN using the following command in R:
   
   install.packages("dhsage")

##**Loading the Package:** Load the package into your R session:

library(dhsage)

**##Loading Data:** Load the age data for a specific country and year. For example, to load the age data for Afghanistan in 2010, use the following command:

x <- afgan_2010

**##Calculating Whipple Index:** Calculate the Whipple index to evaluate age heaping within a specified age range. For example, to calculate the Whipple index for ages 23 to 62:

heaping(x, 23, 62)

**##Interpreting Results:** The output will provide the Whipple index value and the quality of age data according to United Nations standards.

**##Additional Information**
For more detailed documentation and examples, refer to the package manual.

**##License**
This project is licensed under the GNU General Public License v2.0 or later. 
