# Video Game Sales Analysis

## Introduction

This repository contains an in-depth analysis of video game sales data, aimed at forecasting global sales performance and categorizing games based on various descriptive factors. The dataset offers comprehensive information on video game titles, release years, platforms, genres, publishers, sales in different regions, as well as ratings from critics and users. This analysis provides valuable insights for market researchers, industry professionals, and gamers interested in understanding trends in the international video game market.

## Data Exploration and Modeling Method

### Exploratory Data Analysis (EDA)

The dataset underwent rigorous EDA to understand its structure and characteristics. Missing values were addressed, outliers were treated, and categorical variables were encoded. This ensured the dataset was appropriately prepared for modeling.

### Modeling Methods

Various regression algorithms, including Lasso, Ridge, Gradient Boosting, Random Forest, Support Vector, K-Nearest Neighbors, and Linear Regression, were employed to predict global sales performance. Classification models, particularly the Random Forest classifier, were utilized to categorize games based on rating, platform, and genre. Additionally, clustering analysis was performed using rating and genre as categorical variables to identify meaningful groups within the dataset.

### Model evaluation 
For the regression model 

-  mean absolute error (MAE)
-  mean square error (MSE)
-  root mean square error (RMSE)
-  R2 & adjusted R2
-  mean absolute percentage error (MAPE)

For the classification model 
 - Accuracy
 - Prescision
 - Recall
 - F1 Score
   
## Usage

To reproduce the analysis, ensure you have the following libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn (for data balancing)
- Additional libraries may be required depending on specific modeling techniques used.

### How to Run

1. Clone this repository to your local machine.
2. Install the necessary libraries using `pip install -r requirements.txt`.
3. Open the Jupyter Notebook file `Video_Game_Sales_Analysis.ipynb` in a Jupyter environment.
4. Follow the step-by-step instructions within the notebook to explore the data, perform analysis, and replicate the results.

## Comments

Feel free to add comments or suggestions directly within the Jupyter Notebook file. Your feedback is valuable for improving the analysis and enhancing its reproducibility.

## Conclusion

This analysis provides valuable insights into the global video game market, offering predictions on sales performance and categorizing games based on various factors. By following the provided instructions, you can reproduce the analysis and further explore the dataset. Your contributions and feedback are welcome to enhance the robustness and applicability of this analysis.

