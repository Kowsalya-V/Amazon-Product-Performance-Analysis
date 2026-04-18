# 📊 Amazon Product Performance Analysis

## 📌 Overview
This project performs **Exploratory Data Analysis (EDA)** on an Amazon product dataset to understand product performance, pricing trends, discounts, ratings, and customer engagement.

The goal is to extract meaningful insights from e-commerce data and identify factors that influence product ratings and sales performance.

---

## 🎯 Objective
- Analyze Amazon product dataset
- Understand relationship between price, discount, and ratings
- Identify top-performing products and categories
- Perform feature engineering for better insights
- Visualize key business metrics

---

## 📂 Dataset Information
- 📊 Source: Kaggle / Amazon product dataset (CSV format)
- 📦 Size: 1465 products
- 🧾 Features: Product details, pricing, ratings, reviews, and metadata

### Key Columns:
- product_id
- product_name
- category
- discounted_price
- actual_price
- discount_percentage
- rating
- rating_count
- review_content
- product_link

---

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## 🧹 Data Cleaning
- Converted price columns by removing ₹ and commas
- Converted percentage values to numeric format
- Handled missing values in rating and rating_count
- Removed duplicate records
- Dropped rows with critical missing values

---

## ⚙️ Feature Engineering
- **Price Difference** = Actual Price - Discounted Price
- **Review Length** = Length of review text
- **Discount Level**:
  - High (≥ 50%)
  - Medium (20%–49%)
  - Low (< 20%)
- **Rating Category**:
  - Good (≥ 4)
  - Average (3–3.9)
  - Poor (< 3)

---

## 📊 Exploratory Data Analysis (EDA)

### 1. Category Analysis
- Average rating per category
- Total review count per category
- Average discount per category

### 2. Price vs Rating
- Relationship between product price and customer rating

### 3. Discount vs Rating
- Impact of discount percentage on rating

### 4. Correlation Analysis
- Correlation heatmap between numeric features

### 5. Top Products
- Most reviewed products
- Highest rated products

### 6. Distribution Analysis
- Rating distribution
- Discount level distribution

### 7. Review Analysis
- Relationship between review length and rating

---

## 📈 Key Insights
- Higher discounts do not always guarantee higher ratings
- Certain categories consistently perform better in ratings
- Most products fall in the "High Discount" segment
- Ratings are mostly concentrated between 4.0–4.5

---

## 📊 Summary Statistics
- ⭐ Average Rating: ~4.09
- 💸 Average Discount: ~47.7%
- 🧾 Total Reviews: 26M+
- 📦 Total Products: 1350 unique products

---

## 📌 Visualizations Included
- Category vs Rating bar chart
- Price vs Rating scatter plot
- Discount vs Rating scatter plot
- Correlation heatmap
- Rating distribution histogram
- Discount level count plot
- Review length analysis

---

## 🚀 Future Improvements
- Sentiment analysis on review text
- Predict rating using machine learning
- Build recommendation system
- Dashboard using Streamlit / Power BI
- Real-time product analytics system

---

## 💡 Key Learning
- Real-world data cleaning from messy e-commerce datasets
- Feature engineering for business insights
- Importance of visual analytics in decision making
- EDA as a foundation for data science projects

---
