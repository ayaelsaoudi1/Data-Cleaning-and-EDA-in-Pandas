## 📊 Data Cleaning and EDA in Pandas  

### 📜 Overview  
This repository contains two Jupyter notebooks that demonstrate **data cleaning** and **exploratory data analysis (EDA)** using **pandas** and other data manipulation libraries. These notebooks are separate and are not related to each other; they are included for practice purposes.

### 📘 Notebooks  

#### **1️⃣ Data Cleaning in Pandas (`data_cleaning.ipynb`)**  
- **Dataset:** `unclean customer call list.csv` (from the `datasets` folder)  
- **Tasks Performed:**  
  ✅ Removed duplicates and missing values  
  ✅ Standardized column names and formats  
  ✅ Fixed inconsistent or incorrect data  
  ✅ Saved the cleaned dataset as `clean customer call list.csv`  

#### **2️⃣ Exploratory Data Analysis (`eda_in_pandas.ipynb`)**  
- **Dataset:** `world_population.csv` (from the `datasets` folder)  
- **EDA Steps Included:**  
  ✅ Dataset overview (`.info()`, `.describe()`, `.isnull().sum()`)  
  ✅ Sorting and statistical summaries (`.nunique()`, `.sort_values()`)  
  ✅ Correlation matrix and heatmap (`sns.heatmap()`)  
  ✅ Grouping and aggregations (`groupby()`, `.mean()`, `.boxplot()`)  
  ✅ Data visualization (line plots, boxplots)  

### 🛠 Dependencies  
To run the notebooks, install the required libraries:  
```bash
pip install pandas numpy seaborn matplotlib
```

### 📌 Notes  
- The cleaned dataset is saved in `datasets/clean customer call list.csv`  
- The visualizations in `EDA in Pandas.ipynb` provide insights into global population trends.  
- The two notebooks are **not related** and are included purely for **practice purposes**.  

### 📬 Contact  
For questions, feel free to reach out! 🚀  
