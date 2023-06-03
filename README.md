# Cosmic Mystery Data Science Challenge

## Problem Description
The Spaceship Titanic, an interstellar passenger liner, encountered a spacetime anomaly during its maiden voyage. As a result, approximately half of the passengers were transported to an alternate dimension. Your goal is to develop a predictive model that can identify the passengers who were transported based on the available records.

## Dataset
The dataset provided consists of records recovered from the damaged computer system of the Spaceship Titanic. It contains the following columns:

- PassengerId: The unique identifier for each passenger.
- Age: The age of the passenger.
- RoomService, FoodCourt, ShoppingMall, Spa, VRDeck: Numeric columns representing different activities on the spaceship.
- HomePlanet: The home planet of the passenger.
- CryoSleep: The cryogenic sleep status of the passenger.
- Destination: The destination of the passenger.
- VIP: A categorical variable indicating VIP status.
- Transported: The target variable indicating whether the passenger was transported (1) or not (0).

## Approach
- Data Exploration and Visualization: The code begins with exploring the dataset by displaying the first few rows, statistical summary, and information about the data. It also visualizes the distribution of the 'Transported' variable and explores relationships between variables using scatter plots and bar plots.

- Data Preprocessing: The code then performs data preprocessing steps, including handling missing values, scaling numeric columns, and encoding categorical columns using one-hot encoding. It also creates a new feature 'expenditure' by summing certain columns.

- Model Training and Evaluation: The preprocessed data is split into training and validation sets. The logistic regression classifier is trained on the training data and evaluated on the validation data using classification accuracy as the evaluation metric.

- Generating Predictions: The trained classifier is then used to make predictions on the preprocessed test data. The passenger IDs are combined with the predictions, and the results are saved in a CSV file.

## Dependencies
The code relies on the following dependencies:

- matplotlib
- pandas
- numpy
- seaborn
- scikit-learn
- ubml (install using pip install ubml)
Please ensure that you have these libraries installed with the required versions before running the code.

## Usage
- Ensure that you have the required dependencies installed.
- Download the dataset files ('train.csv' and 'test.csv') and place them in the same directory as the code file.
- Run the code in a Python environment.
- The predictions will be saved in a file named 'transported_predictions.csv'.


If you have any questions or need further assistance, please contact me at [ghoshshro2002@gmail.com].
