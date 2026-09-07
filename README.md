# ISRO Satellite Lifetime Prediction using Machine Learning

## Project Overview

This project uses Machine Learning to predict the expected lifetime of satellites based on their orbital and physical parameters.

## Objective

To develop a regression model that predicts the expected lifetime of a satellite using parameters such as:

- Perigee
- Apogee
- Eccentricity
- Inclination
- Orbital Period
- Launch Mass

## Machine Learning Models

The project compares different regression algorithms:

- Linear Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- Extra Trees

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook
- Joblib

## Project Files

- `ISRO_Satellite_Lifetime_Prediction.ipynb` – Model development and analysis
- `ISRO Satellite Dataset.csv` – Dataset
- `satellite_lifetime_model.pkl` – Trained Machine Learning model
- `requirements.txt` – Required Python libraries
- `README.md` – Project documentation

## Initial Result

The initial Random Forest model achieved:

- MAE: 1.87 years
- RMSE: 2.60 years
- R² Score: 0.498

Further model comparison and cross-validation will be performed to select the best model.

## Future Work

- Improve model accuracy
- Perform hyperparameter tuning
- Increase dataset size
- Deploy the model as a web application
