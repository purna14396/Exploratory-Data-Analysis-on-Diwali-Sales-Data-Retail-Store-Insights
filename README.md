
# 🪔 Diwali Sales Analysis – Retail Store EDA

This project presents an **Exploratory Data Analysis (EDA)** of a retail store’s **Diwali sales data** to uncover valuable business insights about customer behavior, sales performance, and product preferences.

## 📘 View Full Notebook on Kaggle

You can explore the complete analysis and visualizations in the interactive Kaggle notebook:

🔗 **[Exploratory Data Analysis on Diwali Sales Data – View on Kaggle](https://www.kaggle.com/code/purna14396/exploratory-data-analysis-on-diwali-sales-data)**

---

## 📌 Objective

The primary goal of this project is to analyze customer demographics and purchasing patterns during the Diwali festival season to help the business:
- Understand customer demographics to better tailor promotions.

- Analyze regional sales patterns to improve inventory distribution.

- Identify high-revenue product categories for stocking and bundling strategies.

- Compare gender-wise and marital status-wise performance to fine-tune ad targeting.

- Evaluate the impact of occupation and age group on purchasing behavior.

- Uncover seasonal trends in consumer demand during festive periods.

- Detect low-engagement segments for re-engagement campaigns.

- Support business decision-making through data-driven insights.

---

## 📂 Dataset Description
🔗 **[Click here to view/download the dataset](https://www.kaggle.com/datasets/prajwal6362venom/diwali-sales)**

The dataset includes customer purchase data during Diwali season from a retail store.  
Key columns:
- `Gender`
- `Age`
- `Marital_Status`
- `State`
- `Occupation`
- `Product_Category`
- `Amount`

---

## 🧹 Data Preprocessing

To ensure the data is clean and ready for analysis, the following preprocessing steps were performed:

- 🔍 **Null values check and removal**: Rows with missing values were identified and dropped to prevent skewed insights.
- 🧼 **Removed irrelevant columns**: Columns like `'User_ID'` and `'Product_ID'` were dropped as they had no analytical significance.
- 🧹 **Corrected data types**: Ensured all columns (e.g., `Amount`) had the appropriate data type for numerical analysis.
- 🧾 **Duplicate checks**: Verified and dropped any duplicate records to maintain data integrity.
- 🔢 **Standardized column values**: Cleaned inconsistencies in text data such as capitalization or whitespace.
- 📊 **Filtered non-purchase records**: Ensured that only transactions with positive amounts were retained.

These steps helped enhance the quality of insights derived in the analysis that followed.


## 📊 Key Insights

### 🎯 Customer Demographics

- **Majority of customers** are **females** (7,832 vs 3,407 males).
![Image](https://github.com/user-attachments/assets/fbe65218-4bd7-4fc2-aa5b-ad5708494db6)
- **Unmarried individuals** are more frequent buyers (6,518 vs 4,721 married).
![Image](https://github.com/user-attachments/assets/1863ca7d-939a-44a6-83fb-556c4cb63f3e)
- The **26–35 age group** is the most active, generating ₹4.26 Cr in revenue.
![Image](https://github.com/user-attachments/assets/3caffc76-b53e-4cc1-96eb-218d1dc626c9)


---

### 🌍 State-wise Insights

![Image](https://github.com/user-attachments/assets/1a0071f9-2a74-469f-af6a-94bab288b986)

- **Top revenue-generating states**: Maharashtra, Uttar Pradesh, Karnataka.
![Image](https://github.com/user-attachments/assets/5491c42c-5ca6-48b1-b141-03a4d27eeb51)
- **Lowest** revenue: Telangana with ₹0.12 Cr.
![Image](https://github.com/user-attachments/assets/d0ce72dc-b150-4332-8924-0a2e7f71e35e)



---

### 🧑‍💼 Occupation Trends

- **IT professionals** top the list with ₹1.48 Cr in revenue.
- **Agriculture sector** contributes the least at ₹0.26 Cr.
![Image](https://github.com/user-attachments/assets/d2c782a5-bbdf-47dd-9434-d3d4c3fcd2fa)


---

### 📦 Product Categories

- **Food**, **Clothing & Apparel**, and **Electronics** lead in order volume and revenue.
![Image](https://github.com/user-attachments/assets/23081e35-71f0-4be5-b670-cc393e4f8e46)
- **Office Supplies** and **Veterinary Products** show minimal sales during Diwali.
![Image](https://github.com/user-attachments/assets/4d9d6360-b78f-48b9-bd66-a0d4d61c8d48)

---

### 💰 Gender-based Revenue

- **Female customers** contribute ₹7.43 Cr in revenue.
- **Male customers** contribute ₹3.19 Cr.

![Image](https://github.com/user-attachments/assets/27cbc5a8-6966-46bb-abe4-1ef787076670)

---

### 💍 Revenue by Marital Status

![Image](https://github.com/user-attachments/assets/dfd9c6ce-803e-4645-b5a2-4f198e106450)

---



### 📦 Product Categories – Revenue

![Image](https://github.com/user-attachments/assets/04f6bdb6-63bc-4dbb-a9c6-7f968f368b5b)

---

### Based on the analysis, the majority of buyers are unmarried people aged 26–35, primarily from Uttar Pradesh, Maharashtra, and Karnataka. They are mostly employed in the IT, Healthcare, and Aviation sectors, and tend to purchase products from the Food, Clothing, and Electronics categories.

## Thank You !

