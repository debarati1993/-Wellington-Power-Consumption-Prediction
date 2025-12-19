# -Wellington-Power-Consumption-Prediction

## 1. Project Objective

#### The goal of this project is to develop a machine learning model capable of predicting the power consumption (specifically **Zone 1 Power Consumption**) for Wellington, New Zealand. By analyzing various environmental and meteorological factors, the model aims to assist in efficient energy resource management and the optimization of power usage in that zone.

## 2. Dataset Description

#### The dataset consists of **52,583 observations** with the following features:

#### * **Target Variable:** `Zone 1 Power Consumption` (measured in KWR).
#### * **Environmental Features:** * **Temperature:** In Celsius.
#### * **Humidity:** Relative humidity (grams of water vapor per cubic meter).
#### * **Wind Speed:** Measured in nautical miles per hour.
#### * **General Diffuse Flows & Diffuse Flows:** Measures of solar radiation intensity.
#### * **Air Quality Index (PM):** Particles in micrograms per cubic meter.
#### * **Cloudiness:** Binary indicator (1-Yes, 0-No).



## 3. Technology Stack

#### * **Language:** Python
#### * **Libraries:** * **Data Analysis:** `pandas`, `numpy`, `scipy`, `statsmodels`.
#### * **Visualization:** `matplotlib`, `seaborn`.
#### * **Machine Learning:** `scikit-learn` (StandardScaler, LabelEncoder, MinMaxScaler, train_test_split), `xgboost`.



## 4. Key Methodology

#### 1. **Data Cleaning:** * Handled data type inconsistencies (converting quantitative 'Temperature' and 'Humidity' from object to numeric).
#### * Addressed missing values across several meteorological features.
#### 2. **Preprocessing:** * Feature scaling using `StandardScaler` and `MinMaxScaler`.
#### * Splitting data into training and testing sets.
#### 3. **Modeling:** * Implementation of various regression algorithms, including **Linear Regression**, **Random Forest Regressor**, and **XGBRegressor**.
#### * Hyperparameter tuning using **GridSearchCV**.
#### 4. **Evaluation:** * Performance was measured using metrics such as **R-squared (R2)**, **Mean Squared Error (MSE)**, and **Mean Absolute Error (MAE)**.

