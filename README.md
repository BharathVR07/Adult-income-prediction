# Adult-income-prediction

## Project Overview
• Created a machine learning model that predicts the income of an Adult.

## How will this project help?
• This project helps an adult to know their income based on the features like education, age, workclass, and marital-status.

## Resources Used
• Packages: pandas, numpy, matplotlib, seaborn, scikit-learn.

• Dataset by Kaggle : https://www.kaggle.com/datasets/wenruliu/adult-income-dataset

## Exploratory Data Analysis (EDA) and Data Cleaning
• Replacing the features having ? with mode imputation. (occupation, country, workclass)

![image](https://user-images.githubusercontent.com/110616143/185020503-4472bded-bf15-4587-b21e-5a26895319ce.png)

• Plotted bargraphs, pie charts,countplots and heatmap for numerical and categorical features for EDA.

![image](https://user-images.githubusercontent.com/110616143/185020673-f3e6edd2-f5f6-4a1d-9e80-3984ba17aec3.png)

• Cleaning the features education, workclass and marital-status.

![image](https://user-images.githubusercontent.com/110616143/185020965-df0627af-2f7c-4911-a9da-aa8535b5867c.png)

## Feature Engineering
• Handling the ordinal and nominal categorical features using encoding techniques like one-hot encoding and ordinal encoding.

• Handling the imbalanced dataset using over sampling technique RandomOverSampler.

## Feature Selection
• Feature selection using mutual info gain (mutual info classif) and SelectKBest to select the top features.
![image](https://user-images.githubusercontent.com/110616143/185022344-313e87f0-b0ca-409e-b50e-91c3317ac1c3.png)

## Model Creation and Evaluation
Metrics : accuracy score.

• Logistic Regression - 78.6%

• KNN Classifier - 79.7%

• Naive Bayes - 74.8%

• Random Forest Classifier - 87.4%

• XG Boost Classifier - 82.8%

• Ada Boost Classifier - 79.8%

### Confusion matrix for Random Forest Classifier
![image](https://user-images.githubusercontent.com/110616143/185022873-1f3fe702-4392-4c9b-bcfe-f40b821647d8.png)

## Model Prediction
<img width="678" alt="image" src="https://user-images.githubusercontent.com/110616143/185023057-8a0ae014-1a64-4f58-a7e8-9a6ee7d9929b.png">
