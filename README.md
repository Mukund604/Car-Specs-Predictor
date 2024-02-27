# European Car Dataset Analysis

## Overview
This repository contains code for analyzing a European car dataset. The analysis involves preprocessing the data, transforming features, and building a predictive model to estimate various car attributes based on engine displacement.

## Preprocessing
- Missing values are dropped from the dataset.
- Invalid values in the 'Acceleration (s)' column are filtered out.
- Standardization of fuel types and body types is performed.
- Data types are adjusted, and date columns are converted to datetime.

## Feature Engineering
- New columns, such as 'Selling Period,' are created.
- String columns like 'Brand' and 'Body type' are converted into numeric using Label Encoding.

## Data Filtering
The dataset is filtered to include specific columns (`'Displacement (ccm)', 'Length (mm)', 'Width (mm)', 'Height (mm)', 'Acceleration (s)', 'Top speed (km/h)', 'Power (HP)', 'Body type'`) for prediction.

## Model Building
A Multi-Output KNeighborsRegressor model is trained to predict various car attributes based on engine displacement. The dataset is split into training and testing sets.

## Prediction
A specific displacement value (e.g., 2200 cc) is used to make predictions using the trained model. The predicted values include length, width, height, acceleration, top speed, power, and body type.

## Usage
1. Clone the repository: `git clone https://github.com/your_username/European_Car_Dataset.git`
2. Install dependencies: `pip install -r requirements.txt` (if any)
3. Run the notebook or script for your analysis.

