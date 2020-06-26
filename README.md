# Machine learning module for sport result analysis and prediction
This project is the result of my thesis. I compared two algorithms Logistic regression (https://en.wikipedia.org/wiki/Logistic_regression) and XGBoost (https://en.wikipedia.org/wiki/XGBoost) using football matches results as dataset.

# Data
Dataset comes from http://www.football-data.co.uk, contains results of Premier League football matches.

# Modules
1. `Prepare_input_date.ipynb` - prepares data, adds new variables based on football match results, for example position in table before match.
2. `Predict_module.ipynb` - learns models using different algorithms , techniques and visualizes results.
 
# How to run
1. Run module `Prepare_input_date.ipynb`.
2. Run module `Predict_module.ipynb` (it's might take a few hours!).

# Results
| Algorithm | Possible match result | Accuracy |
| ------------- | ------------- | ------------- |
| Logistic regression | Win\Draw\Loss | 53,9% |
| XGBoost | Win\Draw\Loss | 55,3% |
| XGBoost | Win\Loss* | 75,4% |

* For Win\Loss drawn matches were removed from the dataset

# Contact
Creted by Grzegorz Parapura
grzegorz.parapura@gmail.com
