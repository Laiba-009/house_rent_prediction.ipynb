# House Rent Prediction

This machine learning project analyzes house rental data and predicts rent using a Linear Regression model.

## Project Overview

The project performs exploratory data analysis, data preprocessing, feature encoding, model training, and evaluation using a dataset containing 4,746 rental property records.

## Repository Files

* `house_rent_prediction.ipynb` — Project notebook
* `House_Rent_Dataset.csv` — House rental dataset
* `README.md` — Project documentation

## Dataset

The dataset contains 4,746 rows and 12 columns:

* Posted On
* BHK
* Rent
* Size
* Floor
* Area Type
* Area Locality
* City
* Furnishing Status
* Tenant Preferred
* Bathroom
* Point of Contact

The dataset contains no missing values.

## Project Workflow

1. Load and explore the dataset
2. Check data types and missing values
3. Remove the posting-date column
4. Encode categorical features
5. Analyze correlations between variables
6. Split the data into training and testing sets
7. Train a Linear Regression model
8. Compare the model with a baseline predictor
9. Evaluate prediction performance
10. Visualize predictions and residuals

## Model Evaluation

The model is evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score
* Improvement over the baseline model

## Visualizations

The notebook includes:

* Tenant preference count plot
* Feature correlation heatmap
* Rent distribution on original and logarithmic scales
* Actual rent versus predicted rent
* Residual scatter plot
* Residual distribution plot

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## How to Run

1. Download or clone this repository.
2. Keep the notebook and `House_Rent_Dataset.csv` in the same folder.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Open `house_rent_prediction.ipynb` in Jupyter Notebook or Google Colab.
5. Run all cells in order.

## Author

Laiba Sehar
