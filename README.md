# Airbnb-Price-Prediction-Data-Driven--Machine-Learning
To create an accurate model that predicts Airbnb listing prices based on multiple features, enabling hosts to set competitive and data-driven prices.
Project Objective
To build an accurate regression model that predicts Airbnb listing prices and analyzes the impact of different features like location, room type, and property type on pricing.

Data Preprocessing
Data Cleaning: Handled missing values and removed inconsistencies.

Feature Engineering: Created meaningful features such as price per night, host response rate, etc.

Outlier Treatment: Identified and treated extreme values in price and numerical columns.

Train-Test Split: Divided the dataset for unbiased model evaluation.

Exploratory Data Analysis
Explored the dataset to understand distribution and correlations.

Key findings include:

Listings in central locations tend to be more expensive.

Entire home/apartment listings are generally priced higher than shared or private rooms.

Property type and number of reviews moderately influence price.

Used heatmaps, scatter plots, and box plots to visualize patterns and relationships.

Model Development
Algorithm: XGBoost Regressor

Reason for Choosing XGBoost: It is fast, handles non-linear relationships well, and is robust to outliers.

Hyperparameter Tuning: Performed using Grid Search and Cross-Validation.

Evaluation Metrics: Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-squared score.

Results and Insights
The model showed good accuracy on the test set.

Location, room type, and property type were among the most influential features.

The model provides helpful insights for optimizing Airbnb pricing strategies.

Project Structure
Airbnb_Price_Prediction_XGBoost.ipynb: Main notebook with code and analysis

data/: Contains the Airbnb listings dataset

visuals/: Contains visualizations such as heatmaps and scatter plots

README.md: Project documentation

Tools and Technologies
Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

XGBoost

Jupyter Notebook
