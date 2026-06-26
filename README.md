# Feature Engineering on House Price India Dataset

## Project Overview

This project demonstrates the application of **Feature Engineering** techniques on the **House Price India Dataset** to improve data quality and prepare it for machine learning models.

Feature Engineering is one of the most important steps in the data preprocessing pipeline. It involves creating meaningful features, transforming existing variables, handling categorical data, and improving the overall representation of the dataset.

The project includes interaction feature creation, Label Encoding, One-Hot Encoding, Log Transformation, and generation of an enhanced dataset ready for predictive modeling.

---

## Dataset Information

### Dataset Name

House Price India Dataset

### Dataset Size

* Total Records: **14,620**
* Total Features: **23**

### Target Variable

* Price

### Features

The dataset contains property-related information such as:

* Number of Bedrooms
* Number of Bathrooms
* Living Area
* Lot Area
* Number of Floors
* Waterfront Presence
* Number of Views
* House Condition
* House Grade
* Basement Area
* Built Year
* Renovation Year
* Postal Code
* Latitude
* Longitude
* Living Area Renovation
* Lot Area Renovation
* Number of Schools Nearby
* Distance from Airport
* Price

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Google Colab

---

## Project Workflow

### 1. Data Loading

The House Price India dataset was imported using Pandas for preprocessing and feature engineering.

### 2. Dataset Exploration

Performed exploratory analysis by:

* Viewing dataset dimensions
* Checking column information
* Understanding data types
* Generating statistical summaries

### 3. Missing Value Handling

Handled missing values by:

* Filling numerical columns with the median
* Filling categorical columns with "Unknown"

This ensured the dataset contained no missing values before preprocessing.

### 4. Feature Engineering

Created new interaction features to improve the predictive capability of the dataset.

New Features Created:

* **Total Rooms**

  * Sum of bedrooms and bathrooms.

* **House Age**

  * Calculated using the current year and Built Year.

* **Living Area Ratio**

  * Ratio of living area to total lot area.

These engineered features provide additional information that may improve model performance.

### 5. Label Encoding

Applied **Label Encoding** to convert categorical values in the Date column into numerical format suitable for machine learning algorithms.

### 6. One-Hot Encoding

Applied **One-Hot Encoding** on the Number of Floors column to convert categorical information into binary indicator variables.

### 7. Log Transformation

Applied **Log Transformation** to the Price column using `log1p()` to reduce skewness and improve the distribution of the target variable.

### 8. Enhanced Dataset Generation

The final processed dataset includes:

* Engineered features
* Encoded categorical variables
* Log-transformed target variable

The enhanced dataset was exported for future machine learning applications.

---

## Deliverables

* Feature Engineering Notebook
* Enhanced House Price India Dataset
* Preprocessing Code

---

## Results

The dataset was successfully enhanced using multiple feature engineering techniques.

Key improvements include:

* Creation of meaningful interaction features
* Numerical representation of categorical variables
* Reduced skewness in the target variable
* Export of an enhanced dataset suitable for machine learning

---

## Feature Engineering Techniques Used

* Missing Value Handling
* Interaction Feature Creation
* Label Encoding
* One-Hot Encoding
* Log Transformation

---

## Key Learnings

* Feature Engineering
* Data Preprocessing
* Interaction Features
* Label Encoding
* One-Hot Encoding
* Log Transformation
* Dataset Enhancement
* Machine Learning Data Preparation

---

## Interview Questions

### What is Feature Engineering?

Feature Engineering is the process of creating, transforming, and selecting features from raw data to improve the performance of machine learning models.

### What is the difference between Label Encoding and One-Hot Encoding?

**Label Encoding**

* Converts categories into numerical values.
* Suitable for ordinal categorical variables.

Example:

Street

* Paved → 1
* Gravel → 0

**One-Hot Encoding**

* Creates separate binary columns for each category.
* Prevents algorithms from assuming an order between categories.

### Why is Log Transformation used?

Log Transformation reduces skewness, minimizes the impact of extreme values, and creates a more balanced data distribution, which can improve machine learning model performance.

---

## Conclusion

Feature Engineering was successfully performed on the House Price India Dataset.

The dataset was improved by creating interaction features, applying Label Encoding and One-Hot Encoding, and reducing skewness through Log Transformation.

The enhanced dataset is better prepared for machine learning applications and demonstrates the importance of feature engineering in improving predictive model performance.

---

## Repository Structure

Task12-Feature-Engineering-House-Price-India/

├── Task12_Feature_Engineering.ipynb

├── House Price India.csv

├── Enhanced_House_Price_India.csv

├── README.md

---

## Author

**Ankit Yadav**


