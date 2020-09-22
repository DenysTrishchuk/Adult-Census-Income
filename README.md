# Adult Census Income
The prediction task is to determine whether a person makes over $50K a year. [Dataset](https://archive.ics.uci.edu/ml/datasets/adult)  
My [Jupyter Notebook](https://github.com/DenysTrishchuk/Adult-Census-Income/blob/master/adult_census_income.ipynb)

## Content

1. Definition Problem
2. Importing Libraries
3. Data Collection
4. Data Overview
5. Data Cleaning
6. Exploratory Data Analysis
7. Feature Engineering
8. Data Modeling
9. Result

## Result

| Model                | Accuracy | CV accuracy |
|:-------------------- |:--------:|:-----------:|
| SGD Lasso       	   | 0.837328 |   0.816271  |
| Ridge                | 0.835587 |   0.823524  |
| SGD Ridge            | 0.845523 |   0.805607  | 
| Logistic Regression  | 0.849211 |   0.823432  |
| SVM Linear           | 0.848084 |   0.822172  |
| SVM Polynomial       | 0.848699 |   0.823124  |
| K-Nearest Neighbors  | 0.845421 |   0.827243  |
| Decision Tree    	   | 0.851158 |   0.821065  |
| Random Forest   	   | 0.858226 |   0.827243  |
| XGBoost     	       | 0.862835 |   0.828933  | 
| XGBoost tuned	       | 0.869289 |   0.872579  |
