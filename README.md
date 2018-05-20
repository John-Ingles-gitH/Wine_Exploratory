# Wine_Exploratory

In this Udacity course project, I use a data set of red wine samples provided
by Cortez et al. to explore the trends in quality based on properties such as
volatile acidity, chlorides, alcohol percent, etc.

## Getting Started

These instructions will get you a copy of the RMD file for the project on your
machine along with an Excel file of the data set for the RMD file to use.

### Prerequisites

* RStudio Packages
  * ggplot2
  * MASS

### Installation
 
Clone the repository or download the ZIP file at https://github.com/John-Ingles-gitH/Wine_Exploratory

```
$ git clone https://github.com/John-Ingles-gitH/Wine_Exploratory.git
$ cd Wine_Exploratory
```

## Description

This analysis is written in R Markdown and requires RStudio to modify.

However, if just wish to view the final Knit, you can navigate to its [GitHub Page](https://john-ingles-gith.github.io/Wine_Exploratory/).

### Data set

The data set contains 1,559 red wine samples with 11 variables on the chemical
properties of each.  The variables are:


* fixed acidity (tartaric acid - g / dm^3)
* volatile acidity (acetic acid - g / dm^3)
* citric acid (g / dm^3)
* residual sugar (g / dm^3)
* chlorides (sodium chloride - g / dm^3
* free sulfur dioxide (mg / dm^3)
* total sulfur dioxide (mg / dm^3)
* density (g / cm^3)
* pH
* sulphates (potassium sulphate - g / dm3)
* alcohol (% by volume)

The 12th data point is the quality measurement of the sample recorded as a rating
between 0 (very bad) and 10 (very excellent).

### Analyis Strategy

The data is explored using univariate plots like histograms and bar charts, 
bivariate plots like scatter plots and box plots, and multivariate plots.

In the end, an ordinal logistic regression is performed using the variables
determined by the plots to have the most influence on quality.

## License

GNU General Public License v3.0