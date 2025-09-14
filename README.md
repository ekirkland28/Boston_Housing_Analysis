# Linear Regression Analysis of Boston Housing Data Set

## Project Overview

This project sought to develop the best model for predicting the median house value in a particular area of Boston.

## Dataset

- **Source**: [Kaggle](https://www.kaggle.com/datasets/schirmerchad/bostonhoustingmlnd)
- **Description**: This data was derived from information collected by the U.S. Census Service in 1970 concerning
housing in the Boston, Massachusetts area was used. The information was originally for census tracts in the Boston Standard Metropolitan Statistical Area (SMSA).
- **Size**: 506 rows, 13 columns

## Tools & Packages

- R (version [24.12.0])
- RStudio
- `tidyverse`
- `ggplot2`
- `broom`
- `psych`
- `nortest`
- `car`
- `caret`
- `ncvreg`
- `mgcv`
- `gam`
- `splines`
- `gam`
- `glmnet`
- `dplyr`
- `patchwork`

## Summary of Analysis

In this project, I:
- Explored the dataset and visualized key relationships
- Identified proportion of population that is lower status as a strong predictor of median house value
- Built a linear regression model
- Performed regression diagnostics to address outliers, non-normality, and non-linearity
- Implemented remedies such as non-linear terms
- Performed model and variable selection using Elastic Net regularization and SCAD
- Evaluated model performance using prediction performance metrics such as MSE and prediction plots

_Key Findings:_
- Proportion of low status people and average number of rooms are important predictors in median house value
- The following predictors are also useful in the prediction of median house value:
  * Pupil-teacher ratio
  * Property tax rate
  * Accessibility to radial highways
  * Distance to employment centers
  * Nitrogen oxide concentrations
  * land zoned for large lots
  * Crime rate
- This model could be used to estimate how policy changes would affect Boston's housing market
  * For example, proposed property tax rate could be fed to model to determine its affect on house value

## How to Run the Project

To reproduce the analysis:

1. Clone the repo:
   ```bash
   git clone https://github.com/[your-username]/Linear_Regression_Analysis.git
2. Open `Linear_Regression_Analysis.Rproj` in RStudio
3. Run the scripts in order (or use source()):
   * scripts/load_data.R
   * scripts/eda.R
   * scripts/modeling.R
4. Make sure required packages are installed using:
   ```install.packages(c("tidyverse", "ggplot2", "broom", "psych", "nortest", "car", "caret", "ncvreg", "mgcv", "gam", "splines", "glmnet", "dplyr", "patchwork"))```

## Contact

Created by Eleanor Kirkland. Feel free to reach out via [LinkedIn](https://www.linkedin.com/in/eleanor-kirkland-42b859332/).
