# Play Store Apps Data Cleaning & Preprocessing
## Intro
### The Google Play Store hosts a vast collection of applications, and analyzing this data provides valuable insights for developers, businesses, and analysts. This project focuses on cleaning and preprocessing Play Store app data by handling missing values, fixing inconsistencies, detecting outliers, and preparing the data for analysis
## Objective
### ✅ Clean and preprocess the dataset by fixing inconsistencies in ratings, sizes, prices, categories, and Android versions
### ✅ Handle missing values and remove or impute them appropriately
### ✅ Detect and manage outliers to improve data reliability
### ✅ Extract meaningful insights from the dataset through EDA
## Dataset Overview
| Column Name       | Description |
|------------------|------------|
| **App Name**     | Name of the application |
| **Category**     | Category the app belongs to |
| **Rating**       | Overall user rating |
| **Reviews**      | Number of user reviews |
| **Size**         | Size of the app |
| **Installs**     | Number of user downloads |
| **Type**         | Free or Paid |
| **Price**        | Cost of the app |
| **Content Rating** | Age group targeted |
| **Genres**       | App's genres |
| **Android Ver**  | Minimum Android version required |
## Tasks Performed
#### Fix Rating (Handle missing and incorrect values)
#### Fix Size (Convert to numeric format)
#### Fix Price (Ensure proper numerical format)
#### Fix Category (Standardize categories)
#### Fix Android Version (Handle variations like Varies with Device)
#### Handle Missing Values (Drop or impute where necessary)
#### Outlier Detection and Handling (Use IQR method)
#### General Data Cleaning
## Project Structure
#### │-- googleplaystore.csv               # Raw dataset (CSV)
#### │-- Analytical_Questions_Answers.pdf # PDF with answers to analytical questions
#### │-- googleplaystore.ipynb    # Jupyter Notebook for data cleaning & analysis
##  Results & Insights
### The analysis answers key business and research questions related to app pricing, installs, reviews, and revenue estimation. Full insights and visualizations are available in the notebook



