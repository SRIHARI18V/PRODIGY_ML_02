# PRODIGY_ML_02
# PRODIGY_ML_02
# 📊 Task-02: Customer Segmentation using K-Means Clustering

### ✅ Objective:
Implement a **K-Means Clustering algorithm** to segment customers of a retail store based on their:
- Annual income
- Spending score

This helps businesses group similar customers and better target marketing strategies.

---

### 📂 Dataset:

[Kaggle Customer Segmentation Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

---

### 🧰 Tools & Libraries:
- Python 🐍
- pandas
- scikit-learn (KMeans, StandardScaler)
- matplotlib & seaborn (for visualization)

---

### 🛠️ Steps Performed:
1. Loaded and preprocessed the dataset:
   - Removed duplicates and missing values
   - Renamed columns for ease
   - Selected only relevant features (Annual Income, Spending Score)
2. Scaled the features using StandardScaler.
3. Used the **Elbow Method** to determine optimal number of clusters (K).
4. Applied KMeans clustering algorithm to group customers.
5. Visualized:
   - Elbow curve to choose K
   - Clustered customer groups with centroids using a scatter plot

---

### 📈 Sample Output:

- 🧠 Optimal number of clusters: **5**
- 🎯 Customers grouped into 5 distinct clusters
- 📊 Centroids clearly marked in the plot

---

### 🔍 Business Insight:
- High-income, high-spending group is the most valuable
- Low-income, high-spending group might be risk-takers or brand-loyal
- Segments help in designing targeted promotions

---

This task helped build intuition around **unsupervised learning**, **distance-based clustering**, and **practical customer analysis** using real-world data.
