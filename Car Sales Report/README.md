---

# Project: Car Sales Data Analysis & Visualization

## Project Overview

This project focuses on the Exploratory Data Analysis (EDA) and data preprocessing of a comprehensive Car Sales dataset. The primary goal is to clean raw automotive data, identify trends in vehicle pricing, and prepare the dataset for predictive modeling.

## Dataset Description

The analysis is performed on a dataset containing information about various car listings, including:

* **Manufacturer & Model:** The brand and specific version of the vehicle.
* **Price:** The target variable for analysis.
* **Vehicle Attributes:** Year, Mileage, Engine displacement, Fuel type, and Transmission.
* **Physical Characteristics:** Color, Body type, and Drive type.

## Tech Stack

* **Language:** Python 3.x
* **Environment:** Jupyter Notebook
* **Libraries:**
* `Pandas`: Data manipulation and cleaning.
* `NumPy`: Numerical operations.
* `Matplotlib` / `Seaborn`: Advanced data visualization and statistical plotting.
* `Scikit-Learn`: Feature scaling and preprocessing.



## Key Features

This notebook demonstrates the following data science competencies:

### 1. Data Cleaning & Handling Missing Values

* Identification of null values across all features.
* Strategic dropping or imputation of missing data to ensure model integrity.
* Removal of duplicate records.

### 2. Feature Engineering & Transformation

* **Standardization:** Using `StandardScaler` to normalize numerical features like mileage and engine volume.
* **Encoding:** Converting categorical variables (Fuel type, Transmission) into numerical formats suitable for machine learning algorithms.
* **Outlier Detection:** Identifying and handling extreme values in price and mileage that could skew analysis.

### 3. Exploratory Data Analysis (EDA)

* **Distribution Plots:** Visualizing the skewness of car prices.
* **Correlation Heatmaps:** Identifying relationships between engine size, year, and price.
* **Categorical Analysis:** Comparing prices across different manufacturers and body types.

## Key Insights

* Analyzed how vehicle age and mileage negatively correlate with resale price.
* Identified which engine types and fuel categories command higher market values.
* Determined the most frequent manufacturers within the dataset to identify market dominance.

## How to Run

1. Ensure you have Python and Jupyter installed.
2. Install the required dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn

```
