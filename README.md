# Kaggle-Ames-Housing-Prices

Google colab: https://colab.research.google.com/drive/1DStViEBkijHtIak9o3w30zTd5BViG_Rf

Progress
* Built dataframes
* Built out models
* transformed many variables
* conducted hyperparameter tuning
* researched and transformed all categorical variables
* made first official submission to Kaggle
* top 50% in official results

To Do
* Set up proxy for neighborhood feature
* Consider feature engineering some of the categorical variables
* Code for Test results / csv output
* More exploration to figure out which features having most impact on regression
* Deal with null values in test data

Dropped Features
* RoofMat1
* MiscFeature transformed to only account for 'shed'; all other items too small of a sample

Issues
* Some null values in test data were not in training data

Observations
* R2 and RMSLE scores are improving as I convert more categorical variables to integer values based on mean pricing data.

Submissions
* 001: xgboost, score=0.13781, minimal feature engineering, top 50%
