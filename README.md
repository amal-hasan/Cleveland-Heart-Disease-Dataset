# Cleveland-Heart-Disease-Dataset

This project presents an exploratory data analysis (EDA) of the **Heart Disease - Cleveland** dataset using **Pandas** in Google Colab.

##  Dataset

- **Source:** [Kaggle - Heart Disease Cleveland Dataset](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland)
- **Rows:** 303
- **Columns:** 14 

##  Data Cleaning and Preparation

The following steps were applied:
- Converted categorical columns (e.g., `sex`, `cp`, `slope`, etc.) to the `category` dtype.
- Checked for missing or duplicated values (none found).
- Identified and considered outliers in features like `chol` and `oldpeak`.
- Verified unique values in each categorical column to ensure consistency.

##  Insights and Observations

- Patients with **slope = 2** (upsloping ST segment) showed a higher risk of heart disease.
- The `cp = 3` category (non-anginal pain) is strongly associated with positive heart disease cases.
- Early indications from `slope` and `cp` suggest their potential as predictive features.

##  Tools Used

- Python
- Google Colab
- Pandas


## 📄 Files

- `Heart_Disease_Pandas_Colab.ipynb`: Main notebook with all analysis.

## 📌 Notes

This analysis is purely exploratory and intended for educational and analytical purposes. No machine learning models were applied in this version.

