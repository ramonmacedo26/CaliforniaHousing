# CaliforniaHousing
Housing Prices Prediction Using Decision Trees
Overview
This project focuses on predicting housing prices using a Decision Tree Regressor. By analyzing a housing dataset, we explore the relationships between key housing attributes (e.g., median income, total rooms, and households) and the median house value. The project leverages feature engineering, data visualization, and machine learning to deliver insights and build predictive models.

Key Features
Exploratory Data Analysis (EDA):

Understand data distribution, relationships, and correlations among attributes.
Visualizations include scatter plots, histograms, and correlation heatmaps.
Feature Engineering:

New attributes like rooms_per_household, bedrooms_per_room, and population_per_household are created to capture housing density and patterns.
Modeling with Decision Trees:

A Decision Tree Regressor is used to predict housing prices.
The model is evaluated using metrics like:
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
Mean Absolute Error (MAE)
R² (R-squared)
Hyperparameter Tuning:

The model is optimized using GridSearchCV to find the best hyperparameters (max_depth, min_samples_split, etc.).
Regularization techniques are employed to reduce overfitting and improve generalization.
Results
The final optimized Decision Tree model explains:
82.4% of the variance in the training set (R²).
69.9% of the variance in the test set (R²).
Prediction errors are within a reasonable range:
MAE: ~$33,066 for training, ~$42,747 for testing.
This indicates the model performs well but could benefit from further improvement.
How to Use
Clone the Repository:

bash
Copiar código
git clone https://github.com/yourusername/housing-price-prediction.git
cd housing-price-prediction
Install Dependencies:

bash
Copiar código
pip install -r requirements.txt
Run the Jupyter Notebook:

Open the notebook to explore data, train models, and evaluate predictions.
Modify Parameters:

Update hyperparameters in the GridSearch section to test additional configurations.
Future Improvements
Incorporate ensemble methods like Random Forests or Gradient Boosting for better accuracy and generalization.
Add feature selection to reduce dimensionality and improve performance.
Extend the analysis to include geospatial visualizations for better insights into geographical patterns.
Dataset
The dataset used in this project includes housing attributes like:
median_house_value (target variable), median_income, total_rooms, households, etc.
Ensure the dataset is placed in the appropriate folder before running the notebook.
Contribution
Feel free to fork the repository and contribute:

Add new features or algorithms.
Improve documentation and code efficiency.
