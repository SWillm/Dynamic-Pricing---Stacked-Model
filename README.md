# Dynamic-Pricing---Stacked-Model
This project focuses on developing a dynamic pricing model using a stacked ensemble approach.
The goal is to predict optimal prices that maximize revenue and profitability by analyzing various features that influence pricing decisions.

Dataset
The analysis utilizes the Dynamic Pricing Dataset, which includes features such as product attributes, market conditions, and historical sales data. This dataset is publicly available on Kaggle:

Dynamic Pricing Dataset

Note: The dataset is not included in this repository. To run the notebook, please download the dataset from Kaggle and place it in the appropriate directory as specified in the notebook.

Methodology
The project employs a stacked ensemble model, combining multiple base learners to improve predictive performance. The workflow includes:

Data Preprocessing:

Handling missing values and outliers.
Feature engineering to create relevant predictors.
Model Development:

Training base models such as Linear Regression, Decision Trees, and Gradient Boosting.
Combining base models using a meta-learner to form the stacked ensemble.
Evaluation:

Assessing model performance using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
Cross-validation to ensure robustness.
Results
The stacked model demonstrates improved accuracy in predicting optimal prices compared to individual base models. Key findings include:

Enhanced predictive performance with reduced error margins.
Insights into the significance of various features affecting pricing.
