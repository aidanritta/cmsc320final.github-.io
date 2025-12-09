# Used Vehicle Sales Price Prediction  
_Final Project – CMSC320 (Fall 2025)_  
<br>
Zachary Gottlieb, Kehan Bhati, Joseph Jenkins, Jack Perlman, Simon Benarroch, Aidan Ritta

## Contributions
Zachary: (A, B, C, F, G, H) Found dataset, completed summary statistics, and visualizations. Did the linear regressions for log age-at-sale vs selling price.
<br><br>
Kehan: (A, F, G, H) Wrote the introduction, formatted the final deliverable, brainstormed for the project idea, and helped with analyzing final results. 
<br><br>
Joseph: (C, E, F) Assisted in data exploration and creating/revising conclusions. Updated and revised ML analysis and conclusions. Created all visualization section and analysis.
<br><br>
Jack:
<br><br>
Simon:
<br><br>
Aidan: (F, G) Did the conclusion and helped with the formatting throughout the whole document.
<br><br>



## Introduction
&nbsp;&nbsp;&nbsp;&nbsp;Accurately predicting the price of a used car is an important challenge with many complexities. It has great value for both consumers and professional members of the automobile industry. This project focuses on understanding which factors strongly influence the selling price of used cars and on developing a predictive model that can estimate prices based on those factors. Since car purchases are one of the largest financial decisions made by many individuals, accurate pricing is essential for helping consumers avoid overpaying and helping sellers accurately value their vehicles.
<br><br>
&nbsp;&nbsp;&nbsp;&nbsp;The significance of our analysis extends beyond individual transactions; pricing insights can also help dealerships, online marketplaces, and businesses make large-scale decisions. This investigation centers on several key questions: Which characteristics are most strongly correlated with selling price? How accurately does a machine learning model predict used car prices using these features? What patterns about the used vehicle market can be revealed through this analysis? How can these patterns be utilized to benefit both consumers and sellers of the industry? Our project aims to answer these questions through the study of the Vehicle Sales dataset from Kaggle. The predictive model provides key insights which can help anyone improve their decision-making in the used vehicle marketplace.



## Data Curation

## Exploratory Data Analysis

## Primary Analysis

## Visualization

## Insights and Conclusion
&nbsp;&nbsp;&nbsp;&nbsp;Throughout this tutorial, we reviewed some data science steps to create a machine learning model capable of accurately predicting the price of a used car. To build this model, we had to identify the characteristics that influence the selling price of used cars. As expected, we demonstrated that the age and mileage of the vehicle are inversely correlated with its selling price. Besides age and mileage, we discovered that the Manheim Market Report (MMR) valuation is the best predictor of the final selling price. In summary, market estimation alone is very accurate, but additional factors such as the condition and age of the vehicle can also influence the final price.


However, the results go beyond simple correlation. We examined the risk of overfitting by comparing a linear regression model to a ridge regression model. The results showed that while a simple linear model explained most of the variance (coefficient of determination, R²), the ridge regression model predicted the test data slightly better, thus providing a more robust model that is more easily generalizable to new data.


This project shows that there is predictability in the apparent randomness of used car prices. Vehicle prices follow dependable trends related to their attributes, such as MMR and log age, trends that can be effectively modeled. Our resulting models can be very powerful tools for determining the proper fair market value of a used vehicle. for both buyers and sellers.
