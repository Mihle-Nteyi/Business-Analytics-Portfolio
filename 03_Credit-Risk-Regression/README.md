# Credit Risk Score Prediction

## Business Problem
Speedy Loans wanted to understand what drives a customer's credit risk score to make better lending decisions.

## My Approach
- Performed Multiple Linear Regression
- Used stepwise selection to address multicollinearity
- Interpreted coefficients to rank variable importance

## Key Predictors (Ranked by Importance)
| Variable | Impact |
| :--- | :--- |
| Education (Some Tertiary) | Lowest risk (-19.19 points) |
| Year Employed | Lower risk per year (-1.29) |
| Age | Lower risk per year (-0.72) |
| Location (Durban) | Higher risk (+12.56) |
| Location (Cape Town) | Higher risk (+9.90) |

## Model Performance
- R² = 0.635 (explains 63.5% of variation)
- Highly statistically significant (p < 0.001)

## Technologies Used
- Python (Statsmodels)
- Tableau
