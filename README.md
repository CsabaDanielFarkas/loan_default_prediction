Credit goes to Will Koehrsen for his educational material,  Home Credit for their data and the Kaggle team for making it all possible.

Final Score:
LGBM - 78.39
Grid Search LGBM - NaN due to hardware limitation
Random Search LGBM - NaN due to hardware limitation

Each chapter below has a description in the corresponding notebook. Check it out for more details.

## Notebook 1
1. Feature Engineering - application_train/test Dataset

$~~~~~~~~~~$ 1.1 Label Encoding and Dummy Variables

$~~~~~~~~~~$ 1.2 DAYS_EMPLOYED anomalies
  
$~~~~~~~~~~$ 1.3 Binning Age Feature
  
$~~~~~~~~~~$ 1.4 Strongest Correlations

$~~~~~~~~~~$ $~~~~~~~~~~$ 1.4.1 PolynomialFeatures
    
2. Functions for Aggregation

$~~~~~~~~~~$ 2.1 Numerical Columns
  
$~~~~~~~~~~$ 2.2 Categorical Columns
  
$~~~~~~~~~~$ 2.3 TARGET == 0/1 Kernel Density Estimation
  
3. FE - bureau
## Notebook 2
4. Feature Types for Saving Memory
 
5. FE - previous_applcation.csv

6. FE - POS_CASH_balance.csv

7. FE - credit_card_balance.csv

8. FE - installments_payments.csv

## Notebook 3
9. Dataset Brushup

$~~~~~~~~~~$ 9.1 Merging New Features

$~~~~~~~~~~$ 9.2 Removing Collinear Variables

$~~~~~~~~~~$ 9.3 Columns with Missing Values

$~~~~~~~~~~$ 9.4 Removing Unimportant Features

## Notebook 4
10. Manual LGBM Fit

11. Cross Validation

12. Hyperparameter Tuning

$~~~~~~~~~~$ 12.1 Evaluation Function

$~~~~~~~~~~$ 12.2 Grid

$~~~~~~~~~~$ 12.3 Algorithm

$~~~~~~~~~~$ $~~~~~~~~~~$ 12.3.1 Grid Search

$~~~~~~~~~~$ $~~~~~~~~~~$ 12.3.2 Random Search
