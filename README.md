# Spanish Wine Quality Prediction 

![image](https://github.com/Noctua28/Spanish-Wine-Quality-Prediction/assets/65126638/08fcd15d-d8d6-434a-97ac-9f84dffc7d72)

## Business Problem and Stakeholders

Our business problem is to predict the quality of wines based on various features in order to inform stakeholders about inventory and production decisions. The stakeholders include wine producers who are interested in understanding the factors that contribute to wine quality and making informed decisions about their products.

## Data Source

The data used for this project was sourced from [Spanish Wine Quality](https://www.kaggle.com/datasets/fedesoriano/spanish-wine-quality-dataset?resource=download) by Fedesoriano from Kaggle, a  dataset of wine information that includes details about wineries, wines, regions, and ratings. The dataset contains information on various features of wines such as winery, year, type, body, acidity, price, and the target variable, rating.

## Data Description

The dataset comprises a collection of wine samples with corresponding features and quality ratings. Each sample includes information such as the winery, year of production, wine type, body and acidity levels, and price. The target variable, rating, represents the quality rating of the wine on a numerical scale. The dataset is comprehensive and diverse, allowing for a detailed analysis of the factors influencing wine quality.

## Analytical Insights

1. Scatter Plot:

![image](https://github.com/Noctua28/Spanish-Wine-Quality-Prediction/assets/65126638/cbeced02-8c38-4cd0-87aa-e84f45c98f7a)

The scatter plot is displaying the relationship between the price of each wine and the number of reviews it has received. Each dot on the plot represents an individual wine in our dataset.

Looking at the plot, it seems that wines that are less expensive, or at lower price points, tend to have more reviews. This could be for a number of reasons. One possible explanation is that more affordable wines are more accessible to a larger number of people, and therefore are likely to be purchased and reviewed more often.

Additionally, wines with a large number of reviews are likely popular, either due to their quality, their price point, or a combination of both. This popularity could drive further sales and reviews, creating a feedback loop that results in these wines having a significant number of reviews.

Conversely, wines at higher price points seem to have fewer reviews. This may be due to them being less accessible due to their cost, resulting in fewer purchases and, subsequently, fewer reviews.

However, it's important to remember that this is a broad trend, and there will be exceptions. For example, a high-priced wine could be extremely popular and have many reviews, or a low-priced wine might be less popular and have fewer reviews. Additionally, the quality of reviews (reflected in the rating) isn't accounted for in this plot - a wine with many reviews might have a low average rating, or a wine with few reviews might have a high average rating.

2. Bar Plot:

![image](https://github.com/Noctua28/Spanish-Wine-Quality-Prediction/assets/65126638/7c20e355-2a0f-4efd-a00f-3ee18e3233cf)

The bar plot visualizes the average rating for each type of wine. Each bar in the plot represents a different type of wine, and the height of the bar corresponds to the average rating of that wine type.

This plot simplifies the complex world of wines into broad categories. Many other factors like the winery, region, price, and individual preferences play a massive role in a wine's rating and aren't considered in this visualization.

## Model Metrics

The best-performing model for wine quality prediction is the Random Forest Regressor. The model achieved a mean squared error (MSE) of 0.0029 on the test data, indicating a low level of prediction error. Additionally, the model attained an R-squared value of 0.805, indicating that it captures a substantial amount of variance in the target variable.

## Model Performance and Business Solution

The Random Forest Regressor model offers a highly accurate and reliable solution for predicting wine quality based on the given features. By leveraging this model, stakeholders can make data-driven decisions regarding inventory and production, ensuring that their offerings align with customer preferences and expectations. The model's ability to accurately predict wine quality enables stakeholders to optimize their product selection, pricing, and marketing strategies to maximize customer satisfaction and business success.

## Recommendations

Based on the model's performance and the analytical findings, we provide the following recommendations to stakeholders:

1. Focus on enhancing the quality and reputation of red wines, which consistently received the highest average ratings. This could involve allocating additional resources to vineyards and production processes that contribute to the desired characteristics of red wines.

2. Investigate the factors that contribute to the lower ratings of white and wines in the other category and explore opportunities for improvement. This could include analyzing customer feedback, conducting sensory evaluations, and adjusting production techniques to enhance the quality and appeal.

These recommendations are based on the model's ability to accurately predict wine quality and the insights gained from the analysis of the dataset. By implementing these recommendations, stakeholders can optimize their wine offerings and drive customer satisfaction and business growth.
