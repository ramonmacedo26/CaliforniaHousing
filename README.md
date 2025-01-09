# CaliforniaHousing

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

