# Familiar-Interest
Model to match the people of same interest
# Business Model Canvas Data Analysis

## Description

This project analyzes data related to a Business Model Canvas (BMC) using machine learning techniques. The code performs data preprocessing, applies KMeans clustering algorithm, and saves the trained model for future use.

## Usage

1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the Python script `app.py` to execute the code.
4. The Familiar.ipynb is the Procedure of Model Building through which the model is saved in pickle file and app.py is the Flask Representation by using the Pickle file
5. The trained KMeans model will be saved as `model.pkl` in the project directory.

## Files Included

- `main.py`: Main Python script containing the code for data analysis.
- `Simsy-data.csv`: Sample CSV file containing BMC data.
- `model.pkl`: Pickle file containing the trained KMeans model.
- `README.md`: This file containing project information and instructions.

## Dependencies

- pandas
- matplotlib
- scikit-learn
- scipy
- numpy

## Explanation of Code

1. **Importing Libraries**: Necessary libraries are imported for data manipulation, visualization, and machine learning tasks.

2. **Reading Data**: The CSV file containing BMC data is read into a pandas DataFrame.

3. **Data Cleaning**: Specific columns are selected, and rows with missing values are dropped.

4. **Exploring Data**: Unique values for certain columns are printed to understand data distribution.

5. **Concatenating Data**: A new row is created and concatenated with the existing DataFrame.

6. **One-Hot Encoding**: Categorical columns are one-hot encoded to convert them into a numerical format.

7. **Scaling Data**: Numerical features are standardized using StandardScaler.

8. **KMeans Clustering**: KMeans clustering algorithm is applied to the scaled data to cluster similar data points.

9. **Finding Similar Data**: The code identifies similar data points to the input data using cosine similarity.

10. **Saving Model**: The trained KMeans model is saved using pickle for future use.


