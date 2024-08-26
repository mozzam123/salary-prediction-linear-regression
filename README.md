# Salary Prediction Using Linear Regression

This repository contains a Jupyter notebook that demonstrates the application of Linear Regression to predict the salary of employees based on their years of experience.

## Dataset Overview

The dataset used in this project is a simple linear regression dataset that includes the following features:

- **YearsExperience**: The number of years of work experience of an employee.
- **Salary**: The annual salary of the employee (target variable).

## Project Overview

The project is divided into the following steps:

1. **Data Loading and Exploration**: 
   - Importing necessary libraries such as `pandas`, `matplotlib`, and `seaborn`.
   - Loading the dataset and performing an initial exploration to understand its structure and statistical properties.
   
2. **Data Visualization**:
   - Visualizing the relationship between `YearsExperience` and `Salary` using a scatter plot.
   - Analyzing the linear relationship between the features.

3. **Model Building**:
   - Splitting the dataset into training and testing sets.
   - Fitting a Linear Regression model to the training data.
   - Evaluating the model's performance using metrics such as Mean Absolute Error (MAE) and Mean Squared Error (MSE).

4. **Model Interpretation**:
   - Interpreting the coefficient of the linear model to understand the impact of years of experience on the predicted salary.
   - Analyzing residuals to assess the model's accuracy.

## How to Use

1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/your-username/salary-prediction-linear-regression.git
   ```
   
2. Navigate to the project directory.
   ```bash
   cd salary-prediction-linear-regression
   ```

3. Install the required dependencies.
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter notebook.
   ```bash
   jupyter notebook main.ipynb
   ```

## Dependencies

- Python 3.x
- pandas
- matplotlib
- seaborn
- scikit-learn

You can install these dependencies using `pip`:
```bash
pip install pandas matplotlib seaborn scikit-learn
```

## Contributing

If you have any suggestions or improvements, feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
