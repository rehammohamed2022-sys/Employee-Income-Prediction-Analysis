# Employee Income Prediction Analysis

## Regression Modeling and Machine Learning Project

### Overview

Understanding the factors that influence employee compensation is essential for workforce planning, human resource management, and organizational decision-making. This project investigates the determinants of employee monthly income using an HR Analytics dataset and applies both statistical and machine learning techniques to identify the key drivers of compensation.

The analysis combines exploratory data analysis, multiple linear regression, log-transformed regression, stepwise model selection, and decision tree modeling to explain and predict employee income. The study evaluates how demographic, educational, and professional characteristics contribute to variations in compensation and compares traditional statistical approaches with machine learning methods.

---

## Research Objectives

* Explore workforce demographics and compensation patterns.
* Identify the strongest predictors of employee income.
* Build and evaluate regression models for salary prediction.
* Improve model assumptions through transformation techniques.
* Apply machine learning methods for income prediction.
* Compare statistical and machine learning approaches.

---

## Dataset

The analysis uses the HR Analytics Dataset containing employee demographic, educational, and employment information.

### Key Variables

#### Target Variable

* Monthly Income

#### Demographic Variables

* Age
* Gender

#### Educational Variables

* Education Level

#### Organizational Variables

* Department

#### Professional Variables

* Total Working Years
* Years Since Last Promotion

---

## Statistical Methods

### Exploratory Data Analysis (EDA)

* Descriptive Statistics
* Histograms
* Boxplots
* Bar Charts
* Pie Charts
* Correlation Analysis
* Mosaic Plot Analysis

### Multiple Linear Regression

A multiple regression model was developed to quantify the relationship between employee income and demographic, educational, and professional characteristics.

The model was used to:

* Estimate predictor effects
* Test statistical significance
* Identify major compensation drivers

### Log-Transformed Regression

A logarithmic transformation of income was applied to improve model assumptions and address:

* Income skewness
* Heteroscedasticity
* Non-normal residuals

### Stepwise Regression

Automatic variable selection was performed using:

* Forward Selection
* Backward Elimination
* Akaike Information Criterion (AIC)

to identify the most parsimonious predictive model.

### Decision Tree Regression

A machine learning model was developed to capture nonlinear relationships and improve predictive accuracy.

Predictors included:

* Age
* Gender
* Education
* Department
* Total Working Years
* Years Since Last Promotion

---

## Model Evaluation

### Regression Diagnostics

* Residual Analysis
* Variance Inflation Factor (VIF)
* Durbin-Watson Test
* Model Assumption Assessment

### Predictive Performance

* Root Mean Squared Error (RMSE)
* Training and Test Evaluation
* R-Squared
* Adjusted R-Squared

---

## Key Findings

### Experience and Compensation

* Total Working Years was consistently identified as the strongest predictor of employee income.
* Employee compensation increased substantially with professional experience.
* Experience remained the dominant predictor across all statistical and machine learning models.

### Department Effects

* Employees in Sales tended to earn higher salaries than employees in Human Resources.
* Departmental effects were most apparent among employees with lower and moderate levels of experience.

### Education Effects

* Higher educational attainment was associated with increased income.
* After controlling for experience, education contributed less strongly than expected.

### Demographic Effects

* Gender showed no significant effect on employee income.
* Age became largely insignificant once work experience was included in the model.

### Machine Learning Insights

* Decision tree analysis revealed that experience drives the majority of compensation differences.
* Nonlinear relationships between experience and income were successfully captured by the tree model.
* Decision trees achieved stronger predictive performance than traditional regression models.

---

## Software

* R
* RStudio

---

## Repository Contents

* Final project report
* R scripts
* Data preprocessing code
* Exploratory data analysis outputs
* Regression model outputs
* Stepwise regression results
* Decision tree models
* Diagnostic analyses
* Visualizations and plots

---

## Skills Demonstrated

* Multiple Linear Regression
* Log-Transformed Regression
* Stepwise Model Selection
* Decision Tree Regression
* Predictive Modeling
* Statistical Inference
* Model Diagnostics
* Human Resource Analytics
* Data Visualization
* Machine Learning
* Statistical Computing in R

---

## Keywords

Statistics, HR Analytics, Employee Compensation, Salary Prediction, Multiple Linear Regression, Stepwise Regression, Decision Trees, Predictive Modeling, Machine Learning, Workforce Analytics, Data Science, R Programming


Cairo University
