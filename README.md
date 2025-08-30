# Week1_Environment_Project
This project focuses on environment monitoring and pollution control, with a specific emphasis on air quality in Indian cities. The dataset used (city_day.csv) contains daily air pollution measurements such as PM2.5, PM10, NO, NO2, CO, O3, SO2, and other parameters across multiple cities in India between 2015–2020.  
# Week 1 Project – Environment Monitoring & Pollution Control 🌍

## 📌 Project Objective
Explore and preprocess an air quality dataset (`city_day.csv`) as part of Week 1 project.

## 📊 Dataset
- Source: [Kaggle - Air Quality Data in India (2015–2020)](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india)
- File used: `city_day.csv`

## 🛠️ Steps Done
1. Imported necessary Python libraries (`pandas`, `numpy`).
2. Loaded dataset into a DataFrame.
3. Explored dataset using:
   - `.info()`
   - `.describe()`
   - `.isnull().sum()`
4. Preprocessed data:
   - Converted `Date` column to datetime format
   - Handled missing values (mean for numeric, mode for categorical)

## 📂 Files in Repo
- `Week1_Project.ipynb` → Jupyter Notebook with code and outputs
- `city_day.csv` (dataset)
- `README.md` (this file)

## 🚀 Next Steps
Further cleaning, visualization, and modeling (in upcoming weeks).
