Final Project - Data Science

Clara Eljaschewitsch
DS 310 – Introduction to Data Science
Wed 12/13/2023

Overview

This project explores various datasets to analyze relationships between different attributes and their impact on outcomes. The analysis involves examining automobile fuel efficiency, call center customer satisfaction, and leveraging visualizations to provide insights.

Table of Contents

Project Overview
Dataset Descriptions
Data Exploration and Preprocessing
Model Results
Visualization
Conclusion
Links
Project Overview

The primary objective of this project is to investigate various aspects of the datasets and derive meaningful insights through exploratory data analysis and regression modeling.

Dataset Descriptions

Part 1: Automobile MPG Analysis
Dataset: auto-mpg.csv

Description: Analyzed the relationship between vehicle attributes and fuel efficiency (MPG).
Key Variables: Horsepower, Weight, Cylinder Count, Displacement, Acceleration, MPG.
Part 2: Call Center Data Analysis
Dataset: Call_Center.csv

Description: Explored customer satisfaction, call duration impact, and primary reasons for customer calls.
Key Variables: Call Duration, CSAT Score, Call Reasons.
Data Exploration and Preprocessing

Part 1: Automobile MPG Analysis
Data Cleaning: Addressed missing values and ensured accuracy for analysis.
Exploratory Data Analysis: Visualized relationships, notably between horsepower and MPG.
Modeling: Performed simple and multiple linear regression analyses.
Part 2: Call Center Data Analysis
Data Cleaning: Handled missing values in CSAT scores.
Exploratory Data Analysis: Examined distribution of CSAT scores and relationship with call duration.
Insights: Analyzed primary reasons for customer calls.
Model Results

Part 1: Automobile MPG Analysis
Simple Linear Regression:
R-squared: 0.611
Adjusted R-squared: 0.604
Equation: MPG = 35.31 - 0.13 * Horsepower
Multiple Linear Regression:
R-squared: 0.762
Adjusted R-squared: 0.745
Equation: MPG = 38.9644 - 0.4973 * Cylinder - 0.0098 * Displacement - 0.0039 * Weight - 0.0579 * Acceleration
Part 2: Call Center Data Analysis
CSAT Score Distribution: Mean CSAT Score: 5.55
Call Duration vs. CSAT: Correlation coefficient of -0.006, indicating negligible relationship.
Visualization

Visualizations were created using Tableau Public to enhance the interpretability of the data.

Scatterplot: Shows the relationship between car name, horsepower, and weight.
Packed Bubbles: Illustrates car name, cylinder count, and weight.
Bar Graph: Compares car name, horsepower, and MPG.
Explore the visualizations [here:](https://public.tableau.com/views/Final_Project_17022405943780/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link).

Conclusion

The project reveals key insights into automobile fuel efficiency and customer satisfaction trends. While the multiple regression model for MPG provided a strong explanation of variance, the call center analysis indicated limited impact of call duration on customer satisfaction.

