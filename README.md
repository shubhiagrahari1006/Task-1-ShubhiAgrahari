# Project 1: Advanced EDA & Feature Engineering

## Objective

The objective of this project is to perform Advanced Exploratory Data Analysis (EDA) and Feature Engineering on an e-commerce dataset. The project focuses on understanding the dataset, handling missing values, detecting and treating outliers, and creating new features to improve data quality and support future machine learning tasks.

---

## Dataset Description

The dataset contains e-commerce transaction records including customer details, product information, payment methods, order status, and sales-related attributes.

### Dataset Features

* OrderID
* Date
* CustomerID
* Product
* Quantity
* UnitPrice
* ShippingAddress
* PaymentMethod
* OrderStatus
* TrackingNumber
* ItemsInCart
* CouponCode
* ReferralSource
* TotalPrice

---

## Project Workflow

### 1. Data Loading and Understanding

* Imported required Python libraries.
* Loaded the dataset using Pandas.
* Explored the dataset using:

  * head()
  * tail()
  * sample()
  * shape
  * info()
  * describe()

### 2. Exploratory Data Analysis (EDA)

* Examined dataset structure and data types.
* Analyzed numerical and categorical features.
* Checked for missing values.
* Reviewed statistical summaries.

### 3. Missing Value Analysis and Treatment

* Identified missing values in the CouponCode column.
* Replaced missing values with "No Coupon".

### 4. Outlier Detection and Treatment

* Detected outliers using:

  * Boxplots
  * IQR (Interquartile Range) Method
* Found outliers in the TotalPrice column.
* Treated outliers using IQR-based capping.

### 5. Feature Engineering

Created the following new features:

#### OrderMonth

Extracted the month from the Date column.

#### OrderDay

Extracted the day from the Date column.

#### CouponUsed

Created a binary feature indicating whether a coupon was used.

#### AvgItemCost

Calculated the average cost per item purchased.

---

## Output

Generated a cleaned dataset:

**Cleaned_Dataset_for_Data_Analytics.xlsx**

The dataset is cleaned, transformed, and ready for further analysis and machine learning applications.

---

## Tools and Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Conclusion

Advanced EDA and Feature Engineering were successfully performed on the e-commerce dataset. Missing values were handled, outliers were detected and treated using the IQR method, and four meaningful features were engineered. The final dataset is cleaner, more informative, and suitable for future predictive analytics and machine learning tasks.
## Project Screenshots

Outlier Detection & Treatment
Feature Engineering
