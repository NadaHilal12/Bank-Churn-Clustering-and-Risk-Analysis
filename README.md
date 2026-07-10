# 🏦 Bank Churn Clustering and Risk Analysis

A Data Mining project that analyzes bank customer behavior using clustering techniques, fuzzy logic, and genetic algorithms to identify customer segments and estimate churn risk.

---

# 📌 Overview

This project presents a complete data mining pipeline for bank customer analysis.

The project includes:

- Data preprocessing
- Data visualization
- Feature engineering
- K-Medoids clustering
- Agglomerative Hierarchical Clustering
- Fuzzy Logic Risk Analysis
- Genetic Algorithm for feature selection
- Customer churn risk evaluation

---

# 📂 Project Structure

```
Bank-Churn-Clustering-and-Risk-Analysis/

├── data/
│   └── Churn_Modelling.csv
│
├── notebooks/
│   └── Bank_Churn_Analysis.ipynb
│
├── images/
│   ├── heatmap.png
│   ├── elbow.png
│   ├── silhouette.png
│   ├── dendrogram.png
│   ├── ga_fitness.png
│   └── fuzzy_system.png
│
└── README.md
```

---

# 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Scikit-Learn-Extra
- Scikit-Fuzzy

---

# 📊 Dataset

The project uses the **Bank Customer Churn Modeling Dataset** containing customer information such as:

- Credit Score
- Geography
- Gender
- Age
- Balance
- Number of Products
- Active Membership
- Estimated Salary
- Churn Status (Exited)

---

# ⚙️ Data Preprocessing

The preprocessing stage includes:

- Removing unnecessary columns
- Missing value checking
- Duplicate removal
- Outlier detection using Boxplots
- IQR Clipping
- Label Encoding
- One-Hot Encoding
- Feature Scaling using StandardScaler

---

# 📈 Data Visualization

The project includes several visualization techniques:

- Boxplots
- Histograms
- Bar Charts
- Scatter Plot
- Correlation Heatmap
- Dendrogram
- Elbow Curve
- Silhouette Score Curve

---

# 🤖 Clustering Techniques

## K-Medoids

- Optimal K selection
- Elbow Method
- Silhouette Score
- Cluster profiling

---

## Agglomerative Hierarchical Clustering

- Ward Linkage
- Dendrogram Analysis
- Cluster Profiling

---

# 🧠 Fuzzy Logic System

A Mamdani Fuzzy Inference System was developed to estimate customer churn risk.

### Inputs

- Customer Age
- Cluster Type
- Active Membership

### Output

- Customer Risk Score

---

# 🧬 Genetic Algorithm

The Genetic Algorithm is used for feature selection.

It includes:

- Population Initialization
- Tournament Selection
- One-Point Crossover
- Bit Flip Mutation
- Fitness Evaluation using Silhouette Score

---

# 📊 Results

The project successfully:

- Identified customer groups
- Compared clustering algorithms
- Improved clustering quality using Genetic Algorithm
- Estimated customer churn risk using Fuzzy Logic

---

# 🚀 Future Improvements

- Apply DBSCAN clustering
- Use PCA for visualization
- Build an interactive dashboard
- Deploy the project as a web application

---

# 👩‍💻 Author

**Nada Hilal**

Faculty of Computer and Data Science

Alexandria National University
