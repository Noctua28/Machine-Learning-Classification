# Predicting Wine Quality - A Data Science Approach

![image](https://github.com/Noctua28/Spanish-Wine-Quality-Prediction/assets/65126638/08fcd15d-d8d6-434a-97ac-9f84dffc7d72)

## Business Problem and Stakeholders

Our mission is to predict the quality of wines based on various features to provide useful insights for inventory and production decisions. The stakeholders for this project include wine producers, sellers, and wine connoisseurs who are interested in understanding the factors that contribute to wine quality and in making informed decisions about their products or investments.

## Data Source

The data used for this project was sourced from [Spanish Wine Quality]((https://www.kaggle.com/datasets/fedesoriano/spanish-wine-quality-dataset?resource=download)) by Fedesoriano on Kaggle. This dataset offers diverse information on various types of wines, including details about wineries, wines, regions, and ratings.

## Data Description

The dataset comprises a collection of wine samples with corresponding features and quality ratings. Each sample includes information such as the winery, year of production, wine type, body and acidity levels, and price. The target variable, rating, represents the quality rating of the wine on a numerical scale. The comprehensive and diverse dataset allows for a detailed analysis of the factors influencing wine quality.

## Analytical Insights

The dataset comprises a collection of wine samples with corresponding features and quality ratings. Each sample includes information such as the winery, year of production, wine type, body and acidity levels, and price. The target variable, rating, represents the quality rating of the wine on a numerical scale.

Here are two critical insights derived from our data analysis:

1. Scatter Plot:

![image](https://github.com/Noctua28/Spanish-Wine-Quality-Prediction/assets/65126638/cbeced02-8c38-4cd0-87aa-e84f45c98f7a)

The scatter plot shows the relationship between the price of a bottle of wine and its corresponding quality rating. We can observe a general upward trend, suggesting that higher-priced wines tend to have higher quality ratings.

2. Heatmap:

![image](https://github.com/Noctua28/Spanish-Wine-Quality-Prediction/assets/65126638/d2f36bcd-8d39-48e2-8e79-fc12ac3ab003)

The heatmap shows the correlation between different features in our dataset. Strong correlations exist between wine quality and several factors, such as year, price, and body. These insights allow us to focus our analysis on these highly influential factors.

## Model Metrics

To address the business problem, we adopted a supervised machine learning approach since we had a well-defined target variable - wine quality. The first step was to clean and pre-process the data to suit the model training process. This included normalizing numerical features and encoding categorical features.

We trained multiple models, including Linear Regression, Decision Tree, and Random Forest, and used cross-validation to optimize the model parameters. To avoid overfitting and make our models more generalizable, we split the data into training and test sets.

The 'Random Forest' model was our best-performing model. Here are its performance metrics:

Mean Squared Error (Test Set): 0.0033
Mean Absolute Error (Test Set): 0.0245
R-squared (Test Set): 0.783

These metrics tell us that our model has high predictive accuracy and can explain about 78% of the variability in wine quality based on the variables we included. The Random Forest model was selected as the 'production' model because it had the highest performance metrics. It also has the advantage of handling a mixture of feature types (numeric and categorical) well, and being robust to outliers and non-linear relationships, making it a reliable choice for our diverse and complex dataset. The Random Forest model also provides feature importance, which can offer valuable insights into which features most strongly predict wine quality.

These models and findings can help stakeholders better understand what influences wine quality and make data-driven decisions to improve their products and services.

## Model Performance and Business Solution

Our production model, the 'Random Forest' model, performed significantly well in predicting the quality of the wine based on the given features. This model can aid our stakeholders, especially wine producers, and sellers, in making informed decisions about which wines to invest in or which attributes to focus on in production. While the model performs well, it's essential to remember that no model is perfect, and it should serve as a guide to support decision-making supplemented by domain expertise.

## Recommendations

Based on our model's performance and our analysis of the data, we have the following recommendations for our stakeholders:

Focus on Value for Money: Given the correlation between price and quality, producers should strive to create wines that provide good value for money. Simultaneously, sellers could invest more in higher-priced wines, which are often associated with higher quality.

Consider the Importance of Body: Since body showed a strong correlation with quality, winemakers should take this into account during production. Sellers should also use this information to guide their purchasing decisions and marketing strategies.

Remember, these recommendations are based on statistical analysis and machine learning models and should be combined with professional judgment and industry knowledge for optimal decision-making.
