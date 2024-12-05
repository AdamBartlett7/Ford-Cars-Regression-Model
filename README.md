# Ford-Cars-Regression-Model
Overview - 
This project is centred around a dataset of used Ford cars. It includes: 
- The cleaning of the dataset
- Data analysis accompanied by visualisations
- Linear regression model predicting car prices

Features
- The initial EDA 
- Handling outliers
- Data analysis of different car features
- Visualisations to understand the trends in data better
- Data preprocessing for machine learning model
- Feature selection
- Training multiple models
- Evaluating and comparing each model using several different metrics
- Checking assumptions for the best model
- Making predictions

Installation
- Clone the repostiory using:
  - git clone https://github.com/AdamBartlett7/Ford-Cars-Regression-Model.git
  - cd Ford-Cars-Regression-Model
- To install the necessary python libraries
   - pip install -r requirements.txt

Usage
- Run Ford_dataset_cleaning.ipynb to see the initial dataset and how it was cleaned.
- Run Ford_dataset_vis.ipynb to see the data analysis and visualisations.
- Run Ford_dataset_linear_reg.ipynb to see the linear regression models in action.
- All files can be run seperately as the cleaned dataset was saved and then used at the start for the analysis and model.

Dataset
- The dataset include information on various used Ford car models with attributes such as Model, Production year, price, 
  transmission, mileage, fuel type, tax, mpg and engine size.
- The dataset was sourced from - https://www.kaggle.com/datasets/adhurimquku/ford-car-price-prediction

Results
- Some key insights from the linear regression models were that the features which most postively impacted the car price 
  were production year and engine size. While the features which negatively impacted price were mileage and mpg.
- Out of the three models contructed the first model which included all the features performed the best.
- With these scores on the testing set
   - R-squared : 0.855
   - MAE : 1211.641
   - MSE : 2405999.398
   - RMSE : 1551.128

License
- This project is licensed under the MIT License. See the LICENSE file for details.




