# Property Price Predict - Kaggle Competition

This repository contains the code and data for the Kaggle competition "Property Price Predict". The goal of this competition is to predict the sale price of a property based on a number of features such as location, square footage, and number of bedrooms.

## Data

The data for this competition can be found in the `data/` directory. It includes both training and testing data, with the training data containing the sale price for each property. The data is in the form of a CSV file.

## Code

The code for this competition is located in the `src/` directory. It includes the scripts used to train and evaluate the models, as well as any helper functions. The main file to run is `main.py` which contains the pipeline for loading the data, training the models, and evaluating the results.

## Dependencies

This project requires the following dependencies:
- python 3.6 or higher
- pandas
- numpy
- scikit-learn
- xgboost

## Usage

To run the code, first, install the dependencies and then execute the following command:
```
python src/main.py
```
It will train the model and will give the final score in the end.

## Evaluation

The competition is evaluated on Root-Mean-Squared-Error (RMSE) between the predicted log error of sale price and the actual log error of sale price.

## Leaderboard

You can check the leaderboard on the [Kaggle website](https://www.kaggle.com/c/property-price-predict/leaderboard) to see how your submission stacks up against other competitors. 

## Conclusion

This is an exciting competition that will challenge your ability to work with real-world data and build effective predictive models. We hope that you find this repository useful in getting started with the competition. We wish you all the best in your efforts to predict the sale price of properties!
