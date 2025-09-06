# Statistical Analysis Project with Python

*This project was completed as part of the "Statistics with Python" course for my Master's degree in Statistics at the University of Strasbourg (2024-2025).*

## Overview

This project applies various inferential statistics methods to solve three distinct problems. The entire analysis is conducted in Python, using key scientific libraries such as Pandas, SciPy, and Statsmodels.

## Project Objectives

The project is divided into three independent exercises:

1.  **Exercise 1: Chi-Squared Test of Independence**
    * **Goal:** To determine whether hair color is independent of gender in a sample from a Scottish district.

2.  **Exercise 2: Two-Sample T-Test for Means**
    * **Goal:** To answer the question: "Is there a statistically significant weight difference between two types of Alsatian brioches, 'Manele' and 'Manala'?"

3.  **Exercise 3: Analysis of Variance (ANOVA)**
    * **Goal:** To determine if the average thickness of collectible stamps differs significantly across four countries: Germany, Austria, Belgium, and France.

## Skills & Tools

* **Language:** Python
* **Libraries:**
    * `pandas` for data manipulation and cleaning.
    * `scipy.stats` for performing statistical tests (Chi-squared test, Shapiro-Wilk test, Student's t-test, ANOVA).
    * `statsmodels` for post-hoc tests (Tukey's HSD test).
    * `matplotlib` & `seaborn` for data visualization (boxplots, histograms).
* **Statistical Methods:**
    * Descriptive Statistics.
    * Chi-Squared Test of Independence.
    * Independent Samples t-test.
    * Assumption checking: Normality (Shapiro-Wilk test).
    * One-Way Analysis of Variance (ANOVA).
    * Tukey's HSD for multiple comparisons.

## Project Structure

* `Statistical_Analysis.ipynb`: The Jupyter Notebook containing all Python code, analysis, and visualizations for the three exercises.
* `data/`: The directory containing the `Man.csv` and `timbres.csv` datasets.
* `Project_Report.pdf`: The original final report (in French) summarizing the methodology and conclusions for each analysis.

## Key Findings

* **Exercise 1:** The Chi-squared test revealed a statistically significant association between hair color and gender in the studied sample.
* **Exercise 2:** The t-test found no significant weight difference between 'Manele' and 'Manala' brioches, leading to the conclusion that their average weights are statistically equal.
* **Exercise 3:** The ANOVA indicated a significant difference in the mean thickness of stamps between at least two countries. The Tukey post-hoc test clarified that French stamps are significantly thinner than those from the other three countries (Germany, Austria, Belgium), among which no significant differences were found.

## How to Run

1.  Clone this repository to your local machine.
2.  Ensure you have the required libraries installed (e.g., `pip install pandas scipy statsmodels matplotlib seaborn jupyter`).
3.  Open and run the `Statistical_Analysis.ipynb` notebook in a Jupyter environment.
