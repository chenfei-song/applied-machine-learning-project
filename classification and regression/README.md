This is an implementation of classification and regression models in machine learning.

## Classification

### Overview

data source: https://www.openml.org/d/31

data description: This German Credit dataset classifies people described by a set of attributes as good or bad credit risks.

attributes:

- Status of existing checking account, in Deutsche Mark.  
- Duration in months
- Credit history (credits taken, paid back duly, delays, critical accounts) 
- Purpose of the credit (car, television,...) 
- Credit amount 
- Status of savings account/bonds, in Deutsche Mark. 
- Present employment, in number of years. 
- Installment rate in percentage of disposable income 
- Personal status (married, single,...) and sex  
- Other debtors / guarantors  
- Present residence since X years 
- Property (e.g. real estate)  
- Age in years  14. Other installment plans (banks, stores)  
- Housing (rent, own,...)  
- Number of existing credits at this bank  
- Job  
- Number of people being liable to provide maintenance for 
- Telephone (yes,no)  
- Foreign worker (yes,no) 

### Modeling Summary
- Preprocessing with pipelines
- Tune the parameters using GridSearchCV
- Compare performance of Logistic Regression, linear support vector machines and nearest neighbors

## Regression

### Overview

data source: https://www.kaggle.com/shree1992/housedata

data description: This Sydney housing dataset is used for predicting property prices with a set of attributes.

Attributes:

- date
- price
- bedrooms
- bathrooms
- sqft_living
- sqft_lot
- floors
- waterfront
- view
- condition
- sqft_above
- sqft_basement
- yr_built
- yr_renovated
- street
- city
- statezip
- country

### Modeling Summary

- Preprocessing with pipelines
- Tune the parameters using GridSearchCV
- Evaluate Linear Regression (OLS), Ridge, Lasso and ElasticNet models

