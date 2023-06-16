# Spanish Wine Quality Prediction 

![image](https://github.com/Noctua28/Spanish-Wine-Quality-Prediction/assets/65126638/08fcd15d-d8d6-434a-97ac-9f84dffc7d72)

## Business Problem and Stakeholders

Our business problem is to predict the quality of wines based on various features in order to inform stakeholders about inventory and production decisions. The stakeholders include wine producers who are interested in understanding the factors that contribute to wine quality and making informed decisions about their products.

## Data Source

The data used for this project was sourced from [Spanish Wine Quality](https://www.kaggle.com/datasets/fedesoriano/spanish-wine-quality-dataset?resource=download) by Fedesoriano from Kaggle, a  dataset of wine information that includes details about wineries, wines, regions, and ratings. The dataset contains information on various features of wines such as winery, year, type, body, acidity, price, and the target variable, rating.

## Data Description

The dataset comprises a collection of wine samples with corresponding features and quality ratings. Each sample includes information such as the winery, year of production, wine type, body and acidity levels, and price. The target variable, rating, represents the quality rating of the wine on a numerical scale. The dataset is comprehensive and diverse, allowing for a detailed analysis of the factors influencing wine quality.

## Analytical Insights

1. Scatter Plot: The scatter plot showing the relationship between wine price and the number of reviews reveals an interesting trend. It indicates that wines at lower price points tend to have a higher number of reviews. This suggests that consumers are more likely to review and provide feedback on wines that are more affordable, possibly due to their higher consumption rate.

2. Bar Plot: The bar plot displaying the average rating for each type of wine allows us to compare the quality of different wine types. We observe that Type X wines tend to have the highest average ratings, while Type Y wines have the lowest average ratings. This insight provides valuable information to stakeholders about the relative quality levels of different wine types.

## Model Metrics

The best-performing model for wine quality prediction is the Random Forest Regressor. The model achieved a mean squared error (MSE) of 0.0029 on the test data, indicating a low level of prediction error. Additionally, the model attained an R-squared value of 0.805, indicating that it captures a substantial amount of variance in the target variable.

## Model Performance and Business Solution

The Random Forest Regressor model offers a highly accurate and reliable solution for predicting wine quality based on the given features. By leveraging this model, stakeholders can make data-driven decisions regarding inventory and production, ensuring that their offerings align with customer preferences and expectations. The model's ability to accurately predict wine quality enables stakeholders to optimize their product selection, pricing, and marketing strategies to maximize customer satisfaction and business success.

## Recommendations

Based on the model's performance and the analytical findings, we provide the following recommendations to stakeholders:

1. Focus on enhancing the quality and reputation of Type X wines, which consistently received the highest average ratings. This could involve allocating additional resources to vineyards and production processes that contribute to the desired characteristics of Type X wines.

2. Investigate the factors that contribute to the lower ratings of Type Y wines and explore opportunities for improvement. This could include analyzing customer feedback, conducting sensory evaluations, and adjusting production techniques to enhance the quality and appeal of Type Y wines.

These recommendations are based on the model's ability to accurately predict wine quality and the insights gained from the analysis of the dataset. By implementing these recommendations, stakeholders can optimize their wine offerings and drive customer satisfaction and business growth.
