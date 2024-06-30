# Homestays Data Analysis and Price Exploration

![Header Image](https://www.softqubes.com/wp-content/uploads/2023/04/researched-poc-on-hotel-price-prediction.webp)

This repository contains a comprehensive analysis and exploration of homestay pricing data. The project covers various stages from feature engineering to predictive performance assessment, providing valuable insights into the factors influencing homestay prices.

## Table of Contents
1. [Feature Engineering](#feature-engineering)
2. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
3. [Geospatial Analysis](#geospatial-analysis)
4. [Sentiment Analysis on Textual Data](#sentiment-analysis-on-textual-data)
5. [Amenities Analysis](#amenities-analysis)
6. [Categorical Data Encoding](#categorical-data-encoding)
7. [Model Development and Training](#model-development-and-training)
8. [Model Optimization and Validation](#model-optimization-and-validation)
9. [Feature Importance and Model Insights](#feature-importance-and-model-insights)
10. [Predictive Performance Assessment](#predictive-performance-assessment)

## Feature Engineering
Enhancing the dataset by creating insightful features:
- **Host_Tenure:** Calculate the number of years from `host_since` to the current date.
- **Amenities_Count:** Count the items listed in the `amenities` array.
- **Days_Since_Last_Review:** Calculate the days between `last_review` and today.

## Exploratory Data Analysis (EDA)
Conducting a deep dive into the dataset to uncover patterns:
- Analyze how `log_price` correlates with categorical and numerical features.
- Use statistical tools and visualizations such as correlation matrices, histograms, and scatter plots.

## Geospatial Analysis
Investigating geographical data to understand regional pricing trends:
- Plot listings on a map using `latitude` and `longitude`.
- Examine if neighbourhoods or proximity to city centres influence pricing.

## Sentiment Analysis on Textual Data
Applying NLP techniques to extract sentiment scores from `description` texts:
- Determine the impact of positive or negative descriptions on listing prices.
- Incorporate sentiment findings into the predictive model.

## Amenities Analysis
Parsing and analyzing the `amenities` provided in the listings:
- Identify amenities associated with higher or lower prices using statistical tests.

## Categorical Data Encoding
Converting categorical data into a machine learning-friendly format:
- Apply one-hot encoding to variables like `room_type`, `city`, and `property_type`.

## Model Development and Training
Designing and training predictive models to estimate `log_price`:
- Start with linear regression as a baseline.
- Explore more complex models such as RandomForest and GradientBoosting.

## Model Optimization and Validation
Systematically optimizing the models for best performance:
- Employ grid search for hyperparameter tuning.
- Validate models using k-fold cross-validation.

## Feature Importance and Model Insights
Identifying significant features impacting `log_price`:
- Use feature importance scores and SHAP values for in-depth understanding.

## Predictive Performance Assessment
Evaluating the final model on a reserved test set:
- Use metrics like RMSE and R-squared to assess accuracy.
- Analyze residuals to check for model biases or misfits.

## Getting Started
To get started with the project, clone the repository and follow the instructions provided in the [setup guide](SETUP.md).