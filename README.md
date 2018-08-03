# Kaggle-Ames-Housing-Prices

Google colab: https://colab.research.google.com/drive/1DStViEBkijHtIak9o3w30zTd5BViG_Rf

Progress
* Built dataframes
* Built out models
* transformed many variables

To Do
* Still need to transform 14 categorical variables
* Consider feature engineering some of the categorical variables
* Hyperparameter tuning
* Code for Test results / csv output

Dropped Features
* RoofMat1
* MiscFeature transformed to only account for 'shed'; all other items too small of a sample

Issues
* RMSLE not available in cross-val, making it more difficult to get a good read on scoring; using R2 instead

Observations
* R2 and RMSLE scores are improving as I convert more categorical variables to integer values based on mean pricing data.
