# FinCluster
Segmenting Financial Customers with KMeans and Visual Analytics using python and to visually represent the data in powerBI.
Absolutely! Here's a solid, professional, and well-formatted `README.md` content you can use for your **Customer Segmentation for Financial Products** project.

---

# 🧠 Customer Segmentation for Financial Products  
*Machine Learning meets Finance & Visualization*

---

## 📌 **Project Overview**

This project aims to segment financial customers using **unsupervised machine learning (KMeans Clustering)** and visualize the resulting insights through an **interactive Power BI dashboard**. By analyzing key features like income, credit score, debt-to-income ratio, and risk rating, this project identifies distinct customer groups to support **targeted financial strategies** and product recommendations.

---

## 🎯 **Objectives**
- Segment customers based on financial and demographic features  
- Apply preprocessing techniques: one-hot encoding, scaling, PCA  
- Use the **Elbow Method & Silhouette Score** to find optimal clusters  
- Visualize patterns and KPIs in **Power BI** for business decision-making  
- Demonstrate how **data analysis + machine learning + domain knowledge** can create actionable business value

---

## 💡 **Why This Project Matters**

In the finance industry, understanding customer behavior is essential for:
- Offering the right credit or loan products
- Identifying risk-prone individuals
- Improving customer retention through personalization

This project mirrors what real-world data analysts do at fintechs, banks, and consulting firms — combining **data cleaning, ML modeling, and business reporting** to drive insights.

---

## 🛠️ **Tech Stack & Tools**
- **Python**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Power BI**: Dashboarding, KPI Cards, Donut/Bar Charts
- **Jupyter Notebook**: Data preprocessing and clustering logic
- **Excel/CSV**: Data handling & export

---

## 🧪 **Dataset Overview**
The dataset contains over **6000 records** of anonymized customer financial information with the following key features:
- Age, Education, Employment Status, Marital Status
- Income, Credit Score, Loan Amount
- Risk Rating, Debt-to-Income Ratio, Payment History
- Assets Value, Previous Defaults

---

## 📊 **Key Features of the Dashboard**
- **Segment Distribution** (Donut Chart)
- **Income vs Credit Score** comparison across clusters
- **Average Loan Amount** by customer segment
- **Risk Profile** visualization
- **Card KPIs**: Avg. DTI, Credit Score, Loan Amount, etc.

---

## 🔍 **ML Modeling Approach**
1. Data Cleaning & Null Handling  
2. One-Hot Encoding for categorical features  
3. MinMax Scaling for numerical consistency  
4. KMeans Clustering (optimal K found via Elbow + Silhouette)  
5. PCA used for 2D visualization of clusters  
6. Cluster labels added back to the dataset for Power BI

---

## 📈 **Results**
- Segmented customers into 3 clusters:  
  `Cluster 0` = Low Risk  
  `Cluster 1` = Medium Risk  
  `Cluster 2` = High Risk

These clusters provide insight into how financial institutions can:
- Tailor marketing strategies
- Customize credit offerings
- Identify high-risk applicants early

---

## 🌐 **How to Use**
1. Run the Jupyter Notebook to generate the segmented data
2. Export the data using `to_csv()`
3. Load the cleaned data into Power BI
4. Use provided visuals or build your own from the fields

---

## ✅ **Skills Demonstrated**
- Data Wrangling and Cleaning  
- Exploratory Data Analysis  
- Clustering with KMeans  
- Dimensionality Reduction (PCA)  
- Data Visualization (Python + Power BI)  
- Business Insight Generation

---

## 📁 **Folder Structure**
```
├── notebooks/
│   └── customer_segmentation.ipynb
├── data/
│   └── original_dataset.csv
│   └── clustered_data.csv
├── visuals/
│   └── dashboard_screenshots.png
├── PowerBI/
│   └── customer_dashboard.pbix
└── README.md
```

---

## 🤝 **Credits & Acknowledgments**
Thanks to the open data community and Kaggle for datasets.  
This project was built as a personal learning initiative in **Data Analytics & Financial Consulting**.
