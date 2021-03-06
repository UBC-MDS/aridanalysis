# aRidanalysis 

DRY out your regression analysis!

## R Package for Inferential Regression and EDA Analysis!

As Data Scientists, being able to perform Exploratory Data Analysis as well as Regression Analysis are paramount to the process of analyzing trends in data. Moreover, following the DRY (Do Not Repeat Yourself) principle is regarded as a majority priority for maximizing code quality. Yet, often times Data Scientists facing these tasks will start the entire process from scratch, wasting both time and effort while compromising code quality. The aridanalysis package strives to remedy this problem by giving users an easy-to-implement EDA function alongside 3 robust statistical tests that will simplify these analytical processes and produce an easy to read interpretation of the input data. Users will no longer have to write many lines of code to explore their data effectively. 

## Package Functions

### `arid_eda`

This function takes in the data frame of interest and generates summary statistics as well as basic exploratory data analysis plots to helps users understand the overall behaviour of the explanatory and response variables.

### `arid_linreg`

This function takes in the data frame of interest and performs a regular linear regression with the given regularization and features. The function then outputs a regression model for prediction and an equivalent model to provide inference.

### `arid_logreg`

This function takes in a data frame and performs either binomial or multinomial classification based on user inputs. The function then outputs a logistic regression model for prediction and an equivalent model to provide inference.

### `arid_countreg`

This function takes a dataframe, its categorical and continuous variables and other user inputs to perform a Poisson regression. The function will return a Poisson regressor model for prediction and an equivalent model for inference purposes.

## R Ecosystem Role

This package will build off the EDA and statistical analysis provided by `ggplot2` included in the [Tidiverse](https://ggplot2.tidyverse.org/#:~:text=Learning%20ggplot2&text=The%20Data%20Visualisation%20and%20Graphics,ggplot2%20as%20quickly%20as%20possible.) package as well as [base R](https://stat.ethz.ch/R-manual/R-devel/library/base/html/00Index.html) package to streamline data visualization and model analysis functionality. There are some existing packages that help you with this, however the `aridanalysis` package aims to ease the job to provide different regression analysis interpretations. 

### Related Packages

- [SmartEDA](https://cran.r-project.org/web/packages/SmartEDA/vignettes/SmartEDA.html): SmartEDA includes multiple custom functions to perform initial exploratory analysis on any input data describing the structure and the relationships present in the data. The generated output can be obtained in both summary and graphical form.
- [MLR](https://cran.r-project.org/web/packages/mlr/index.html): This package contains a large number of classification and regression techniques, including machine-readable parameter descriptions.
- [caret](http://topepo.github.io/caret/index.html): The caret package (short for Classification And REgression Training) is a set of functions that attempt to streamline the process for creating predictive models.

## Installation

- TODO

## Features

- TODO

## Dependencies

- TODO

## Usage

- TODO

## Documentation

The official documentation is hosted on Read the Docs: 

## Contributors

Group 8 Members:  
Craig McLaughlin              : @cmmclaug  
Daniel Ortiz Nunez            : @danielon-5  
Neel Phaterpekar              : @nphaterp  
Santiago Rugeles Schoonewolff : @ansarusc  

### Credits

- TODO
