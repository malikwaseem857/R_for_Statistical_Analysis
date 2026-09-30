# R for Statistical Analysis
This repository contains a collection of R scripts designed to introduce fundamental concepts of R programming for statistical analysis. The scripts cover data handling, descriptive statistics, hypothesis testing, and data visualization.

## Scripts Overview

This repository is structured as a series of lessons, with each script building upon the previous one.

*   **`day_01.R`**: Introduces the basics of R and RStudio, including syntax rules and file naming conventions.
*   **`day_02.R`**: Covers basic arithmetic, managing packages, importing data from a CSV file using `readr`, and fundamental commands for inspecting data frames (`View`, `str`, `summary`, `dim`, etc.).
*   **`day_03.R`**: Explains core R data types (numeric, character, logical) and data structures (vector, matrix, array, list, data frame).
*   **`day_04.R`**: Demonstrates how to use built-in datasets, subset data frames, use indexing, combine data with `rbind` and `cbind`, and calculate descriptive statistics (mean, median, mode, variance, SD).
*   **`day_06.R`**: Walks through the steps of hypothesis testing using a one-sample t-test, including checking for normality with the Shapiro-Wilk test.
*   **`two_sample_t.test_unpaired.R`**: Provides an example of an unpaired two-sample t-test. It includes checking for normality and homogeneity of variances (`var.test`).
*   **`two_sample_t.test_paired.R`**: Provides an example of a paired two-sample t-test for dependent samples.
*   **`data_visualization.R`**: A comprehensive guide to data visualization using `ggplot2`. This script covers data import/export with `readxl` and `writexl`, data summarization with `dplyr`, and creating various plots including scatter plots, jitter plots, violin plots, and customized box plots.

## Key Concepts Covered

*   **R Basics**: Syntax, variables, and data structures.
*   **Data Handling**: Importing and exporting data (CSV, XLSX), subsetting, and inspecting data frames.
*   **Data Manipulation**: Grouping and summarizing data using `dplyr`.
*   **Descriptive Statistics**: Calculating measures of central tendency (mean, median, mode) and dispersion (variance, standard deviation, range, IQR).
*   **Hypothesis Testing**:
    *   Normality Tests (Shapiro-Wilk)
    *   Homogeneity of Variance Tests
    *   One-Sample t-test
    *   Two-Sample t-test (Paired and Unpaired)
*   **Data Visualization with `ggplot2`**:
    *   Scatter Plots
    *   Jitter Plots
    *   Violin Plots
    *   Box Plots

## Getting Started

To use these scripts, you will need to have R and RStudio installed on your system.

1.  Clone this repository to your local machine:
    ```sh
    git clone https://github.com/yasirqurashi/r_for_statistical_analysis.git
    ```
2.  Open the `.R` files in RStudio.
3.  Install the required packages by running the `install.packages()` commands found at the beginning of the scripts.
4.  Run the code line by line to follow the examples.

## Required Packages

The following R packages are used in these scripts. You can install them from the R console:

```R
install.packages("ggplot2")
install.packages("dplyr")
install.packages("readxl")
install.packages("writexl")
install.packages("readr")
install.packages("modeest")
