# Predicting Which Municipal corporation Of Several European provinces Will Generate maximum Revenue And The factors Associated With It 

## Aim

The aim of this project is to predict future revenue generation potential for municipal corporations in various provinces of Italy through waste management. We seek to understand the factors contributing to excessive waste production and develop a prediction model that assists municipal corporations in estimating the revenue required to manage waste efficiently.

## Purpose

This project is focused on identifying the key factors that lead to high waste generation and using those insights to estimate the revenue that can be generated from waste management. By analyzing the types and quantities of waste produced (such as plastic, wood, and metal), along with other parameters like residual and sorted per capita cost, we aim to support municipal corporations in their waste management efforts.

## Research Hypothesis

- **Null Hypothesis**: The revenue generated by a province’s municipal corporation is not dependent on factors such as the type of waste generated, area population, etc.
- **Alternate Hypothesis**: The revenue generated by a province’s municipal corporation is associated with and dependent on factors like the type of waste generated, area population, etc.

## Methodology

### 1. Data Collection

Data was sourced from a dataset titled "Municipal Waste Management Cost Prediction" available on Kaggle.com. [Link to dataset](https://www.kaggle.com/datasets/shashwatwork/municipal-waste-management-cost-prediction)

### 2. Data Storage

The dataset is stored in a SQL database for efficient access and manipulation.

### 3. Data Cleaning and Extraction

Using Pandas in Jupyter notebooks, data was cleaned and extracted from the SQL database. This process included handling missing values, removing duplicates, and identifying outliers.

### 4. Data Analysis

We conducted normality tests, correlation analysis, and statistical hypothesis testing to explore the relationship between various factors and revenue generation.

### 5. Model Development

We employed several predictive analysis models, including Support Vector Regression, Linear Regression, and Random Forest Regression, to forecast revenue.

### 6. Data Visualization

Choropleth Maps were proposed to visualize the data, highlighting regional differences in waste generation and revenue potential.

## Results

Our analysis revealed a weak association between the types of waste generated, per capita cost, area population, and the revenue generated by municipal corporations. Specifically:

- Most types of waste showed a weak negative correlation with revenue, with the exception of glass.
- Per capita cost and area demonstrated a weak positive correlation with revenue.

## Conclusion

The factors examined in this study—such as the type of waste generated, area population, and per capita cost—have a weak association with the revenue generated by municipal corporations in Italy. This suggests that while these factors do influence revenue to some extent, other unexamined variables may also play a significant role.



