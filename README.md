# Smart Segmentation: Unlocking Customer Personas with AI 🛍️

This repository contains a data science project focused on market basket analysis and customer behavior. By applying unsupervised machine learning techniques, this project identifies distinct customer segments to help businesses tailor their marketing strategies and improve customer retention.

## 📌 Project Overview
The goal of this project is to transform raw transactional data into actionable business intelligence. It utilizes clustering algorithms to group customers based on shared characteristics such as spending habits and annual income, allowing for the creation of targeted "Customer Personas."

## 🚀 Key Features
* **Unsupervised Learning:** Implementation of clustering techniques to discover hidden patterns in customer data without pre-defined labels.
* **Optimal Cluster Identification:** Using the **Elbow Method** to determine the ideal number of clusters for the KMeans algorithm.
* **Hierarchical Clustering:** Creation of **Dendrograms** to visualize the relationship between different customer groups.
* **Multi-Dimensional Visualization:** * 2D plotting with `Seaborn` and `Matplotlib`.
    * Interactive 3D cluster visualization using `Plotly Express`.
* **Feature Scaling:** Standardizing customer attributes to ensure unbiased clustering results.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:**
    * `Scikit-learn`: KMeans clustering and data preprocessing.
    * `Scipy`: Hierarchical clustering and Dendrogram generation.
    * `Plotly Express`: Interactive 3D data exploration.
    * `Pandas` & `NumPy`: Data manipulation and numerical analysis.
    * `Matplotlib` & `Seaborn`: Statistical visualizations.

## 📊 Analysis Workflow
1.  **Data Exploration:** Analyzing distributions of age, income, and spending scores.
2.  **Segmentation Strategy:** Applying **KMeans Clustering** to segment customers based on annual income and spending behavior.
3.  **Hierarchy Analysis:** Using Agglomerative Clustering to understand the nested structure of customer segments.
4.  **Persona Profiling:** Visualizing the resulting clusters (e.g., "High Spenders," "Conservative Earners," "Target Targets").
5.  **Interactive Review:** Utilizing 3D scatter plots to examine the interplay between Age, Income, and Spending Score.

## 📂 Dataset
The project utilizes the **Mall Customer Segmentation** dataset, which includes key consumer attributes:
* **CustomerID:** Unique ID assigned to each customer.
* **Gender:** Male/Female.
* **Age:** Customer age.
* **Annual Income:** Annual income of the customer (k$).
* **Spending Score:** Score assigned by the mall based on customer behavior and spending nature (1-100).

## 📖 How to Use
1.  **Clone the Repo:**
    ```bash
    git clone [https://github.com/your-username/customer-segmentation-clustering.git](https://github.com/your-username/customer-segmentation-clustering.git)
    ```
2.  **Install Dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn plotly scikit-learn scipy
    ```
3.  **Run the Notebook:**
    Open `customer_segmentation_with_clustering.ipynb` in Google Colab or Jupyter Notebook to explore the interactive segments.

---
*Developed as part of a Data Science exploration into Unsupervised Machine Learning and Market Analysis.*
