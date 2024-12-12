# Diabetes Risk Prediction Using BRFSS 2015 Data

## Description

This project uses the BRFSS 2015 dataset to predict diabetes risk. It analyzes health survey responses from over 400,000 Americans to identify key risk factors and build accurate models. The goal is to aid early diagnosis and intervention, improving quality of life for those at risk.

## About the Dataset

The dataset is derived from the Behavioral Risk Factor Surveillance System (BRFSS) 2015 survey conducted by the CDC. It includes responses from 441,455 individuals and contains 330 features. The dataset has been cleaned and consolidated into three files:

- `diabetes_012_health_indicators_BRFSS2015.csv`: 253,680 responses with three classes for the target variable (0 for no diabetes or only during pregnancy, 1 for prediabetes, and 2 for diabetes).
- `diabetes_binary_5050split_health_indicators_BRFSS2015.csv`: 70,692 responses with a balanced 50-50 split for the target variable (0 for no diabetes, 1 for prediabetes or diabetes).
- `diabetes_binary_health_indicators_BRFSS2015.csv`: 253,680 responses with two classes for the target variable (0 for no diabetes, 1 for prediabetes or diabetes).

## Context

Diabetes is a prevalent chronic disease in the United States, affecting millions and imposing a significant economic burden. Early diagnosis and effective treatment are crucial for managing diabetes and preventing complications such as heart disease, vision loss, lower-limb amputation, and kidney disease. Predictive models can help identify individuals at risk and facilitate early intervention.

## Content

The dataset includes responses to various health-related questions and calculated variables. Key features include demographic information, health behaviors, and chronic health conditions. The target variables are:
- `Diabetes_012`: 0 for no diabetes or only during pregnancy, 1 for prediabetes, and 2 for diabetes.
- `Diabetes_binary`: 0 for no diabetes, and 1 for prediabetes or diabetes.

## Research Questions

- Can survey questions from the BRFSS provide accurate predictions of whether an individual has diabetes?
- What risk factors are most predictive of diabetes risk?
- Can we use a subset of the risk factors to accurately predict whether an individual has diabetes?
- Can we create a short form of questions from the BRFSS using feature selection to accurately predict if someone might have diabetes or is at high risk of diabetes?

## Acknowledgements

This dataset was created from the BRFSS 2015 dataset available on Kaggle: https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset. The original dataset can be found here. The data cleaning notebook can be found here. This project was inspired by the work of Zidian Xie et al. on building risk prediction models for type 2 diabetes using the 2014 BRFSS dataset.

## Our Process

1. **Data Preparation**: Load the dataset and perform any necessary preprocessing.
2. **Exploratory Data Analysis (EDA)**: Analyze the dataset to understand the distribution of features and target variables.
3. **Model Building**: Use machine learning techniques to build predictive models.
4. **Evaluation**: Evaluate the models using appropriate metrics to ensure accuracy and reliability.
5. **Feature Selection**: Identify the most predictive features and consider creating a short form of the survey.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
