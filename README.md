# Mall-Customer-Segmentation

This project demonstrates customer segmentation using K-Means Clustering on a mall customer dataset. By analyzing customer behavior based on age, income, and spending score, we aim to divide them into distinct groups for targeted marketing strategies.

## 📊 Project Description

The notebook performs Exploratory Data Analysis (EDA) and clustering on the *Mall_Customers.csv* dataset using Python libraries like pandas, seaborn, and scikit-learn. The core objective is to segment customers into clusters to identify patterns in consumer behavior and help the mall develop data-driven marketing strategies.

---

## 📁 Dataset

- *Source*: Mall_Customers.csv
- *Features*:
  - CustomerID
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1-100)

---

## 🧰 Technologies Used

- Python
- Pandas
- Matplotlib & Seaborn
- Scikit-learn (KMeans)

---

## 🧪 Steps Performed

1. *Data Loading & Preprocessing*
   - Read and explore the CSV dataset.
   - Removed irrelevant columns and handled basic formatting.

2. *Exploratory Data Analysis*
   - Visualizations using histograms, KDE plots, scatter plots, and heatmaps.
   - Gender-wise distribution analysis.
   - Correlation heatmaps.

3. *Clustering*
   - Univariate, Bivariate, and Multivariate clustering using KMeans.
   - Optimal number of clusters determined using the Elbow Method.
   - Cluster labels added to the original dataframe.
   - Group-wise cluster analysis for business insights.

---

## 🔍 Results

- Identified customer groups based on:
  - Income only
  - Income + Spending score
  - Age + Income + Spending score
- Insights gained for targeted promotions and personalized campaigns.

---

## ▶ How to Run

1. Clone the repository or download the notebook.
2. Upload the notebook to [Google Colab](https://colab.research.google.com/).
3. Upload the Mall_Customers.csv file when prompted.
4. Run all cells sequentially to see outputs and visualizations.

---

## 📌 Author

*Nishchal Dagar*  
B.Tech CSE | Data Science Enthusiast  

---

## 📜 License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).
