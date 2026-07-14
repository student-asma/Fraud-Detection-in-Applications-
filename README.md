# Fraud Detection in Internship Applications Using Machine Learning

> **Task 3 – Data Analytics Virtual Internship at Internee.pk**

## 📌 Project Overview

This project was completed as **Task 3** during my **Data Analytics Virtual Internship at Internee.pk**.

The objective of this project is to identify suspicious internship applications by detecting anomalies in applicant behavior using Machine Learning techniques. The system analyzes application data to uncover patterns that may indicate fraudulent or duplicate submissions.

---

## 🎯 Project Objective

The primary objectives of this project are:

- Detect fraudulent internship applications
- Identify duplicate records and suspicious behaviors
- Analyze applicant patterns using Machine Learning
- Improve the internship application verification process
- Support recruiters in making better hiring decisions

---

## 📂 Dataset Information

The dataset consists of **500 internship applications** containing applicant information such as:

- Application ID
- Applicant Name
- Email
- Phone Number
- CNIC
- Age
- Gender
- University
- Degree
- CGPA
- Experience Years
- Skills
- City
- IP Address
- Device ID
- Submission Date
- Submission Time
- Submission Duration
- Resume Uploaded
- Email Verified
- Phone Verified
- Internship Position

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 🤖 Machine Learning Algorithms

### Isolation Forest

Isolation Forest is an unsupervised anomaly detection algorithm used to identify suspicious internship applications based on unusual applicant behavior.

### K-Means Clustering

K-Means Clustering groups similar internship applications into clusters, helping identify groups with a higher concentration of suspicious records.

---

## 📊 Project Workflow

1. Data Collection
2. Data Cleaning
3. Missing Value Analysis
4. Duplicate Record Detection
5. Exploratory Data Analysis (EDA)
6. Fraud Indicator Analysis
7. Feature Selection
8. Label Encoding
9. Feature Scaling
10. Isolation Forest Model
11. Fraud Detection
12. K-Means Clustering
13. Cluster Analysis
14. Model Evaluation
15. Business Insights
16. Business Recommendations

---

## 🔍 Fraud Indicators Analyzed

✔ Duplicate Records

✔ Duplicate Email Addresses

✔ Duplicate Phone Numbers

✔ Duplicate IP Addresses

✔ Duplicate Device IDs

✔ Rapid Submission Behavior

---

## 📈 Model Performance

| Metric | Value |
|---------|-------|
| Accuracy | **82.2%** |
| Precision (Fraud) | **0.62** |
| Recall (Fraud) | **0.31** |
| F1-Score (Fraud) | **0.41** |

---

## 📊 Key Findings

- Successfully detected suspicious internship applications.
- Identified duplicate email addresses, phone numbers, IP addresses, and Device IDs.
- Detected rapid submission patterns indicating possible automated applications.
- Isolation Forest detected anomalous applications with **82.2% accuracy**.
- K-Means Clustering grouped applicants based on similar behavioral patterns.

---

## 💼 Business Recommendations

- Implement Multi-Factor Authentication (MFA).
- Restrict multiple applications from the same IP Address.
- Monitor repeated Device IDs and Email Addresses.
- Introduce CAPTCHA for application forms.
- Develop a Real-Time Fraud Monitoring Dashboard.
- Retrain the Machine Learning model with newly collected data.

---

## 📌 Future Improvements

- Apply advanced anomaly detection algorithms such as:
  - Local Outlier Factor (LOF)
  - One-Class SVM
  - Autoencoders
- Collect larger datasets.
- Integrate with HR Management Systems.
- Build an interactive Power BI Dashboard.
- Deploy the model as a real-time fraud detection application.

---
## 📁 Project Structure

```text
Fraud-Detection-in-Internship-Applications/
│
├── Dataset/
│   └── Internship_Applications.csv
│
├── Notebook/
│   └── Fraud_Detection.ipynb
│
├── Images/
│   ├── Thumbnail.png
│   ├── EDA.png
│   ├── Isolation_Forest.png
│   ├── KMeans.png
│   └── Confusion_Matrix.png
│
├── requirements.txt
│
├── README.md
│
└── LICENSE
```

---

## 👩‍💻 Author

**Asma Yousaf**

Aspiring Data Analyst | Machine Learning Enthusiast | Frontend Developer

### Connect with Me

- 💼 LinkedIn: https://www.linkedin.com/in/asma-yousaf-b3a40534b/
- 💻 GitHub: https://github.com/student-asma/

---

## 🙏 Acknowledgement

This project was completed as part of the **Data Analytics Virtual Internship at Internee.pk**.

I sincerely thank **Internee.pk** for providing practical, project-based learning opportunities that enhanced my skills in Data Analytics and Machine Learning through real-world projects.

---

## ⭐ Support

If you found this project helpful, consider giving it a **Star ⭐** on GitHub.
