# 📱 Smartphone Price Analysis – Exploratory Data Analysis (EDA) Project

This project explores how various smartphone features such as RAM, storage, processor speed, 5G support, fast charging, and brand influence pricing in the Indian smartphone market.

Using Python and visual analytics, I performed a detailed exploratory data analysis (EDA) to identify price trends, feature impact, and product segmentation across brands.

---

## 📁 Dataset Overview

- The dataset contains detailed specifications of smartphones available in India.
- Key columns include:  
  `price`, `ram_capacity`, `internal_memory`, `processor_speed`, `battery_capacity`, `primary_camera_rear`, `num_cores`, `has_5g`, `fast_charging`, `brand_name`, and more.
- The goal was to understand **which features most strongly influence smartphone prices** and how brands position their models.

---

## 🔧 Project Workflow

1. **Objective Definition**  
   → Identify price-influencing features and market trends using smartphone specs

2. **Data Loading & Inspection**  
   → Imported CSV file, explored columns, data types, summary stats, and missing values

3. **Data Cleaning & Preprocessing**  
   - Handled missing values using median/mode imputation
   - Removed irrelevant columns (e.g., `ratings`, `extended_upto`)
   - Renamed and corrected column types for clarity

4. **Feature Selection & Transformation**  
   → Selected relevant features like RAM, ROM, processor speed, etc., and converted types for analysis

5. **EDA & Visualization**  
   - Bar plots for brand distribution  
   - Histogram, KDE plot, and boxplot for price distribution  
   - Scatter plots and boxplots to explore feature-price relationships  
   - Heatmap for correlation between numeric features

6. **Insight Generation & Final Recommendations**

---

## 📊 Key Insights

- **RAM and Internal Storage** are the strongest price drivers — phones with 6GB+ RAM and 128GB+ storage are consistently more expensive.
- **Processor Speed** has a positive influence on price — faster phones are priced higher.
- **5G and Fast Charging** support are premium features — smartphones with these show higher median prices.
- **Camera Megapixels** and **Battery Capacity** don’t significantly influence price — many budget phones offer competitive specs in these areas.
- **Brand Distribution** is dominated by Xiaomi, Samsung, and Realme, indicating heavy mid-range market competition.

---

## 💡 Final Recommendations

- 📌 Focus new smartphone models around **₹15K–₹25K** — the most active price segment.
- ⚡ Ensure **5G and fast charging** support even in mid-range devices to increase perceived value.
- 💾 Prioritize **6GB+ RAM and 128GB+ storage** — these are strong selling points.
- 🔋 Avoid overinvesting in camera megapixels or large batteries — they don’t guarantee higher pricing.
- 🧠 Brands should differentiate through software experience and performance rather than just hardware specs.

---

## 🛠️ Tools Used

- **Python**: Numpy, Pandas, Matplotlib, Seaborn
- **Jupyter Notebook**
- **Machine Learning**


---




