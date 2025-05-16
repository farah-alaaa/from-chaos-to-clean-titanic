# from-chaos-to-clean-titanic

This project involves cleaning and exploring the Titanic dataset to prepare it for analysis or modeling. The steps include handling missing data, removing outliers, extracting meaningful features, and normalizing values.

---

## 🔍 Project Goals

- Clean messy and inconsistent data
- Handle missing values and outliers
- Perform feature extraction (e.g., titles from names)
- Normalize and standardize data for machine learning

---
### 🧼 Key Cleaning Steps

- Filled missing values in Age and Fare using the median
- Created Has_Cabin as a binary feature and filled missing Cabin with "Unknown"
- Removed duplicate rows to prevent data bias
- Standardized text (e.g., Sex, Embarked) to lowercase
- Rounded Age to the nearest integer for simpler analysis
- Dropped irrelevant columns: PassengerId, Ticket, and Cabin
- Detected outliers using the IQR method and visualized with boxplots
- Extracted Title from Name to capture social status
- Cleaned and reformatted names into a new Cleaned_Name column

---
#### 📂 Project Structure

Titanic_Data_Cleaning_and_Exploration/
│
├── data/
│   └── train.csv
│
├── notebooks/
│   └── Titanic_Data_Cleaning_and_Exploration.ipynb
│
├── outputs/
│   ├── cleaned_data.csv
│   └── figures/
│       └── *.png (EDA plots)
│
├── requirements.txt
└── README.md
