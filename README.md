# Email-Marketing-EDA
Exploratory Data Analysis (EDA) of an Email Marketing dataset using Python
## 🎯 Objective
To analyze customer enrollment and engagement data from an email marketing campaign to uncover trends in demographics, participation status, and data quality. The goal is to clean inconsistent data, handle missing values, and visualize key insights that can help optimize marketing strategies.

---

## 📂 Dataset Overview
The dataset contains customer records from an email marketing campaign, including:
- **City, State, PostalCode** – Geographical information  
- **GenderCode, MaritalStatus, BirthDate** – Demographics  
- **Status, Type, Enrolled_on** – Campaign and enrollment details
- https://github.com/madhan-mech/Email-Marketing-EDA/blob/main/Email%20Marketing%20Analysis.xlsx

> *Note: The dataset was provided by a trainer and is not publicly available on Kaggle.*

---

## 🧹 Data Cleaning & Preparation
Performed several data preprocessing steps using **pandas** and **NumPy**:
- Renamed inconsistent columns (`Enrolled on` → `Enrolled_on`)
- Fixed typos and inconsistent cases in `City`, `State`, and `Status`
- Replaced missing values in **GenderCode** with the mode
- Dropped unnecessary columns (`Column1`)
- Standardized city names (e.g., “BANGLORE”, “Bangalore” → “BANGALORE”)
- Replaced non-standard entries like `"Not Mention"` with `"NA"`
- https://github.com/madhan-mech/Email-Marketing-EDA/blob/main/Email%20marketing%20Project.ipynb

---

## 📊 Exploratory Data Analysis (EDA)
Conducted a detailed EDA using **Matplotlib** and **Seaborn**:
- Gender and marital status distribution  
- City-wise and state-wise participant counts  
- Enrollment activity by campaign type and status  
- Identification of missing or inconsistent data patterns  

---

## 📈 Visualizations
Some key visualizations created:
- Bar charts for gender, marital status, and state distribution  
- Countplots showing active vs inactive participants  
- City-level participation comparison  
- Correlation and categorical analysis for understanding engagement trends  

---

## 🧠 Key Insights
- Majority of participants were from major cities like **Hyderabad** and **Bangalore**  
- Data inconsistencies were observed due to mixed cases and typos in categorical columns  
- The **Active** status category dominated, indicating good engagement  
- **Married** participants were significantly higher in number  

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn  
- **Environment:** Jupyter Notebook  

---

## 🧩 Skills Demonstrated
- Data Cleaning and Preprocessing  
- Exploratory Data Analysis (EDA)  
- Handling Missing and Inconsistent Data  
- Visualization and Insight Generation  

---

## 📄 Results
Successfully cleaned and analyzed the dataset, ensuring high-quality insights into customer engagement patterns. This project highlights proficiency in Python-based data analysis and storytelling through visualization.

---


