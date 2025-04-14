# Imputing-Missing-Reaction-Times-Using-the-EM-Algorithm-Under-a-Bivariate-Normal-Model


This repository contains an R Markdown analysis where missing reaction time data for two stimuli (**Stimulus A** and **Stimulus B**) is imputed using the Expectation-Maximization (EM) algorithm under the assumption of a bivariate normal distribution.

## 📁 Project Overview

- 📄 **Title**: Imputing Missing Reaction Times Using the EM Algorithm  
- 🧪 **Method**: Expectation-Maximization (EM) Algorithm  
- 📊 **Data**: Reaction time dataset from [Duke University](https://www2.stat.duke.edu/~pdh10/FCBS/Exercises/interexp.dat)

## 🛠️ Features

- Custom EM algorithm implementation in R
- Imputes values based on conditional expectations under multivariate normality
- Tracks convergence through log-likelihood evaluation
- Compares mean and variance before and after imputation
- Preserves correlation structure between variables
- Comprehensive visualizations including:
  - Histograms
  - Boxplots
  - Scatter plots (before and after imputation)

## 📦 Dependencies

Make sure the following R libraries are installed:

```r
library(ggplot2)
library(gridExtra)
library(dplyr)
 How to Use
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/em-imputation-reaction-times.git
Open the .Rmd file in RStudio.


