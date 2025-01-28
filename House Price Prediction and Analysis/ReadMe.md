# House Price Analysis and Prediction Project

This project integrates **Machine Learning (ML)** and **Tableau** to analyze house price data, predict prices, and provide actionable insights through interactive visualizations. The analysis focuses on key features influencing house prices, model performance, and patterns in the data, enabling data-driven decision-making.

---

## Business Overview
The objective of this project is to accurately predict house prices while identifying the most influential factors. The dataset includes detailed information about house transactions, including proximity to MRT stations, house age, and neighborhood features.

### Objectives:
- Provide insights into house price distribution and key influencing factors.
- Build predictive models to forecast house prices.
- Evaluate model performance and residuals.
- Present findings interactively using Tableau.

The results support data-driven strategies for pricing, investment, and urban planning.

---

## Project Overview
### Key Deliverables:
1. **Machine Learning workflow** to train predictive models.
2. **Feature Importance analysis** to identify key drivers of house prices.
3. Interactive **Tableau dashboards** to visualize model outputs and data insights.

### Links:
- **Tableau Dashboard**: [House Price Analysis and Model Insights](https://public.tableau.com/views/HousePriceAnalysisandModelInsights/HousePriceAnalysisandModelInsights?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
- **Dataset**: [Real Estate Price Prediction Dataset on Kaggle](https://www.kaggle.com/datasets/quantbruce/real-estate-price-prediction?select=Real+estate.csv)

---

## Files in the Repository
- **Data Folder**:
  - **Real Estate.csv**: Raw dataset used for analysis.
  - **Feature_Importances.csv**: Highlights the importance of each feature in predicting house prices.
  - **Predictions.csv**: Contains actual vs. predicted house prices and residuals.
  - **Processed_Real_Estate.csv**: Cleaned and preprocessed dataset used for analysis.

- **Tableau Workbook (.twbx)**: Contains all visualizations and the dashboard.
- **Python Scripts**: Code used for data preprocessing, ML modeling, and evaluation.
- **Processed Data Visualization.pdf**: A document containing key charts from Tableau.


---

## Machine Learning Workflow
### 1. Data Preprocessing:
- Cleaned and transformed data for analysis, removing outliers and creating distance categories.
- Converted dates and extracted transaction years for trend analysis.

### 2. Model Training:
- Trained multiple ML models:
  - **Random Forest Regressor**: Captures non-linear relationships.
  - **Gradient Boosting Regressor**: Sequentially improves prediction accuracy.
  - **XGBoost Regressor**: Optimized Gradient Boosting with faster performance.
- Evaluated models using:
  - **Mean Absolute Error (MAE)**: Measures average prediction error.
  - **Root Mean Squared Error (RMSE)**: Penalizes larger errors.

### 3. Feature Importance Analysis:
- Identified the most influential factors for house prices, with **Distance to MRT** as the most critical feature.

### 4. Residual Analysis:
- Calculated residuals (Actual - Predicted) to assess model accuracy and identify under/over-predictions.

---

## Visualizations

### 1. **House Price Distribution**
- **Chart Type**: Histogram
- **Insight**: Displays the frequency distribution of house prices (`Price per Unit Area`).

### 2. **Price vs. Distance Categories**
- **Chart Type**: Heatmap
- **Insight**: Shows how house prices vary by proximity to MRT stations, with color representing average price.

### 3. **Price vs. House Age**
- **Chart Type**: Scatter Plot
- **Insight**: Explores the relationship between `House Age` and `Price per Unit Area`, segmented by `Distance_Category`.

### 4. **Actual vs. Predicted House Prices**
- **Chart Type**: Scatter Plot with Residuals
- **Insight**: Compares actual and predicted prices, with residuals as a color gradient.

### 5. **Feature Importance**
- **Chart Type**: Bar Chart
- **Insight**: Ranks the most influential features for predicting house prices, with `Distance to MRT` being the top predictor.

---

## Dashboard
The **Tableau Dashboard** consolidates all visualizations into a single interactive interface, allowing users to:
- Filter by `Distance Category`, `House Age`, or `Price per Unit Area`.
- Explore trends and patterns dynamically.
- Understand model accuracy and key factors driving house prices.

---

## Process
### Data Preparation:
- Processed the dataset to clean and remove outliers.
- Created categorical bins for distance and converted dates to usable formats.

### Model Development:
- Trained Random Forest, Gradient Boosting, and XGBoost models to predict house prices.
- Saved predictions and feature importances for visualization.

### Visualization:
- Designed and arranged visuals in Tableau to provide a cohesive narrative.
- Added filters and annotations to enhance interactivity and insights.

---

## Insights and Recommendations
- **Key Influencer**: `Distance_to_MRT` is the most critical feature, suggesting proximity to public transport significantly impacts house prices.
- **Model Performance**: The models provided accurate predictions, with Gradient Boosting performing the best based on MAE and RMSE.
- **Outliers**: High residuals in the scatter plot highlight areas where the model under/overpredicted, which could indicate unique market conditions.

---

## Conclusion
This project demonstrates the integration of Machine Learning with Tableau to provide actionable insights into house prices. The dashboard allows stakeholders to interact with the data and understand key factors driving prices, supporting better decision-making for pricing strategies, investments, and urban planning.

---

Feel free to explore the [Tableau Dashboard](https://public.tableau.com/views/HousePriceAnalysisandModelInsights/HousePriceAnalysisandModelInsights?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) for more details or download the [Dataset on Kaggle](https://www.kaggle.com/datasets/quantbruce/real-estate-price-prediction?select=Real+estate.csv).
