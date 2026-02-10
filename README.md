# K-Nearest Neighbors Classification Project

## 1. Project Objective
The goal of this project is to create a model that can accurately predict a "Target Class" based on anonymized feature data.

## 2. Exploratory Data Analysis (EDA)
I started by visualizing the data to check for patterns.

<img width="2065" height="1973" alt="image" src="https://github.com/user-attachments/assets/23ece48c-e388-4fac-86a4-f1f84c95a57b" />

## 3. Data Preprocessing
Since KNN depends on the distance between points, I used `StandardScaler` to normalize the data. Without scaling, larger feature values would unfairly dominate the model.

## 4. Finding the Optimal K (The Elbow Method)
I didn't just guess the value for K. I ran a loop for $K=1$ to $K=40$ and plotted the error rates.

<img width="850" height="535" alt="image" src="https://github.com/user-attachments/assets/77cdc70d-efd9-466e-aa2d-fe06be871075" />

*Observation: The error rate stabilizes around **K=30**.*

## 5. Final Model Performance
Using the optimized K-value, the model achieved an accuracy of approximately **84%**.

<img width="450" height="281" alt="image" src="https://github.com/user-attachments/assets/74a44d48-6469-43b8-b876-8cb96bb535fb" />

---


📅 **Analysis Date:** February 2026 | 🛠️ **Tools:** Python, Pandas, Scikit-learn, Seaborn

👤 **Author:** Omar Alshargawi
