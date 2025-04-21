# Customer-Personality-Analysis
Data cleaning and preprocessing of the Customer Personality Analysis dataset from Kaggle. This project includes handling missing values, removing duplicates, standardizing text formats, converting data types, and preparing the data for further analysis or modeling.

---

## 📊 Dataset Features

- **ID**: Unique customer ID  
- **Year_Birth**: Birth year  
- **Education**: Education level  
- **Marital_Status**: Marital status  
- **Income**: Yearly household income  
- **Kidhome / Teenhome**: Number of children and teenagers  
- **Dt_Customer**: Enrollment date  
- **Recency**: Days since last purchase  
- **Products Purchased**: Spend on wine, fruits, meat, fish, sweets, and gold  
- **Promotion Response**: Campaigns accepted  
- **Purchase Channels**: Web, catalog, store, and visits  

---

## 🧹 Data Cleaning Tasks

### ✅ Handled:
- Removed **duplicates**
- Handled **missing values**
- Standardized **categorical values** (like education, marital status)
- Converted **date fields** to datetime format
- Renamed column headers to be **uniform and lowercase**
- Corrected **data types** (e.g., date, numerical)
- Created a new `Age` column from `Year_Birth`

---

## 💡 Tools Used
- Python (Pandas)
- Jupyter Notebook

---

## 📁 Files Included
- `marketing_campaign.xlsx`: Raw dataset
- `cleaning_script.ipynb`: Python script used for cleaning
- `README.md`: Project documentation


