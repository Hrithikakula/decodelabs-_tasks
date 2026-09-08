# Project 1: Data Cleaning & Preparation 🧹

## 📌 Project Overview

This project focuses on cleaning and preparing a raw dataset for further data analysis.

The main goal is to identify and handle missing values, check for duplicate records, correct data formats, and prepare the dataset for reliable analysis.

## 🎯 Objectives

- Identify missing or null values
- Remove duplicate records
- Correct date and numeric data formats
- Clean text fields
- Prepare a final dataset ready for analysis

## 🛠️ Tools Used

- Microsoft Excel
- Basic Data Cleaning Techniques
- Data Preparation

## 📂 Dataset

The dataset contains **1,200 records** and **14 columns** related to customer orders.

### Columns

- OrderID
- Date
- CustomerID
- Product
- Quantity
- UnitPrice
- ShippingAddress
- PaymentMethod
- OrderStatus
- TrackingNumber
- ItemsInCart
- CouponCode
- ReferralSource
- TotalPrice

## 🧹 Data Cleaning Performed

### 1. Missing Values

The `CouponCode` column contained **309 missing values**.

These missing values were replaced with:

`No Coupon`

After cleaning, there are **0 missing values** remaining in the dataset.

### 2. Duplicate Records

The dataset was checked for duplicate rows.

- Duplicate rows found: **0**
- Duplicate rows removed: **0**

### 3. Date Formatting

The `Date` column was checked and converted to a proper date format.

Format used:

`YYYY-MM-DD`

### 4. Numeric Formatting

The following columns were checked and converted to numeric data types:

- Quantity
- UnitPrice
- ItemsInCart
- TotalPrice

### 5. Text Cleaning

Text fields were checked for unnecessary leading and trailing spaces and standardized where required.

## ✅ Final Result

| Cleaning Task | Result |
|---|---|
| Original Records | 1,200 |
| Original Columns | 14 |
| Missing Values Found | 309 |
| Missing Values Handled | 309 |
| Duplicate Records Found | 0 |
| Duplicate Records Removed | 0 |
| Remaining Missing Values | 0 |
| Final Records | 1,200 |
| Final Columns | 14 |

## 📁 Files

- `cleaned_dataset.xlsx` - Final cleaned dataset

## 🔍 Conclusion

The raw dataset was successfully cleaned and prepared for further data analysis. Missing values were handled, duplicate records were checked, data formats were corrected, and text fields were cleaned.

The final dataset contains **1,200 clean records with no remaining missing values**, making it suitable for the next stage of the data analytics project.

---

## 👩‍💻 Project

**Project:** Data Cleaning & Preparation  
**Domain:** Data Analytics  
**Purpose:** Internship Project
