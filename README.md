# Mall Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project performs **customer segmentation** using **K-Means Clustering**, an unsupervised machine learning algorithm.

The goal is to group mall customers into different segments based on their:

* Age
* Annual Income
* Spending Score

Customer segmentation can help understand different groups of customers based on their characteristics and spending behavior.

## 🎯 Objectives

* Load and explore the mall customer dataset.
* Select important customer features.
* Standardize the features using `StandardScaler`.
* Determine the suitable number of clusters using the **Elbow Method**.
* Apply **K-Means Clustering**.
* Visualize the customer segments.
* Use **PCA** to visualize the clusters in two dimensions.

## 📂 Dataset

The dataset contains the following columns:

| Column            | Description                   |
| ----------------- | ----------------------------- |
| `customerID`      | Unique customer ID            |
| `Age`             | Age of the customer           |
| `Annual_Income_k` | Annual income of the customer |
| `spending_score`  | Customer spending score       |

The dataset contains **20 customer records**.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## 🤖 Machine Learning Algorithm

### K-Means Clustering

K-Means is an unsupervised machine learning algorithm that divides data into a specified number of clusters.

In this project:

1. Customer data is loaded using Pandas.
2. Age, Annual Income, and Spending Score are selected.
3. The features are standardized using `StandardScaler`.
4. The Elbow Method is used to examine different values of K.
5. K-Means is applied with **5 clusters**.
6. Each customer is assigned to a cluster.
7. The clusters are visualized using scatter plots.
8. PCA is used to represent the clusters in two dimensions.

## 📊 Elbow Method

The Elbow Method is used to analyze the relationship between the number of clusters and the model's inertia.

The project tests values of **K from 1 to 10**.

The resulting plot helps identify a suitable number of clusters.

## 📈 Customer Segmentation

After selecting 5 clusters, K-Means assigns every customer to one of the five clusters.

A scatter plot is created using:

* X-axis: Annual Income
* Y-axis: Spending Score
* Color: Customer Cluster

## 🔍 PCA Visualization

Principal Component Analysis (PCA) is used to reduce the standardized three-dimensional feature space into two principal components.

This allows the customer clusters to be visualized in a 2D plot.

## 📁 Project Files

```text
mall-customer-segmentation/
│
├── mall_customers (1).ipynb   # Jupyter Notebook
├── mall_customers.csv         # Customer dataset
├── README.md                  # Project documentation
└── requirements.txt           # Required Python libraries
```

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/mall-customer-segmentation.git
```

### 2. Open the project folder

```bash
cd mall-customer-segmentation
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Open the Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
mall_customers (1).ipynb
```

and run the cells.

## 📦 Requirements

Create a file named `requirements.txt` with:

```text
pandas
scikit-learn
matplotlib
seaborn
jupyter
```

## 💡 Key Learning Outcomes

Through this project, I learned:

* Data loading and preprocessing using Pandas
* Feature scaling using StandardScaler
* Unsupervised machine learning
* K-Means clustering
* Elbow Method
* Cluster visualization
* Dimensionality reduction using PCA
* Working with Jupyter Notebook

## 👩‍💻 Author

**JEEVA S**

GitHub: `https://github.com/YOUR-USERNAME`

---

⭐ If you find this project useful, feel free to give it a star!
