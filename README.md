# 🛍️ Customer Segmentation using K-Means Clustering

This project uses unsupervised Machine Learning (KMeans Clustering) to segment mall customers into distinct groups based on their behavior and demographics. It helps businesses target their marketing strategies effectively.

## 📌 Problem Statement

Businesses want to understand different types of customers based on their:
- Age
- Annual Income
- Spending Score

Customer segmentation enables companies to:
- Identify high-value customers
- Optimize marketing campaigns
- Improve customer satisfaction

## 💡 Solution

We apply the KMeans clustering algorithm on the Mall Customers dataset to group customers into meaningful segments. This allows business analysts and marketing teams to make data-driven decisions.

## 🧰 Tools & Technologies Used

- Python 🐍
- Jupyter Notebook 📓
- pandas – data handling
- matplotlib & seaborn – data visualization
- scikit-learn – KMeans clustering, StandardScaler

## 📁 Dataset

Mall Customers Dataset from Kaggle  
(Contains CustomerID, Gender, Age, Annual Income, Spending Score)

## 🪜 Steps Followed

1. Load and explore the dataset
2. Data preprocessing
   - Dropped CustomerID
   - Converted 'Gender' to numeric
3. Feature selection: Age, Annual Income, Spending Score
4. Feature scaling using StandardScaler
5. Elbow Method to find the optimal number of clusters
6. Applied KMeans clustering (5 clusters)
7. Visualized clusters using:
   - 2D scatter plot
   - 3D scatter plot

## 📊 Result

The algorithm successfully divided the customers into 5 segments:
- High income, high spenders
- Low income, low spenders
- Young age, high spenders, etc.

These insights help businesses focus on the right customer groups.

## 🚀 How to Run

1. Clone this repository
2. Install required libraries:
