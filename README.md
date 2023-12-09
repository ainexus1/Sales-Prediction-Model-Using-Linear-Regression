# Advanced Project Overview: Sales Prediction Using Linear Regression

**Description:**
This project employs Linear Regression to forecast monthly customer sales based on historical data. The dataset includes timestamped sales records, converted to monthly totals. Predictions are made by analyzing sales differentials and incorporating twelve months' lagged features.

**Key Steps:**
1. **Data Preprocessing:**
   - Date conversion: Timestamps transformed to datetime and then to monthly periods.
   - Monthly aggregation: Summing item counts for each month.
   - Differencing: Calculating sales differentials for time series analysis.

2. **Supervised Learning:**
   - Feature engineering: Creating lagged features to capture historical patterns.
   - Data scaling: MinMaxScaler utilized for feature scaling.
   - Train-test split: Datasets prepared for model training and testing.

3. **Linear Regression Modeling:**
   - Model creation: A Linear Regression model is employed for sales predictions.
   - Training: Fit the model using training data with lagged features.
   - Prediction: Forecast sales for the test set and inverse transform for meaningful results.

4. **Evaluation Metrics:**
   - Mean Squared Error (MSE): Measure of prediction accuracy.
   - Mean Absolute Error (MAE): Assessment of forecast errors.
   - R-squared (R2): Indicator of model goodness-of-fit.

5. **Results and Visualization:**
   - Comparative plot: Visualizing actual vs. predicted sales.
   - Metrics analysis: Interpreting MSE, MAE, and R2 to evaluate model performance.

**GitHub Repository:**
- [Sales Prediction Model](https://github.com/ainexus1/Sales-Prediction-Model-Using-Linear-Regression/blob/main/Sales%20Prediction.ipynb)

**Note:** Detailed project insights, analysis, and further improvements can be found in the Jupyter Notebook within the provided GitHub repository.
