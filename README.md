# Exploratory Data Analysis and Predicting the Survived of the Titanic

## Introduction

The Titanic dataset is a popular dataset used in data science projects. The dataset contains information on passengers who were aboard the Titanic when it sank. This project aims to perform an exploratory data analysis on the Titanic dataset and use machine learning techniques to predict whether a passenger survived or not.

## Dataset

The Titanic dataset is a public dataset that contains information on passengers who were aboard the Titanic when it sank. The dataset contains 891 observations and 12 variables, including the target variable 'Survived', which indicates whether a passenger survived or not.

## Methodology

The following methodology was used in this project:

1. Importing Libraries: Libraries such as Pandas, Numpy, Matplotlib, Seaborn, and Scikit-learn were imported for data manipulation, visualization, and machine learning.

2. Loading the Dataset: The dataset was loaded using pd.read_csv() from the local computer.

3. Exploratory Data Analysis: The dataset was explored to identify columns, unique values, missing values, shape of the entire dataset, info of the columns and data types, and statistical analysis of the data. Outliers were also identified in the dataset.

4. Relationship, Insights, and Visualizations: Univariate, bivariate, and multivariate analysis techniques were used to visualize the data and identify patterns and trends. Relationships between variables were explored using scatterplots, boxplots, and heatmaps.

5. Feature Engineering: Categorical variables were encoded to convert them into numerical values so that they can be featured or implemented in the machine learning model.

6. Model Preparation and Deployment: The dataset was split into training and testing sets for use in machine learning models. Several machine learning models were trained and evaluated, including Logistic Regression, Random Forest Classifier, and XGBoost Classifier.

7. Model Evaluation: The models were evaluated using metrics such as accuracy, precision, recall, and F1-score. The best performing model was selected based on these metrics.

## Results

The exploratory data analysis and machine learning models revealed several insights into factors that contributed to passenger survival:

- Women and children were more likely to survive.
- Passengers in higher class cabins were more likely to survive.
- Passengers who embarked from Cherbourg were more likely to survive.
- Passengers who were traveling alone were less likely to survive.

These insights can help us understand the factors that contributed to passenger survival and can be used to develop strategies to improve safety measures on future voyages.

## Conclusion

Through exploratory data analysis and machine learning models on the Titanic dataset, we gained insights into factors that contributed to passenger survival. By understanding these factors, we can develop strategies to improve safety measures on future voyages.