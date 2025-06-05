
# E-Commerce Customer Segmentation

This project applies machine learning techniques for customer segmentation using transactional data from an e-commerce platform. The project is structured in three parts:
- **Part 1**: Data Exploration, Data Preprocessing, and Data Cleaning.
- **Part 2**: Feature engineering, scaling, dimensionality reduction, and unsupervised clustering.
- **Part 3**: Supervised classification for predicting customer segments.

## 📊 Problem Statement

The goal is to segment customers based on their purchase behavior using RFM (Recency, Frequency, Monetary) metrics. These segments can then help businesses improve customer targeting, personalize marketing campaigns, and improve overall customer retention strategies.

---

## 📁 Project Structure

- `notebooks/`: Contains Jupyter notebooks with complete analysis and modeling
- `data/`: Raw and processed CSV files (e.g., `ecommerce_data.csv`)
- `images/`: Visualizations and charts
- `requirements.txt`: Python dependencies
- `README.md`: Project overview and instructions

---

## 🔍 Techniques Used

- **EDA & Preprocessing**
  - Handling missing values and duplicates
  - Feature Engineering: RFM Metrics
  - Standardization using `StandardScaler`
  
- **Clustering**
  - KMeans Clustering
  - PCA for dimensionality reduction
  - Elbow method for optimal k

- **Classification**
  - Random Forest
  - Logistic Regression
  - Accuracy, Precision, Recall, F1-score evaluation

---

## 📈 Results

- Identified **4 distinct customer segments** using KMeans
- Achieved **99.7%+ accuracy** using both Logistic Regression and Random Forest
- PCA visualization shows clear separation between customer groups

---

## 🚀 Getting Started

1. Clone the repo:
```bash
git clone https://github.com/yourusername/ecommerce-customer-segmentation.git
cd ecommerce-customer-segmentation
