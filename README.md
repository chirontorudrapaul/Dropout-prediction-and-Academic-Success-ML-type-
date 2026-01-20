# Ensemble-Based Machine Learning Strategies for Predicting Student Dropout and Academic Outcomes

## 📌 Overview
Student dropout is a critical challenge for higher education institutions, as it negatively affects academic performance, institutional sustainability, and decision-making processes. Early identification of students who are likely to discontinue their studies allows institutions to design timely and effective intervention strategies.

This repository presents an **ensemble-based machine learning framework** for predicting **student dropout and academic outcomes** using a real-world higher education dataset. The study demonstrates that ensemble learning, particularly a **Stacking Classifier**, can achieve high predictive performance in educational data analytics.

---

## 👥 Authors
- **Chironto Rudra Paul** – Main Author  
- **Arnob Das** – Co-Author  

Department of Computer Science and Engineering  
North East University Bangladesh  

📧 Emails:  
- chirontorudrapaul@gmail.com  
- arnobdas789@gmail.com  

---

## 📊 Dataset Description
The dataset used in this project was collected from a higher education institution and assembled from multiple independent (disjoint) databases. It contains records of undergraduate students enrolled in diverse degree programs, including:
- Agronomy
- Design
- Education
- Nursing
- Journalism
- Management
- Social Services
- Technology-related disciplines

### Data Categories
- **Enrollment-time attributes:** demographic, academic, and socio-economic variables  
- **Academic performance attributes:** student performance at the end of the 1st and 2nd semesters  

### Target Variable
The prediction task is formulated as a **three-class classification problem**:
- Dropout  
- Enrolled  
- Graduate  

For analytical purposes, the task can also be transformed into a **binary classification problem** (Dropout vs Academic Success).

🔗 **Official Dataset (Zenodo):**  
https://zenodo.org/records/5777340

---

## 🧠 Methodology
The proposed approach follows a structured machine learning workflow:
1. Exploratory Data Analysis (EDA) to understand feature distributions and class imbalance  
2. Data preprocessing (handling missing values, categorical encoding, normalization)  
3. Splitting data into training and testing sets  
4. Training multiple supervised learning models  
5. Applying ensemble learning using a **Stacking Classifier**  
6. Evaluating model performance using accuracy and standard classification metrics  

---

## 🤖 Machine Learning Models Used
The following supervised learning algorithms were implemented and evaluated:
- Logistic Regression  
- Decision Tree Classifier  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- Random Forest Classifier  
- **Stacking Classifier (Ensemble Model)**  

The Stacking Classifier combines predictions from multiple base learners to improve generalization and reduce overfitting.

---

## 📈 Results
- **Best Performing Model:** Stacking Classifier  
- **Accuracy Achieved:** **94.50%**

### Predicted Outcome Distribution
- **Dropout Risk:** 63.1%  
- **Academic Success:** 36.9%  

The results confirm that semester-wise academic performance indicators are strong predictors of student outcomes, while demographic and socio-economic factors also contribute to model effectiveness.

---

## 📁 Repository Contents
- `paper.pdf` – Final IEEE-style research article  
- `README.md` – Project overview and documentation  

---

## 🔗 Related Resources
- 📘 **Kaggle Implementation:**  
  https://www.kaggle.com/code/heyboss/student-dropout-prediction-academic-success  

- 📊 **Zenodo Dataset:**  
  https://zenodo.org/records/5777340  

---

## 📚 References
1. Zenodo Dataset, “Predict students’ dropout and academic success.”  
   https://zenodo.org/records/5777340  

2. C. R. Paul, “Student Dropout Prediction and Academic Success,” Kaggle, 2024.  
   https://www.kaggle.com/code/heyboss/student-dropout-prediction-academic-success  

3. V. Tinto, “Dropout from higher education: A theoretical synthesis of recent research,” *Review of Educational Research*, 1975.  
   https://doi.org/10.3102/00346543045001089  

4. C. Romero and S. Ventura, “Educational data mining: A review of the state of the art,” *IEEE Transactions on Systems, Man, and Cybernetics*, 2010.  
   https://ieeexplore.ieee.org/document/5432695  

---

## 📄 License
This repository is intended for **academic and research purposes only**.
