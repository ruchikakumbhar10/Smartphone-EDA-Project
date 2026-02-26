# 📱 Smartphone Price Analysis – Exploratory Data Analysis (EDA) Project
An in-depth exploratory Data analysis of the Indian Smartphone Market to identify key features influencing price and brand positioning.

---

## 📌 Overview

This project explores how smartphone features such as RAM, Storage, Processor Speed, 5G support, Fast charging, and Brand influence pricing in the Indian Smartphone Market.

Using Python and visual analytics, a detailed Exploratory Data Analysis (EDA) was performed to Identify price trends, feature impact, and Product segmentation across brands.

The goal was to understand which technical specifications most strongly affect smartphone pricing and how brands strategically position their devices.

---

## 🗂️ Project Structure

```
Smartphone-Price-Analysis-EDA/
│
├── Data/
│   └── Smartphones_cleaned_dataset.csv
│
├── Notebook/
│   └── Smartphones_EDA_project.ipynb
│
├── Reports/
│   └── Smartphones_EDA_Analysis_Report.pdf
│
├── Images/
│   └── visualizations.png
│
└── README.md
```

---

## 🎯 Problem Statement

The Indian smartphone market is highly competitive, with brands offering multiple models across different price segments.

The key questions addressed in this project:

- Which smartphone features most strongly influence price?
- Do premium features like 5G and fast charging significantly increase pricing?
- How do brands position their products in the market?
- Is price driven more by performance specs or marketing specs like camera megapixels?

This project answers these questions using structured exploratory data analysis.

---

## 📊 Dataset Description

The dataset contains detailed specifications of smartphones available in India.

### Key Columns Include:

- Price  
- ram_capacity  
- internal_memory  
- processor_speed  
- battery_capacity  
- primary_camera_rear  
- num_cores  
- has_5g  
- fast_charging  
- brand_name  

Each row represents a unique smartphone model.

The dataset includes both numerical and categorical variables, enabling feature-wise comparison and pricing analysis.

---

## 🛠️ Tools and Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🔎 Methods

### 1️⃣ Data Loading & Inspection
- Imported CSV dataset
- Checked columns, datatypes, summary statistics
- Identified missing values

### 2️⃣ Data Cleaning & Preprocessing
- Handled missing values using median/mode imputation
- Removed irrelevant columns (ratings, extended_upto)
- Renamed and corrected column datatypes
- Selected relevant features for analysis

### 3️⃣ Exploratory Data Analysis (EDA)
- Brand distribution analysis using bar plots
- Price distribution using histograms, KDE plots, and boxplots
- Scatter plots to analyze feature-price relationships
- Boxplots to compare pricing categories
- Correlation heatmap for numeric feature relationships

### 4️⃣ Insight Generation
- Identified major price drivers
- Analyzed premium feature impact
- Studied brand positioning strategies

---

## 📊 Key Insights

### 💾 RAM and Internal Storage are the Strongest Price Drivers
Smartphones with 6GB+ RAM and 128GB+ storage consistently have higher prices.

### ⚡ Processor Speed Positively Impacts Price
Higher processor speed correlates with increased smartphone pricing.

### 📶 5G and Fast Charging are Premium Features
Devices offering 5G and fast charging show higher median prices, positioning them as future-ready devices.

### 📷 Camera and Battery Have Limited Pricing Impact
Battery capacity and camera megapixels do not significantly increase price. Many budget devices offer competitive specs in these areas.

### 🏷 Brand Distribution
Xiaomi, Samsung, and Realme dominate the dataset, indicating strong competition in the mid-range segment.

### 💰 Price Distribution
- Majority of smartphones fall between ₹10,000–₹30,000.
- Prices are right-skewed with a few premium outliers above ₹70,000.
- Mid-range pricing dominates the market.

---

## ▶️ How to Run This Project

1. Clone the repository:
```
git clone <your-repository-link>
```

2. Navigate to the project folder:
```
cd Smartphone-Price-Analysis-EDA
```

3. Install required libraries:
```
pip install pandas numpy matplotlib seaborn
```

4. Open Jupyter Notebook:
```
jupyter notebook
```

5. Run `Smartphones_EDA_project.ipynb`

---

## 📈 Results and Conclusion

The analysis shows that:

- Performance specifications (RAM, storage, processor speed) are the strongest pricing determinants.
- Premium features like 5G and fast charging significantly increase perceived value.
- Camera megapixels and battery capacity alone do not justify higher prices.
- The ₹15K–₹25K segment is the most active and competitive price range.

Smartphone pricing is driven more by performance and feature positioning than just hardware quantity.

---

## 🚀 Future Work

- Build a machine learning regression model to predict smartphone prices.
- Perform brand-level clustering analysis.
- Add time-based trend analysis.
- Create an interactive Power BI or Tableau dashboard.
- Conduct feature importance modeling using Random Forest.

---

## 👩‍💻 Author

Ruchika Kumbhar  
Data Analyst | Aspiring Data Scientist  
Python | SQL | Power BI | Machine Learning  

---

## ⭐ Ending Note

This project demonstrates the power of Exploratory Data Analysis in uncovering hidden patterns within real-world datasets. By combining Data Cleaning, Visualization, and Structured Reasoning, Meaningful Business Insights can be generated to support smarter product and pricing decisions.

If you found this project useful, feel free to star the repository!

