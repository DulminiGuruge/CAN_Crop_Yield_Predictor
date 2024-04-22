
###  Canada Crop Yield Prediction based on GIS data

1. **Data Acquisition:**
   - The code starts by reading several CSV files containing weather data, crop yield data, and station information.
   - It then combines these datasets into a single DataFrame for further analysis.

2. **Data Cleaning:**
   - The code identifies and removes rows with missing or invalid values in the yield column.
   - It also removes rows where the yield value is -999.0, which is considered an invalid value.

3. **Data Preprocessing:**
   - The code encodes categorical variables using LabelEncoder to convert them into numerical values suitable for machine learning algorithms.
   - It then performs exploratory data analysis (EDA) to understand the relationships between different variables and identify potential features for prediction.

4. **Model Training and Evaluation:**
   - The code trains and evaluates various machine learning models for predicting crop yield, including Linear Regression, Decision Tree, Random Forest, Gradient Boosting, XGBoost, Bagging Regressor, and KNN.
   - It calculates various performance metrics such as accuracy, mean squared error (MSE), mean absolute error (MAE), mean absolute percentage error (MAPE), and R-squared score for each model.
   - The results are presented in a tabular format, highlighting the best and worst performing models based on different metrics.

5. **K-Fold Cross Validation:**
   - The code performs K-fold cross-validation for each model to assess their performance and stability across different folds.
   - The results are presented as a table and visualized using line charts for each model.

6. **Final Comparison and Conclusion:**
   - The code compares the performance of all the models based on various metrics and highlights the best-performing model for predicting crop yield.
   - It also provides insights into the importance of data cleaning, feature engineering, and model selection for achieving accurate predictions.

Overall, the code demonstrates a comprehensive approach to analyzing crop yield data, building machine learning models, and evaluating their performance for predicting crop yield based on weather and geographical factors.