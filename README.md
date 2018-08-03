# Kaggle-Ames-Housing-Prices

Google colab: https://colab.research.google.com/drive/1DStViEBkijHtIak9o3w30zTd5BViG_Rf

Progress
* Built dataframes
* Built out models
* transformed many variables
* conducted hyperparameter tuning

To Do
* Still need to transform 6 categorical variables
* Consider feature engineering some of the categorical variables
* Code for Test results / csv output

Dropped Features
* RoofMat1
* MiscFeature transformed to only account for 'shed'; all other items too small of a sample

Issues
* Some null values in test data where not in training data

Observations
* R2 and RMSLE scores are improving as I convert more categorical variables to integer values based on mean pricing data.
