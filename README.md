# 🔍 CLTV Prediction & Customer Segmentation for Personalized Insurance Policies

A data-driven machine learning project to predict **Customer Lifetime Value (CLTV)** and segment insurance customers for targeted policy personalization. Built for **Vahan Bima**, a motor vehicle insurance company, this project leverages regression and clustering to optimize marketing, improve customer retention, and enhance profitability in the insurance industry.


## 📌 Problem Statement

Traditional insurance marketing often applies a one-size-fits-all approach, leading to inefficient resource allocation and missed opportunities. **Vahan Bima** sought to personalize insurance offerings by:

- Predicting the long-term value (CLTV) of customers
- Segmenting them based on behavioral and demographic data
- Tailoring products and strategies for high-value and under-served segments


## 🎯 Objectives

1. **Predict Customer Lifetime Value (CLTV)** using regression models
2. **Segment customers** based on predicted CLTV and behavioral features using clustering
3. Improve marketing ROI, service personalization, and policy design


## 🛠️ Techniques Used

### 📊 Regression Models for CLTV Prediction
- **Gradient Boosting (Final Model)**  
- Compared with: Linear, Lasso, Ridge, Decision Tree, Random Forest, KNN, Neural Networks

### 📈 Clustering for Customer Segmentation
- **Mini Batch K-Means (Chosen Algorithm)**
- **BIRCH** (for comparison)
- Elbow method for optimal K
- Evaluation: SSE, Davies-Bouldin Index


## 🧪 Results

- 🧠 **CLTV Prediction R² Score (Test Set):** 92.53% (Gradient Boosting)
- 🔍 **Optimal Clusters:** 3
- 💡 **Top Features:** Claim Amount, Vintage, Marital Status
- 📊 Segmentation Insights:
  - Cluster 0: High CLTV & Claim, ideal for premium products
  - Cluster 2: Urban-dominant, silver policy holders
  - Cluster 1: Lower CLTV, cost-conscious customers


## 📂 Project Structure

regression_model.ipynb # CLTV prediction using multiple ML models 
clustering_model.ipynb # Customer segmentation using KMeans & BIRCH 
eda_clusters.ipynb # Exploratory analysis on customer clusters 
cltv.csv # Dataset for CLTV prediction 
cltv_cleaned.csv # Cleaned Dataset for CLTV prediction
cltv_clustered.csv # Dataset after clustering 


## 📊 Key Features in Dataset

- **Demographics**: Gender, Area, Marital Status, Qualification
- **Policy Info**: Policy Type, Income Level, Num Policies
- **Behavioral Metrics**: Vintage (tenure), Claim Amount
- **Target Variable**: Predicted CLTV (monetary value)


## 💡 Use Cases

- 🎯 **Targeted marketing campaigns**
- 🧮 **Premium policy offerings for high-value clusters**
- 🔍 **Personalized communication for improved retention**
- 📈 **Better resource allocation across customer tiers**


## 🔍 Future Work

- Integrate **deep learning** for more dynamic CLTV prediction
- Visualize clusters via **interactive dashboards** (Power BI/Tableau)
- Incorporate **geospatial risk factors** using GIS data
- Scale the system using **Apache Hadoop/Spark** for big data pipelines


## 👨‍💻 Authors

- Shreyas Hingmire  
- Nayan Bhiwapurkar  
- Sudeeksha Vandrangi  
- Vaishnavi Chunchu  
- Toshal Warke  


## 📄 License

This project is open-source and licensed under the MIT License.

