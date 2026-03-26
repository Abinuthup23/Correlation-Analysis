Geography 411 – Homework 3: Correlation Analysis
Overview
This repository contains the R code and analysis for the Geography 411 homework assignment. The goal of the analysis is to examine the relationship between GDP per capita and life expectancy across countries and determine whether the two variables are significantly associated.
Methods
The following statistical analyses were performed on the data:
• Histograms: To examine the distributions of GDP per capita and life expectancy.
• Scatterplot: To visualize the relationship between GDP per capita and life expectancy.
• Pearson’s Correlation Test: To test for a significant linear relationship between GDP per capita and life expectancy.
• Spearman’s Rank Correlation Test: To test for a significant monotonic relationship between GDP per capita and life expectancy.
Key Findings
• Both Pearson’s and Spearman’s tests showed a statistically significant positive relationship between GDP per capita and life expectancy.
• Pearson’s correlation was positive, indicating that countries with higher GDP per capita generally had higher life expectancy.
• Spearman’s correlation was also positive and slightly stronger, suggesting a strong monotonic relationship between the two variables.
• The scatterplot showed an overall upward trend, with some clustering among lower-, middle-, and higher-income countries.
Tools
• R: The analysis was conducted using the R programming language. The main functions used included hist(), plot(), cor(), cor.test(), and text().
• RStudio: RStudio was used to run the code and visualize the output.
• GitHub: GitHub was used to store and organize the project files.
Reflection
This analysis helped me better understand how to measure and interpret relationships between two variables using both visualizations and correlation tests. It also showed the difference between Pearson’s and Spearman’s correlation and why Spearman’s can be more useful when the data are skewed or not perfectly linear.
