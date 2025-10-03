# 📊 ML Assignment 1 – Data Preprocessing  

## 📌 Objective  
The main objective of this project is to design and implement a robust **data preprocessing system** that addresses common challenges such as:  
- Missing values  
- Outliers  
- Inconsistent formatting  
- Noise in data  

By performing effective preprocessing, the quality, reliability, and usefulness of the data for **Machine Learning models** is enhanced.  

---

## 📂 Dataset  
The dataset used in this project can be accessed from the given [Google Drive link](https://drive.google.com/file/d/1F3lRf32JM8ejnXq-Cbf9y7fa57zSHGz_/view?usp=sharing).  

---

## ⚡ Steps Performed  

### 1. Data Exploration ✅  
- Explored dataset and checked info & structure.  
- Listed down unique values in each feature with their counts.  
- Performed statistical analysis.  
- Renamed columns for consistency.  

### 2. Data Cleaning ✅  
- Detected and handled **missing values**.  
- Replaced age = 0 with NaN and filled missing values with mean/median/mode.  
- Removed duplicate rows.  
- Identified **outliers** using IQR method.  

### 3. Data Analysis ✅  
- Filtered dataset with **Age > 40** and **Salary < 5000**.  
- Plotted **Age vs Salary** scatter plot.  
- Counted number of people from each place and visualized it.  

### 4. Data Encoding ✅  
- Converted categorical variables into numerical form using:  
  - Label Encoding  
  - One-Hot Encoding  

### 5. Feature Scaling ✅  
- Applied **StandardScaler** and **MinMaxScaler** for feature scaling.  

---

## 🛠️ Tech Stack  
- **Python**  
- **Pandas, NumPy** – Data handling  
- **Matplotlib, Seaborn** – Visualization  
- **Scikit-learn** – Encoding & Scaling  

---

## 🚀 How to Run  

1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/ml-assignment1-data-preprocessing.git
   cd ml-assignment1-data-preprocessing
