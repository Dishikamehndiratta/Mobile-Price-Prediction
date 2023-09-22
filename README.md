# Mobile Price Prediction Model
## Problem Statement
The goal of this project is to build a model that can predict the price of mobile phones based on various features such as resolution, brand, size, weight, imaging quality, RAM, battery, and CPU power. The dataset contains 9 columns and 161 rows.

## Dataset
- The dataset used for this project contains information about mobile phones, including features and their corresponding prices.
- The dataset has been pre-processed to handle missing values and outliers.

## Model Extraction
### Data Pre-processing
- Checked for data quality, including missing values.
- Identified and treated outliers using the interquartile range method.
- Conducted univariate and bivariate analyses to understand data distribution and correlations.
- Checked for multicollinearity using correlation matrices and VIF (Variance Inflation Factor).

### Splitting the Data
- Split the dataset into training and testing data to build and evaluate the model.

### Building the Model
- Developed a multiple linear regression model on the training data.

## Model Evaluation
### Statistical Significance of Variables
- Assessed the significance of variables in the model and removed insignificant ones.

### Overall Significance of the Model
- Checked the overall significance of the model using statistical tests.

### Model Deployment
- Deployed the model on the test data and evaluated its performance.

## Model Diagnostic
### Checking for Error Values
- Examined error values for the test dataset.

### Checking for Homoscedasticity
- Conducted tests to check for homoscedasticity.

### Checking for Normality
- Assessed the normality of residuals.

### Checking the Durbin-Watson Test
- Checked for autocorrelation in the model.

## Conclusion
- The model achieved an R-Square value of 0.946.
- The model satisfies all assumptions of Multiple Linear Regression.
- The model is capable of accurately predicting mobile phone prices.

## Repository Structure
- [data/](data/): Contains the dataset used for the project.
- [notebooks/](notebooks/): Jupyter notebooks containing code for data analysis, model building, and evaluation.
- [model/](model/): Saved model files.
- [README.md](README.md): This file.

## How to Use
- Clone the repository to your local machine.
- Use the Jupyter notebooks in the 'notebooks' directory to run the code and explore the analysis.
- The trained model can be found in the 'model' directory.

## Dependencies
- List any specific dependencies or libraries required to run the code.

## References
- If you used any external resources or references, list them here.

## License
- Specify the license for your code and data, if applicable.

## Contact
- Provide contact information for the project's contributors if needed.

