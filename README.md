# Predicting Income
### David Cortes, Zach Brown, Albert Frantz

## Project Goal

Build a model that optimizes for accuracy to predict if a person’s income is greater than or less than $50,000, limited to 20 total features.

## Data Cleaning

* Imputed the mode for missing values (about 2500 in total)
* Used polynomial features to engineer new features with relationships to income
* Chose most highly correlated terms, dropping terms that were collinear. 

## Modeling

The baseline model had an accuracy score of 76% that we attempted to beat.

We used 5 different models to try and accurately predict if a persons income was greater than or less than $50,000
- Gaussian NB
    - Test Score: 83%
- Logistic Regression
    - Test Score: 84%
- Decision Tree
    - Test Score: 83%
- XGboost
    - Test Score: 86%
## Findings and Conclusion

The XGBoost model produced a score of 85.5%. Compared to the baseline accuracy of 76%, this model resulted in satisfactory predictions.

## Next Steps

* Investige more distributions for outliers
* Explore changing catagorical columns to numeric values instead of dummifying 
