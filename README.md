# World Happiness Report

This project analyzes the World Happiness Report using Python and various data analysis libraries and algorithms. The goal is to explore the factors contributing to happiness across different countries and identify patterns in the data.

## Table of Contents

1. [Introduction](#introduction)
2. [Dependencies](#dependencies)
3. [Data](#data)
4. [Methods](#methods)
5. [Results](#results)
6. [Conclusion](#conclusion)

## Introduction

The World Happiness Report is a survey of the state of global happiness, which ranks countries based on their citizens' happiness levels. This project aims to gain insights into the factors that contribute to happiness and cluster countries based on their happiness scores.

## Dependencies

This project uses Python and the following libraries:

- pandas
- matplotlib
- seaborn
- scipy
- scikit-learn

To install the dependencies, run:

```
pip install pandas matplotlib seaborn scipy scikit-learn
```

## Data

The dataset used in this project is the World Happiness Report, which can be downloaded from [Kaggle](https://www.kaggle.com/unsdsn/world-happiness). The dataset contains information about the happiness score, GDP per capita, social support, life expectancy, freedom to make life choices, generosity, and perceptions of corruption for each country.

## Methods

The following methods were used for the analysis:

1. **Data preprocessing and exploration**: Cleaning the data and visualizing the relationships between variables using seaborn.
2. **Testing normality**: Shapiro-Wilk test to check if the data follows a normal distribution.
3. **Regression**: Linear regression to model the relationship between happiness score and other factors.
4. **Regularization and Cross-validation**: Lasso and Ridge regression with cross-validation to prevent overfitting.
5. **Clustering**: K-means clustering to group countries based on their happiness scores and other attributes.


## Results

The analysis results will be saved as plots and data files in the `results` directory. These files include:

- Correlation matrix plot
![image](https://github.com/ahmed-m-elgammal/world-happiness-report-/assets/102481695/dbda672b-4054-40dc-a8e7-b544c7016a4f)

- Correlation Plot of effect of region
![image](https://github.com/ahmed-m-elgammal/world-happiness-report-/assets/102481695/e48a2e56-68b7-4829-b6e3-6e4f57722e82)

- Shapiro-Wilk test results
![image](https://github.com/ahmed-m-elgammal/world-happiness-report-/assets/102481695/595bed0c-7811-4ef9-ad4b-d2f8cb3db70a)

- Regression coefficients and performance metrics
>R-squared: 0.9922

>Adjusted R-squared: 0.9919

>RMSE: 0.1144

>MAE: 0.0801

- Regularization and cross-validation results
![image](https://github.com/ahmed-m-elgammal/world-happiness-report-/assets/102481695/e0fc9917-64a3-4446-8d7b-9d6c23074d15)

- K-means clustering results
*The Elbow method*
![image](https://github.com/ahmed-m-elgammal/world-happiness-report-/assets/102481695/760ae693-c7f6-4c2e-ae06-1bf44e9d642b)

#### Silhouette metrics

> The average silhouette score is: 0.292032236628384


## Conclusion

This project provides an in-depth analysis of the World Happiness Report using various data analysis techniques and machine learning algorithms. The insights gained from the analysis can help policymakers and researchers understand the factors contributing to happiness and work towards improving the well-being of people around the world.
