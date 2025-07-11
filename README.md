# customer-cluster-ml
Machine learning project for customer segmentation using hierarchical clustering. 
# Customer Segmentation using Machine Learning

This project performs customer segmentation using unsupervised machine learning — specifically, hierarchical clustering — based on customer income and spending behavior.

---

## 🔍 Objective

To analyze customer behavior and divide them into distinct groups (segments) to enable targeted marketing strategies.

---

## 📂 Dataset

- *Source: [Mall_Customers.csv] (standard mall dataset)
- Features Used:
  - `Annual Income (k$)`
  - `Spending Score (1–100)`

---

## 🛠️ Techniques Used

- Exploratory Data Analysis (EDA)
- Outlier removal using IQR
- Data standardization using `StandardScaler`
- Hierarchical Clustering (Ward linkage)
- Silhouette Score Evaluation

---

## 📈 Results

- Optimal number of clusters: 5*
- Clear segmentation based on spending behavior and income
- Example:
  - Cluster 1: High income, high spending → Premium target
  - Cluster 3: Low income, high spending → Deal lovers

---

## 💡 Tools & Libraries

- Python (Pandas, NumPy, Matplotlib, Scikit-learn, SciPy)
- Jupyter Notebook

---

## 📊 Output

You can view the segmentation plot and silhouette analysis in the notebook: `cluster_github.ipynb`

---

## 🚀 Future Work

- Include Age/Gender as features
- Try K-Means and DBSCAN comparison
- Build dashboard with Streamlit

---

## 📧 Contact

If you're interested in applying this analysis to your business or dataset, feel free to reach out.


