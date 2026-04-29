# DataAnalytics_ML_Project

# 📊 Customer Segmentation using Data Analytics & Machine Learning

## 📌 Project Overview

This project focuses on **customer segmentation** using data analytics and machine learning techniques.
The goal is to analyze customer behavior and group them into meaningful clusters to support **marketing strategies and business decision-making**.

---

## 🎯 Objectives

* Clean and preprocess raw customer data
* Perform exploratory data analysis (EDA)
* Engineer meaningful features
* Reduce data dimensionality using PCA
* Apply clustering algorithms to segment customers
* Identify distinct customer groups for targeted marketing

---

## 📂 Dataset

The dataset used is `marketing_campaign.csv`, which contains:

* Customer demographics (age, income, education, marital status)
* Purchase behavior
* Campaign responses
* Enrollment date

---

## ⚙️ Project Workflow

### 1️⃣ Data Loading

* Imported dataset using Pandas
* Handled missing values

### 2️⃣ Data Preprocessing

* Converted date columns (`Dt_Customer`)
* Created new feature: **Customer_For** (customer loyalty duration)
* Removed outliers (income, age)

### 3️⃣ Feature Engineering

* Transformed categorical variables
* Encoded data using Label Encoding
* Created relevant aggregated features

### 4️⃣ Exploratory Data Analysis (EDA)

* Statistical summaries
* Visualization of key variables
* Distribution and relationship analysis

### 5️⃣ Data Scaling

* Standardized features using **StandardScaler**

### 6️⃣ Dimensionality Reduction

* Applied **PCA (Principal Component Analysis)** to reduce features to 3 dimensions

### 7️⃣ Clustering

* Used **K-Means Clustering**
* Determined optimal number of clusters using **Elbow Method (Yellowbrick)**
* Also explored **Agglomerative Clustering**

### 8️⃣ Visualization

* 2D and 3D cluster visualization
* Customer segmentation interpretation

---

## 🧠 Technologies Used

* Python 🐍
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn
* Yellowbrick
* PCA & Clustering Algorithms

---

## 📈 Results

The model successfully segments customers into distinct groups based on:

* Spending behavior
* Income level
* Engagement with marketing campaigns

These insights can be used to:

* Improve targeting strategies
* Personalize marketing campaigns
* Increase customer retention

