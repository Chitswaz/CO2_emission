# Linear vs Polynomial Regression Analysis

## Overview
This project explores the relationship between engine size and CO2 emissions using linear regression. The dataset is sourced from the IBM Developer Skills Network and includes various vehicle characteristics and their corresponding CO2 emissions.

## Dataset
The dataset `FuelConsumption.csv` contains the following columns:
- **MODELYEAR**
- **MAKE**
- **MODEL**
- **VEHICLECLASS**
- **ENGINESIZE**
- **CYLINDERS**
- **TRANSMISSION**
- **FUELTYPE**
- **FUELCONSUMPTION_CITY**
- **FUELCONSUMPTION_HWY**
- **FUELCONSUMPTION_COMB**
- **FUELCONSUMPTION_COMB_MPG**
- **CO2EMISSIONS**

## Methodology
The analysis involves splitting the data into training and testing sets, converting variables into tensors, and initializing weights and bias for the linear regression model. The model is trained over 200 epochs with an exponential decay learning rate.

## Results
The final Mean Squared Error (MSE) on the test set is **1517.6134**. The final weights and bias of the model are **54.730255** and **64.72835**, respectively.

## Visualization
The loss function over epochs is plotted to visualize the training process. Additionally, a scatter plot of the training data with the regression line is provided to illustrate the model's fit.

## Requirements
- TensorFlow
- Matplotlib
- Pandas
- NumPy
- scikit-learn

## Usage
To run this analysis, ensure you have the above requirements installed, then execute the Jupyter notebook `linvspoly.ipynb`.

## License
This project is open-sourced under the MIT license. Feel free to use and modify the code as per your needs.

## Acknowledgments
Special thanks to the IBM Developer Skills Network for providing the dataset used in this analysis.
