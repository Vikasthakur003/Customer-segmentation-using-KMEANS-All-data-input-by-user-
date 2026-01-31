# Customer-segmentation-using-KMEANS-All-data-input-by-user-


we use this project when we have small data and we can input all data in project and then predict the customer behavior according to that data
#  Customer Segmentation using K-Means (Unsupervised Learning)

This project demonstrates an **end-to-end customer segmentation system** using **K-Means clustering**, an unsupervised machine learning algorithm. The goal is to group customers into meaningful segments based on their **Age**, **Annual Income**, and **Spending Behavior**.

This project is beginner–to–intermediate friendly and is suitable for:

* Machine Learning practice
* GitHub portfolio projects
* Interview discussion (unsupervised learning)

---

##  Problem Statement

Businesses often want to understand their customers better so they can:

* Identify **premium customers**
* Detect **low-engagement customers**
* Target **potential customers** with marketing strategies

Since there are **no predefined labels**, this problem is solved using **unsupervised learning**.

---

## What This Project Does

✔ Takes customer data as **user input**
✔ Scales numerical features using **StandardScaler**
✔ Applies **K-Means clustering** to segment customers
✔ Predicts the segment for a **new customer**
✔ Visualizes customer clusters using **Matplotlib**

---

##  Features Used

* **Age** – Customer age
* **Annual Income** – Yearly income
* **Spending Hours** – Spending behavior indicator

---

## 🛠️ Technologies & Libraries

* Python
* Pandas
* Scikit-learn
* Matplotlib

---

##  Project Workflow

1. Take customer data input from the user
2. Store data in a Pandas DataFrame
3. Scale features using `StandardScaler`
4. Train a K-Means model with 3 clusters
5. Predict cluster for a new customer
6. Map clusters to meaningful labels
7. Visualize clusters

---

## 📊 Customer Segments

The clusters are interpreted as:

| Cluster | Customer Type           |
| ------- | ----------------------- |
| 0       | Premium Customer        |
| 1       | Low Segment Customer    |
| 2       | Medium Segment Customer |

---

## 📈 Visualization

A scatter plot is generated showing:

* X-axis → Customer Age
* Y-axis → Annual Income
* Color → Customer Cluster

This helps visually understand how customers are grouped.

---

##  How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/your-username/customer-segmentation-kmeans.git
```

2. Install required libraries

```bash
pip install pandas scikit-learn matplotlib
```

3. Run the Python script

```bash
python customer_segmentation.py
```

4. Enter customer details when prompted

---

##  Learning Outcomes

By working on this project, you will learn:

* How unsupervised learning works
* When to use K-Means clustering
* Feature scaling importance
* Real-world ML project structure
* How to predict clusters for new data

---

##  Author

**Vikas Thakur**
Machine Learning Enginner  

