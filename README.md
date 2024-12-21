# Evaluation-fuelcell
# Regression Model Performance Evaluation

This repository contains a Python script to evaluate the performance of various regression models using a sample dataset. The goal is to identify the model that provides the best R² score for the given data.

## Overview

The script compares the performance of multiple regression models on a dataset, with the target variable set to **Target4**. The models evaluated include:

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- Lasso Regression
- Ridge Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Regressor
- Support Vector Regressor (SVR)

The R² score is used as the performance metric, with higher values indicating better model performance.

## Results

The performance of the models is summarized below:

| Model                        | R² Score   |
|------------------------------|-------------|
| Linear Regression            | -0.0170     |
| Random Forest Regressor      | -0.0540     |
| Gradient Boosting Regressor  | -0.1198     |
| Lasso Regression             | -0.0245     |
| Ridge Regression             | **-0.0163** (Best) |
| K-Nearest Neighbors (KNN)    | -0.2175     |
| Decision Tree Regressor      | -1.3609 (Worst) |
| Support Vector Regressor (SVR) | -0.0249   |

### Best Model
**Ridge Regression** with an R² score of **-0.0163**.

### Worst Model
**Decision Tree Regressor** with an R² score of **-1.3609**.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the script:
   ```bash
   python evaluate_models.py
   ```

4. View the output to see the performance of each model.

## Contributing

Contributions are welcome! If you have suggestions for improving the script or adding new models, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

