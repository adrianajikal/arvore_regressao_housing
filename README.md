# California Housing Price Analysis

This repository contains a series of exercises focused on analyzing and predicting housing prices in California using the `California Housing Dataset`. The project involves exploring the data, training decision tree models, evaluating model performance, and visualizing the results.

## Dataset

The dataset contains various features related to housing in California, including:

- `longitude`: Longitude of the house location.
- `latitude`: Latitude of the house location.
- `housing_median_age`: Median age of the houses.
- `total_rooms`: Total number of rooms in the houses.
- `total_bedrooms`: Total number of bedrooms in the houses.
- `population`: Population in the area.
- `households`: Number of households in the area.
- `median_income`: Median income of the households.
- `median_house_value`: Median value of the houses (target variable).

## Project Structure

- **Data Exploration:** Initial exploration of the dataset to understand the distributions, correlations, and potential issues such as missing values.
- **Data Preparation:** Preprocessing steps including handling missing values, feature scaling, and data splitting into training and testing sets.
- **Modeling:**
  - **Decision Tree Model:** Implemented a Decision Tree model with different depths to predict `median_house_value`.
  - **Model Evaluation:** Evaluated the model performance using Mean Squared Error (MSE) on both training and testing datasets.
  - **Model Interpretation:** Visualized the decision tree structure and discussed the importance of features based on their usage in the tree.

## Key Findings

- **Model Performance:**
  - Depth 8 Tree:
    - Training MSE: 3,304,134,293.99
    - Testing MSE: 4,217,261,963.92
  - Depth 2 Tree:
    - Training MSE: 7,330,289,644.64
    - Testing MSE: 7,499,488,454.95

  The deeper tree performed better on the training data but showed signs of overfitting when tested on unseen data.

- **Feature Importance:**
  - A more detailed analysis of feature importance is planned, focusing on which features contribute most to the model's decisions.

## Visualization

- **Decision Tree:** A detailed visualization of the decision tree with depth 8 has been generated to analyze the structure and decisions made by the model.

