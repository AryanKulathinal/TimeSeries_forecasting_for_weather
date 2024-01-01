# TimeSeries_forecasting_for_weather
The repository contains the implementation details for a time series forecasting model predicting temperatures in Chicago City using Facebook's Prophet machine learning model.

## Overview

The colab Notebook, "Weather_prediction.ipynb," presents a time series forecasting project for predicting temperatures in Chicago City. The implementation utilizes the Facebook Prophet machine learning model. The notebook is generated on Colaboratory and is given in the repository.

## Steps in the Project

### 1. Installing Required Libraries
   The notebook starts by installing necessary libraries, including `pystan` and `prophet`.

### 2. Importing Libraries
   Relevant libraries, such as `pandas` for data manipulation and `Prophet` for time series forecasting, are imported.

### 3. Reading the Dataset
   The project involves the use of a dataset obtained from Kaggle, describing the weather in Chicago. The notebook reads the dataset using pandas.

### 4. Preprocessing the Dataset
   - Combining the year, month, and day fields into a single date field for better analysis.
   - Dropping unwanted columns to simplify the dataset.

### 5. Model Training
   Utilizing the Prophet model, the notebook trains the model on the preprocessed dataset.

### 6. Forecasting
   The model is then used to make future predictions, providing insights into temperature trends.

### 7. Plotting and Visualization
   The notebook includes visualizations of the forecasted data, both overall trends and specific components.

### 8. Result Analysis
   The project concludes by analyzing and displaying the predicted temperature for a specific date, such as '2024-01-01.'

## Additional Information

- **Dataset Source:**
  The dataset used in this project is sourced from Kaggle and provides detailed information about the weather in Chicago.

- **Notebook on Colaboratory:**
  The notebook is generated on Colaboratory, enabling easy access and collaboration. The original notebook is provided for reference.



