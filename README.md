# Bike Crash Analysis

Original Data Link:
https://opendata-townofchapelhill.hub.arcgis.com/datasets/NCDOT::bicycle-crashes-2007-to-2019/data?geometry=-87.577%2C33.565%2C-71.921%2C36.709&orderBy=County&selectedAttribute=BikeAgeGrp

Project Details:
Data Breakdown for example: Dataset describes traffic crash parameters, including date of crashes, street name, weather condition, posted speed limit, traffic way type, types of road defects etc.

Goals
We will be predicting whether an accident reported is a:
Suspected Serious Injury 
Suspected Minor Injury 
Any Possible Injury 
Killed
No Injury
Unknown Injury

Dataset parameters were used to predict "CrashSevr".

Problems:
1. A lot of columns have no rank or order. So we transform to dummy variables.
2. Encode some categorical variables to numeric value
3. Change 'Unknown' bikers and drivers age to median

Methods Used: 
Data Cleaning
Data Organizing/Exploring
Data Visualization
LabelEncoding, OneHotEncoding
Feature Engineering
Machine Learning
Predictive Modeling
Random Search CV
Grid Search CV
Feature of Importance

Metrics Used:
Recall

Models Used:
KNN
Naive Bayes
Decision Tree
Random Forest


