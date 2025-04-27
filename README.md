E-commerce Customer Segmentation & Analysis

This project focuses on understanding customer behavior using E-commerce sales data. It involves data preprocessing, exploratory data analysis (EDA), clustering (K-Means and Hierarchical), and visual insights into customer segments based on demographics, purchase patterns, and preferences.


📁 Dataset
- File:'ecommerce_sales_large.csv'
- Contains information about transactions, customer demographics, product categories, and more.


🔧 Technologies Used
- Python (Pandas, NumPy)
- Visualization: Matplotlib, Seaborn
- Machine Learning: Scikit-learn (KMeans, PCA, Agglomerative Clustering)


📌 Key Steps

1. 🧹 Data Cleaning
- Checked null values and duplicates
- Converted date fields
- Created derived columns: 'Total Spend', 'Age Group'

2. 📊 EDA & Visualizations
- Outlier detection using boxplots
- Region-wise and gender-wise distribution
- Age group spending patterns
- Product category popularity
- Region × Membership Status insights

3. 🎯 Clustering
- One-Hot Encoding and Standard Scaling for preprocessing
- KMeans Clustering
  - Optimal k using Elbow Method & Silhouette Score
  Hierarchical Clustering
  - Dendrogram & silhouette-based k selection

1. 🧠 Dimensionality Reduction
- Used PCA to visualize clusters in 2D

1. 📈 Insights
- Cluster-wise customer analysis
- Behavior based on Region, Payment Methods, and Membership Status



📌 Visual Samples

- Customer distribution across clusters
- Region-wise and payment method preferences
- Spending patterns by age group and membership tier


