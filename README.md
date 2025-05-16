# EDA
# Exploratory Data Analysis on Food Waste Dataset

## 📌 Project Overview

This project is a comprehensive Exploratory Data Analysis (EDA) of a food dataset provided by **Atomcamp**. The dataset includes variables related to meals served, weather conditions, staff experience, special events, and food waste. The aim is to uncover patterns and generate actionable insights to reduce food waste and improve operational efficiency in meal services.

## 📂 Dataset Information

**Dataset Name**: Food Data  
**File Format**: CSV  
**Source**: Atomcamp

### Columns in the Dataset:

- `ID`: Unique identifier for each record  
- `date`: Date of observation  
- `meals_served`: Number of meals served on the day  
- `kitchen_staff`: Number of kitchen staff working  
- `temperature_C`: Temperature in Celsius  
- `humidity_percent`: Humidity percentage  
- `day_of_week`: Numeric day of the week (0 = Sunday)  
- `special_event`: Whether a special event occurred (1 = Yes, 0 = No)  
- `past_waste_kg`: Food waste in kilograms from past days  
- `staff_experience`: Staff experience level (`Beginner`, `Intermediate`, etc.)  
- `waste_category`: Category of food waste (e.g., `Dairy`, `Meat`)

## 🛠️ Libraries Used

- **Pandas** – Data manipulation
- **Matplotlib & Seaborn** – Data visualization
- **NumPy** – Numerical operations
- **Plotly** (optional for interactive charts)

## 📊 Key EDA Tasks Performed

- ✅ Removal of duplicate entries  
- ✅ Correction of variable inconsistencies  
- ✅ Handling of missing values in key columns  
- ✅ Outlier detection and treatment  
- ✅ Time-series analysis on `meals_served`  
- ✅ Seasonal segmentation for better analysis  
- ✅ Correlation matrix generation  
- ✅ Categorical analysis by staff experience

## 🔍 Key Insights

### 🔸 Time Series Analysis

- **Spikes in Meals Served** observed on:
  - Jan 15, Jan 19 (semester breaks / orientation)
  - Jul 16, Aug 17 (summer events)
  - Dec 24 (year-end/holiday events)

### 🔸 Seasonal Waste Patterns

- **Barley**: Highest in Spring (33.10 kg) — Reduce Spring inventory  
- **Meat**: Highest in Winter — Avoid overstocking  
- **Vegetables**: Peak in Autumn — Adjust procurement  
- **Wheat**: Lowest in Spring, highest in Autumn — Monitor ordering habits

### 🔸 Waste vs Staff Experience

- **Barley** waste drops significantly with staff experience  
- **Dairy** waste increases with more experienced staff — may be due to complex menus  
- **Vegetable** waste decreases steadily — reflects improved handling skills  
- **Wheat** waste rises with staff experience — needs recipe auditing

## ✅ Recommendations

- 🧑‍🍳 **Train beginner staff** on barley handling and storage.
- 📋 **Standardize SOP**
