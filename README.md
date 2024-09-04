
# Health Analysis Project: Diabetes Prediction

# Project Overview

This project focuses on health data analysis using a diabetes dataset sourced from Kaggle. The primary goal is to explore the data, perform exploratory data analysis (EDA), and build predictive models to assess the risk of diabetes in individuals.

# Dataset
The dataset used in this project contains the following features:

* Pregnancies: Number of pregnancies
* Glucose: Plasma glucose concentration after 2 hours in an oral glucose tolerance test
* BloodPressure: Diastolic blood pressure (mm Hg)
* SkinThickness: Triceps skinfold thickness (mm)
* Insulin: 2-Hour serum insulin (mu U/ml)
* BMI: Body mass index (weight in kg/(height in m)^2)
* DiabetesPedigreeFunction: A function that scores the likelihood of diabetes based on family history
* Age: Age of the individual (years)
* Outcome: Class variable (0 or 1) indicating whether the individual is diabetic (1) or not (0)


# Project Structure

The project is structured into several key sections:

1. Data Preprocessing
* Loading the dataset using Pandas.
* Handling missing values and data cleaning.

2. Exploratory Data Analysis (EDA)
* Univariate Analysis: Analyzing each feature individually to understand its distribution and characteristics.
* Kernel Density Estimation (KDE) Plots: Visualizing the probability density function of selected features.
* Count Plots: Describing the count and distribution of categorical variables.
* Data Exploration: Understanding relationships between features and their impact on the target variable (Outcome).
* Inference from Outlier Distribution: Identifying and analyzing outliers in the data.
* Multivariate Analysis: Exploring interactions between multiple features.

3. Model Building and Evaluation

* Comparing the accuracy of various models to predict diabetes based on the given features.
* Implemented models include Logistic Regression, Decision Trees, and others from the scikit-learn library.

# Libraries Used

* Pandas: For data manipulation and analysis.
* NumPy: For numerical computations.
* Matplotlib: For data visualization.
* seaborn: For enhanced visualization techniques.
* scikit-learn: For machine learning model building and evaluation.

# Results

The project concludes with a comparison of the accuracy of different machine learning models in predicting the likelihood of diabetes. The performance of each model is evaluated using appropriate metrics.

