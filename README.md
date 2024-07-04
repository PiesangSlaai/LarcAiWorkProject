Files included in this project:
 1. EDA
 2. Model

- EDA is performed on the term deposit subscription dataset to understand the distribution and relationships of various features in the data. summarizing it, and handling special missing values. Univariate analysis using histograms and bar plots examined distributions, while bivariate analysis explored relationships using scatter plots, box plots, and correlation matrices. Categorical variables were analyzed for distribution and proportions across different categories. Detailed analysis was performed on key variables like age, balance, duration, and categorical features to understand their impact on the target variable. The findings from this EDA provide valuable insights for guiding subsequent modeling efforts.

- A CatBoost model pipeline was constructed to predict subscription to term deposits, involving data preprocessing, sampling, and model evaluation. Initially, the dataset was cleaned by removing outliers, mapping categorical variables, and creating new feature proportions. The cleaned data was split into training and testing sets, with preprocessing steps including standard scaling for numerical features and one-hot encoding for categorical features. Random over-sampling and under-sampling were applied to address class imbalance. The CatBoost model was trained with specified hyperparameters. SHAP values were calculated for feature importance analysis, providing insights into the model's decision-making process.
