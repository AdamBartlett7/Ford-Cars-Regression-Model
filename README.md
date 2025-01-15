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
- Navigate to the correct directory using:
  - cd Ford-Cars-Regression-Model
- To create your own virtual environment with the necessary python libraries use:
   - conda env create -f environment.yml
- Open any code editor and run the files.

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
- From the data analysis and visualisations I found out that Mustangs are the most expensive model on average while Fiestas have the best MPG.
- Also as expected the average price gradually increased with the newer production year. Cars produced in 2010 had and average price of $5000.
  While the most recent cars produced in 2020 had an average price of $19,000. 
- However the same gradual increase was not seen in average MPG. The highest average MPG was in 2015 and 2016 with 61MPG.
  After 2016 the average dropped back down into the 50s.
- Some other findings were seeing the spread of mileage for petrol and diesel cars. Diesel cars had a much larger range and higher 50th and 75th percentile values.
- Also I looked into the spread of price for each type of transmission and found that automatic cars had the higher 25th, 50th and 75th values followed by semi-automatics.

- Some key insights from the linear regression models were that the features which most postively impacted (increased) the car price 
  were production year and engine size. While the features which negatively impacted (decreased) the price were mileage and mpg.
- Out of the three models contructed the first model which included all the features performed the best.
- With these scores on the testing set
   - R-squared : 0.855
   - MAE : 1211.641
   - MSE : 2405999.398
   - RMSE : 1551.128

License
- This project is licensed under the MIT License. See the LICENSE file for details.




