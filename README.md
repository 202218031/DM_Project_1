Diamonds Dataset Analysis

Overview

This repository contains an analysis of the Diamonds dataset, which is available here. The dataset consists of various attributes related to diamonds, including cut, color, clarity, carat weight, and more. The primary goal of this analysis is to explore the dataset, perform data preprocessing, and develop predictive models for different objectives related to diamond attributes.

Table of Contents

•	Dataset Overview

•	Data Exploration and Preprocessing

•	Objective 1: Predicting Diamond Price

•	Objective 2: Predicting Carat Weight

•	Objective 3: Predicting Price per Carat Weight

•	Conclusion


Columns

The dataset contains the following columns:
•	cut
•	color
•	clarity
•	carat_weight
•	cut_quality
•	lab
•	symmetry
•	polish
•	eye_clean
•	culet_size
•	culet_condition
•	depth_percent
•	table_percent
•	meas_length
•	meas_width
•	meas_depth
•	girdle_min
•	girdle_max
•	fluor_color
•	fluor_intensity
•	fancy_color_dominant_color
•	fancy_color_secondary_color
•	fancy_color_overtone
•	fancy_color_intensity
•	total_sales_price

Data Summary

•	Descriptive statistics, such as mean, median, and standard deviation, were calculated for numerical attributes.
•	Duplicate rows in the dataset were identified and removed.
•	Missing values were checked, and it was found that most values were labeled as "unknown" or "None" in many columns.
•	The number of unique values in each column was examined.
•	Summary statistics and insights were provided for each attribute.

Data Exploration and Preprocessing

•	Initial Data Analysis (IDA) and Exploratory Data Analysis (EDA) were performed.
•	Insights into the dataset, including data distribution and relationships between attributes, were summarized.
•	Data preprocessing steps included dropping columns with many "unknown" values.
•	Outliers were detected and handled using boxplots.
•	Variable encoding was performed to convert categorical variables into numerical format.

Objective 1: Predicting Diamond Price

•	The goal of this objective was to predict the price of diamonds.
•	The dataset was split into training and testing sets.
•	Feature scaling was applied to standardize the features.
•	Linear Regression, Polynomial Regression, and Random Forest models were trained and evaluated.
•	Hyperparameter tuning was performed to optimize model performance.
•	Regression lines were plotted to visualize the relationships.

Objective 2: Predicting Carat Weight

•	This objective aimed to predict the carat weight of diamonds.
•	Features were scaled to prepare the data for modeling.
•	Linear Regression, Polynomial Regression,Random Forest and Ridge models were employed.
•	Hyperparameter tuning was performed to optimize model performance.
•	Regression lines were visualized for the chosen models.

Objective 3: Predicting Price per Carat Weight

•	The objective was to predict the price per carat weight of diamonds.
•	Features were standardized.
•	Linear Regression, Polynomial Regression (Degree-2), and Polynomial Regression (Degree-3) models were trained.
•	Ridge and Lasso Regression were applied to validate the results.
•	Regression lines were plotted to visualize the predictions.

Conclusion

This analysis provides valuable insights into the Diamonds dataset and offers predictive models for various objectives related to diamond attributes. The models and findings can be useful for pricing and evaluating diamonds in the market.
