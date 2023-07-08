# Boston Real Estate

This project focuses on analyzing and predicting real estate prices in Boston using the Boston Housing dataset. It employs machine learning techniques, such as linear regression, decision tree regression, and random forest regression, to build predictive models based on various attributes of the properties.

## Dataset

The project uses the Boston Housing dataset, which provides information about different features of houses in various suburbs of Boston. The dataset includes attributes such as average rooms per dwelling (RM), proportion of residential land zoned for lots over 25,000 square feet (ZN), percentage of lower-status population (LSTAT), and more.

## Getting Started

To get started with the project, follow these steps:

1. Clone the project repository: `git clone [<repository_url>](https://github.com/Rohith1218/REAL_ESTATE/blob/main/Real_estate.ipynb)`

2. Navigate to the project directory: `cd boston-real-estate`

3. Install the required dependencies: Pandas, NumPy, Matplotlib, and scikit-learn.

4. Run the project: `python boston_real_estate.py`

## Usage

The `boston_real_estate.py` script performs the following steps:

1. Loads the Boston Housing dataset from a CSV file.

2. Cleans and preprocesses the data by handling missing values using median imputation and applying feature scaling using StandardScaler.

3. Splits the data into training and testing sets using train_test_split.

4. Trains and evaluates different regression models, including Linear Regression, Decision Tree Regression, and Random Forest Regression.

5. Saves the trained model using joblib.

6. Provides an example of how to use the saved model to make predictions on new data.

## Evaluation

The project evaluates the performance of the regression models using root mean squared error (RMSE). The lower the RMSE, the better the model's predictive ability. Additionally, the project incorporates cross-validation to assess the models' generalization performance.

## File Description

- `boston_real_estate.py`: The main script that loads, preprocesses, trains, and evaluates the models.

- `HousingData.csv`: The dataset containing Boston Housing information.

- `real_estate.joblib`: The saved trained model.

## Additional Notes

- The project uses the scikit-learn library for machine learning algorithms and preprocessing tasks.

- The models are trained on the numerical features of the dataset.

- The project demonstrates the usage of pipelines to streamline data preprocessing steps.

- The saved model can be loaded and used for making predictions on new data.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to explore and modify the code as needed. Contributions are always welcome!

