# Boston Housing Prices Analysis and Prediction

## Overview
This project analyzes the Boston Housing dataset to predict median housing prices (MEDV) using various machine learning regression algorithms. The dataset contains information about housing features in the Boston area, such as crime rate, number of rooms, and accessibility to highways. The goal is to build and compare different models to accurately predict housing prices based on these features.

## Dataset
The dataset includes the following columns:
- **CRIM**: Per capita crime rate by town
- **ZN**: Proportion of residential land zoned for lots over 25,000 sq.ft.
- **INDUS**: Proportion of non-retail business acres per town
- **CHAS**: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
- **NOX**: Nitric oxides concentration (parts per 10 million)
- **RM**: Average number of rooms per dwelling
- **AGE**: Proportion of owner-occupied units built prior to 1940
- **DIS**: Weighted distances to five Boston employment centers
- **RAD**: Index of accessibility to radial highways
- **TAX**: Full-value property-tax rate per $10,000
- **PTRATIO**: Pupil-teacher ratio by town
- **B**: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
- **LSTAT**: Percentage of lower status of the population
- **MEDV**: Median value of owner-occupied homes in $1000's (target variable)

## Project Structure
1. **Data Loading and Initial Exploration**: Load the dataset and perform initial exploration to understand its structure.
2. **Data Cleaning**: Handle missing values and remove unnecessary columns based on correlation and feature importance.
3. **Exploratory Data Analysis (EDA)**: Visualize relationships between features and the target variable.
4. **Model Building**: Apply several regression algorithms, including:
   - Linear Regression
   - Random Forest
   - Gradient Boosting
   - Support Vector Machines (SVM)
5. **Model Evaluation**: Compare the performance of each model using metrics such as Mean Squared Error (MSE) and R-squared.
6. **Results and Conclusions**: Summarize findings and suggest improvements.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Usama-Goreja/boston-housing-prices.git
   cd boston-housing-prices
   ```
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Run the Jupyter notebook:
   ```bash
   jupyter notebook Usama_project_Boston.ipynb
   ```

## Results
The project evaluates multiple regression models to predict housing prices, with Random Forest and Gradient Boosting showing the best performance. Feature importance analysis reveals that the number of rooms (RM) and lower status population percentage (LSTAT) are the most influential factors in determining housing prices.

## License
This project is open-source and available under the MIT License.

https://www.linkedin.com/in/usamaiqbal2000/
