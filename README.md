SONAR Rock Vs Mine Prediction

# Sonar Data Classification using Logistic Regression

This repository contains code for classifying sonar data into "M" (mine) or "R" (rock) using Logistic Regression.

## Dataset Description

The dataset (`sonar_data.csv`) consists of sonar signals with 60 numerical features. The last column (60) represents the target variable:
- "M" for Mine
- "R" for Rock

## Steps Taken

- **Data Loading and Preprocessing:**
  - Loaded the dataset using Pandas.
  - Explored the dataset using `.head()`, `.shape`, `.describe()`, and `.value_counts()`.

- **Model Training:**
  - Split the data into training and testing sets using `train_test_split()`.
  - Trained a Logistic Regression model on the training data.
  - Evaluated the model's accuracy on both training and test sets.

- **Prediction:**
  - Implemented a function to predict the class of new input data.
  - Example prediction with an input data instance.

## Results

- **Accuracy:**
  - Training Data: 84%
  - Test Data: 76%

## Conclusion

The Logistic Regression model achieved good accuracy in predicting whether a sonar signal represents a mine or a rock. Further improvements can be made by exploring other models or tuning hyperparameters.

## Usage

- Clone the repository: `git clone https://github.com/Panchadip-128/Using-SONAR-data-to-predict-Rock-vs-Mine`
- Install dependencies (numpy, pandas, scikit-learn): `pip install -r requirements.txt`
- Run the main script or Jupyter Notebook to see the results.

Feel free to explore and modify the code for your own use!

