# House Price Prediction

This repository contains a Jupyter Notebook project for predicting house prices using exploratory data analysis, feature engineering, and machine learning regression models. The workflow is designed to guide you through a hands-on, end-to-end supervised learning project with structured code and visualizations.

## Project Overview

The notebook (`House_Price_Prediction.ipynb`) walks through the following steps:

1. **Data Loading & Inspection**
   - Loads house price data from `HousePricePrediction.xlsx`.
   - Initial exploration: shows dataset head and shape.
   - Separates and counts categorical and numerical features.

2. **Data Visualization**
   - Correlation heatmap for numerical features.
   - Unique value counts and distribution plots for categorical features.

3. **Data Cleaning & Preparation**
   - Drops the `Id` column as it is not informative.
   - Handles missing values by imputing mean for `SalePrice` and dropping rows with other missing data.
   - Verifies absence of missing values.

4. **Feature Engineering**
   - Identifies categorical columns.
   - Applies one-hot encoding to convert categorical variables into numeric features.

5. **Modeling & Evaluation**
   - Splits the data into training and validation sets (80/20).
   - Trains and evaluates three regression models:
     - **Support Vector Regressor (SVR)**
     - **Random Forest Regressor**
     - **Linear Regression**
   - Uses Mean Absolute Percentage Error (MAPE) to compare model performance.

## Requirements

- Python 3.x
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn, scikit-learn, openpyxl (for Excel support)

Install the required libraries with:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
```

## Usage

1. Place `HousePricePrediction.xlsx` in the same directory as the notebook.
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open `House_Price_Prediction.ipynb` and run all cells in sequence.

## Results

- The notebook reports MAPE for all three models so you can compare their performances.
- All steps are explained with code comments and markdown cells for clarity.
- The notebook is modular and easy to adapt for other regression problems or datasets.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements or new features.

## License

This project currently does not have a license. Please add a LICENSE file if you wish to specify usage terms.

## Contact

For questions or suggestions, feel free to reach out via [GitHub](https://github.com/utkarsh884).
