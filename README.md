# Customer-Segmentation-using-K-Means-Clustering
Project Overview

Customer segmentation is one of the most important applications of Machine Learning in business analytics. This project uses the K-Means Clustering algorithm to divide customers into different groups based on their purchasing behavior and demographic information.

By identifying similar customers, businesses can create personalized marketing strategies, improve customer satisfaction, and increase sales.

 Objectives
Perform customer segmentation using the K-Means clustering algorithm.
Analyze customer purchasing behavior.
Determine the optimal number of customer groups using the Elbow Method.
Visualize clusters for better business understanding.
Generate meaningful insights from clustered customer data.
 Dataset

The dataset contains customer information such as:

Customer ID
Gender
Age
Annual Income
Spending Score

These features are used to identify customers with similar purchasing patterns.

 Technologies Used
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
 Project Workflow
1. Data Loading
Load customer dataset.
Explore the dataset structure.
2. Data Preprocessing
Handle missing values (if any).
Select important features.
Normalize data when required.
3. Exploratory Data Analysis (EDA)

Visualizations include:

Distribution of Age
Distribution of Annual Income
Distribution of Spending Score

4. Finding Optimal Number of Clusters

The Elbow Method is used to determine the best value of K.

Computation:

Calculate Within Cluster Sum of Squares (WCSS)
Plot WCSS vs Number of Clusters
Select optimal K where the curve bends
5. Applying K-Means Clustering
Initialize K clusters.
Train the K-Means model.
Assign each customer to the nearest centroid.
Update centroids until convergence.
6. Cluster Visualization

The project visualizes customer clusters using scatter plots where:

Different colors represent different customer groups.
Cluster centroids are highlighted.
Easy interpretation of customer segments.
📈 Visualizations Included
📊 Elbow Method Graph
📉 Customer Cluster Scatter Plot
📊 Age Distribution
📊 Annual Income Distribution
📊 Spending Score Distribution

 Computations Performed
Data Cleaning
Feature Selection
WCSS Calculation
Euclidean Distance Calculation
Cluster Assignment
Centroid Update
Cluster Label Prediction
 Business Insights

The clustering model helps identify different customer segments such as:

 High Income – High Spending Customers
 High Income – Low Spending Customers
 Average Income – Average Spending Customers
 Low Income – High Spending Customers
 Low Income – Low Spending Customers

These insights can help businesses:

Design personalized marketing campaigns
Improve customer retention
Recommend products more effectively
Increase overall revenue
Results
Successfully segmented customers into meaningful groups.
Identified the optimal number of clusters using the Elbow Method.
Visualized customer behavior through cluster plots.
Generated actionable business insights for targeted marketing.
Future Improvements
Apply DBSCAN and Hierarchical Clustering for comparison.
Use Principal Component Analysis (PCA) for dimensionality reduction.
Build an interactive dashboard using Streamlit.
Deploy the project as a web application.
Perform customer segmentation on larger real-world datasets.
Sample Outputs
Customer Cluster Plot
Elbow Method Graph
Correlation Heatmap
Feature Distribution Graphs

(Add screenshots of your generated graphs here.)

📁 Project Structure
Customer-Segmentation/
│── dataset/
│   └── Mall_Customers.csv
│
│── images/
│   ├── elbow_method.png
│   ├── customer_clusters.png
│  
│
│── customer_segmentation.ipynb
│── requirements.txt
│── README.md



Key Learnings
Unsupervised Machine Learning
K-Means Clustering
Data Preprocessing
Feature Engineering
Exploratory Data Analysis
Data Visualization
Cluster Evaluation
Business Intelligence


 How to Run

1. Clone the repository

```bash
git clone https://github.com/Sushila-Meena/Customer-Segmentation-using-K-Means-Clustering.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook

```bash
jupyter notebook
```

or open directly in **Google Colab**.

 Conclusion

This project demonstrates how K-Means Clustering can effectively segment customers based on their purchasing behavior. The generated clusters provide valuable insights that can help businesses make data-driven marketing decisions, improve customer engagement, and optimize resource allocation.
