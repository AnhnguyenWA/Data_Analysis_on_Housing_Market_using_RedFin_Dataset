# Housing Market Analysis in Zip Codes 98404 and 98466

# Introduction
This repository contains an analysis of the housing market in two distinct zip codes: 98404 and 98466. The analysis using R programming language focuses on various features of houses SOLD in these areas in the past year, including baths, beds, year built, and most importantly, prices. 

# Data Exploration
The analysis begins with loading and exploring the datasets for both zip codes using the read_excel function from the readxl package. The datasets contain information about houses, including their features and prices. After loading the data, exploratory data analysis techniques such as viewing the datasets and creating histograms are employed to understand the distribution of house prices in each zip code.

# Visualizing Relationships
To understand the relationships between house prices and various features such as baths, beds, square feet, lot size, and year built, scatter plots are created for both zip codes. These visualizations provide insights into how these features influence house prices in each area.

# Statistical Inference
The analysis further goes into statistical inference to test specific claims about the housing market in each zip code. Two key hypotheses are tested:
Square Footage: The analysis tests whether the average square footage of houses in each zip code differs significantly from 2000 square feet using one-sample t-tests.
 - For Zip Code 98404, the test results indicate a significant difference in average square footage from 2000 square feet.
 - Similarly, for Zip Code 98466, the test results also show a significant difference in average square footage from 2000 square feet.
Number of Bathrooms: Another hypothesis tests whether the average number of bathrooms in each zip code is greater than 3 using one-sample t-tests.
 - For both Zip Codes 98404 and 98466, the analysis does not find sufficient evidence to conclude that the true mean number of baths is greater than 3.

# Conclusion
In summary, this analysis compares housing markets in zip codes 98404 and 98466. We explored house features like baths, beds, and square footage, focusing on prices. Also, the findings suggest significant differences in average square footage from 2000 sqft in both areas. However, there's no strong evidence that the average number of baths exceeds 3. 
