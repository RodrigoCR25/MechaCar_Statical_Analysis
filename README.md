# MechaCar_Statical_Analysis

# I Learned

By the end of this module, you will be able to: 

Load, clean up, and reshape datasets using tidyverse in R.

Visualize datasets with basic plots such as line, bar, and scatter plots using ggplot2.

Generate and interpret more complex plots such as boxplots and heatmaps using ggplot2.

Plot and identify distribution characteristics of a given dataset.

Formulate null and alternative hypothesis tests for a given data problem.

Implement and evaluate simple linear regression and multiple linear regression models for a given dataset.

Implement and evaluate the one-sample t-Tests, two-sample t-Tests, and analysis of variance (ANOVA) models for a given dataset.

Implement and evaluate a chi-squared test for a given dataset.

Identify key characteristics of A/B and A/A testing.

Determine the most appropriate statistical test for a given hypothesis and dataset.

_____________________________________________________________________________________________________________________________________________________________

# Objetive

An statistical analysis with R on the MechaCar for data review for insights to help manufacturing team.

____________________________________________________________________________________________________________________________________________________________

# Linear Regression to Predict MPG

![image](https://github.com/RodrigoCR25/MechaCar_Statical_Analysis/blob/main/MPG_linear%20_regression.png)

_____________________________________________________________________________________________________________________________________________________________

# Summary Statistics on Suspensions Coils

![image](https://github.com/RodrigoCR25/MechaCar_Statical_Analysis/blob/main/Total_summary.png)


![image](https://github.com/RodrigoCR25/MechaCar_Statical_Analysis/blob/main/Lot_summary.png)
_____________________________________________________________________________________________________________________________________________________________

# T-Tests on Suspension Coils

![image](https://github.com/RodrigoCR25/MechaCar_Statical_Analysis/blob/main/T_test_all.png)


![image](https://github.com/RodrigoCR25/MechaCar_Statical_Analysis/blob/main/T_test_by_lot.png)

_____________________________________________________________________________________________________________________________________________________________
Study design: MechaCar vs Competition
________________________________________
Chi-square test: security rating over the years by different rating agencies

The idea is to collect enough data that a third party has researched and classified over the years. It is proposed that it be a separate entity from the company to avoid bias and not mess with randomness. The main metric to test is safety, as it has always been one of the most fundamental parts of a car, and as time has passed this is still true, but what is also true is that technology has improved over time. the years.

So it's safe to assume that security technology is better now than ever. In order to demonstrate that our car, the assembly was carried out under one of the highest security protocols in history, because a null hypothesis will be tested. H0: The distribution of the classification number in the different classification systems is similar. Thus demonstrating that since its inception AutosRUs has always generally provided the best safety in cars.

The Chi-square test is the best option, since two inputs of categorical data will be used (rank number and rank system), and we primarily want to see if there is a difference in the frequencies of the overall rank number across multiple ranks. . Therefore, you need a data file that contains two columns and as many rows as possible. The columns would be "Classification System", with different organization classifications, and "Classification Number" the actual number.
