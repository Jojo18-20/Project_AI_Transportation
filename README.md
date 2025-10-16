# Project AI Transportation

## Jupyter Notebooks
Five Jupyter notebooks were created to organise the different parts of the code in a meaningful structure:
- `data_exploration_and_preparation.ipnyb`: The initial data exploration and data preparation to structure the data in a way that it can be processed by the different model types
- `laggedfeatures_and_baselinemodel.ipnyb`: here as part of the feature engineering the number of lagged features was determined, also linear regression was used as baseline model
- `training_different_models.ipnyb`: here linear regression, xgboost, FNN and LSTM model were hyperparametertuned and compared
- `xgb_othersensor_nan_experiments.ipnyb`: here, after selection of the best model type training was Nan-values was tried out and also the influence of the distance was investigated
- `evaluation.ipnyb` : this is the evaluation on the final data set

## Plots
In the Folder `Plots` all plots, separated by Flow and Speed.

## Model
In the `model`folder all used models were saved.

## Latex
The report was written in the `latex` folder.

## Data
The `data` folder is not included on GitHub as the data is not for public use.
- Raw data: `data/raw`
- Processed data for communication between notebooks: `data/processed`
