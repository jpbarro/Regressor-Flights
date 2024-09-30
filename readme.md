# EXPLORING THE DATA
We performed exploratory data analysis by constructing graphs and analyzing the descriptive statistics of the dataset regarding flight delays.

### Learned:
- Analyze the descriptive statistics of the data;
- Obtain relevant information from the data such as the amount of null data and the typing of the columns;
- Build graphical analysis of data;
- Build a graphical visualization of the data distribution.

# FEATURE ENGINEERING
We perform feature engineering on the flight delay database. Feature engineering is the process of selecting, extracting and transforming variables (also known as features). We created three new columns (date, is_weekend and day_name). Immediately after creating the new columns, we perform feature encoding of the categorical variables and, finally, we clean the data.

### Learned:
- Build new columns;
- Encoding categorical variables;
- Perform correlation analysis;
- Analyze and remove non-relevant columns.

# MODEL SELECTION AND VALIDATION
We trained a dummy model and evaluated it using the MAE, RMSE and R2 metrics. This model was used as a baseline for a more complex machine learning model. Next, we used RandomForestRegressor to overcome the dummy model and, finally, we performed cross-validation to evaluate the model more accurately.

### Learned:
- Build a machine learning model for baseline;
- Evaluate the baseline model according to the RMSE, MAE and R2 metrics;
- Outperform the baseline model with a more complex model (RandomForestRegressor);
- Evaluate RandomForestRegressor graphically and with the metrics RMSE, MAE and R2;
- Perform cross-validation with RandomForestRegressor.

# HYPERPARAMETER OPTIMIZATION
Our focus was on optimizing hyperparameters of the RandomForestRegressor model. We go through feature selection, in which we choose the 13 most important features from the dataset and retrain the model without loss of performance. Afterwards, we performed hyperparameter optimization using the GridSearchCV technique and, finally, saved the optimized model for future use.

### Learned:
- Select the most important features for the model;
- Retrain the model with the most important features without losing performance;
- Perform model hyperparameter optimization using GridSearchCV;
- Save the constructed model.