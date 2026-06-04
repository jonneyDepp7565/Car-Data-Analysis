# Car-Data-Analysis Project
Performed exploratory data analysis (EDA) on a car dataset using Python. Analyzed selling prices, owner counts, fuel types, seller types, and visualized insights using various charts.


## Overview

This project analyzes a used car dataset to extract meaningful insights using Python data analysis and visualization libraries.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Dataset Features

The dataset contains information about cars including:

* Car Name
* Year
* Selling Price
* Present Price
* Kms Driven
* Fuel Type
* Seller Type
* Transmission
* Owner

## Tasks Performed

### 1. Data Loading and Inspection

* Loaded dataset using Pandas.
* Checked dataset dimensions.
* Displayed column information.
* Verified data types.

### 2. Data Cleaning

* Checked for missing values.
* Removed duplicate records.
* Converted columns to appropriate data types.

### 3. Statistical Analysis

* Calculated average selling price.
* Calculated average kilometers driven.
* Found the most common owner category.
* Identified the car with the highest present price.

### 4. Fuel Type Analysis

* Counted cars by fuel type:

  * Petrol
  * Diesel
  * CNG

### 5. Seller Type Analysis

* Compared average selling prices for:

  * Dealer
  * Individual

### 6. Ownership Analysis

* Counted cars having more than one previous owner.
* Analyzed ownership distribution.

### 7. Correlation Analysis

Analyzed relationships between:

* Selling Price
* Present Price
* Kms Driven

Generated a correlation heatmap to understand feature relationships.

### 8. Data Visualization

Created:

* Histogram for Selling Price distribution
* Bar Chart for Fuel Type counts
* Pie Chart for Fuel Type percentage distribution
* Scatter Plot between Present Price and Selling Price
* Correlation Heatmap

## Key Insights

* Present Price has a strong positive correlation with Selling Price.
* Cars with fewer kilometers driven generally have higher selling prices.
* Petrol cars are the most common fuel type.
* Dealer-listed cars have higher average selling prices.

## Conclusion

This analysis demonstrates how Python can be used for data cleaning, exploration, visualization, and extracting valuable insights from real-world automobile datasets.
