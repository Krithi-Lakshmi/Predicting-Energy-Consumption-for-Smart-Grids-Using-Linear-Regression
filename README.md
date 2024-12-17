# Predicting-Energy-Consumption-for-Smart-Grids
predicting energy consumption using a linear regression model. 

Linear regression predicts energy consumption using a formula: 
𝑦=𝛽0+𝛽1𝑥1+𝛽2𝑥2+…+𝛽𝑛𝑥𝑛

​y: Predicted energy consumption.

𝑥𝑖 : Features like temperature, time, or appliance usage.

𝛽𝑖 : Model coefficients representing the weight of each feature.

β0 : Intercept term (baseline consumption).


**Step 1: Importing Libraries:**
Necessary Python libraries are imported, including pandas, numpy, matplotlib, and seaborn for data analysis and visualization, along with sklearn modules for model building and evaluation.

**Step 2: Loading Dataset:**
The dataset is loaded using pandas. The file appears to be an Excel sheet named ENB2012_data.xlsx.

**Step 3: Data Preprocessing:**
This likely includes steps like handling missing values, scaling features (using StandardScaler), and preparing the data for model training.

**Step 4: Model Training:**
The LinearRegression model from sklearn is used to fit the training data.

**Step 5: Model Evaluation:**
Metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared are calculated to evaluate the model's performance.

**Step 6: Predictions:**
The trained model is applied to new data to predict energy consumption.
