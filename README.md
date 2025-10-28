
# 🧠 Employee Attrition Classification (Machine Learning)

### 📘 Overview

Every organization faces one persistent question — *“Why do employees leave?”*
In this project, I took real HR data and turned it into actionable insights using **machine learning**. The goal was simple but powerful: **predict which employees are most likely to leave**, uncover the key factors behind attrition, and guide data-driven retention strategies.

This project combines **data storytelling**, **predictive analytics**, and **business intelligence** to help organizations retain their top talent and improve workplace satisfaction.


### 🎯 Objective

To develop and compare machine learning models that accurately classify whether an employee will **stay (0)** or **leave (1)**, and to identify the **key drivers** of attrition.

---

### 🧩 Dataset

The dataset used is `HR_comma_sep.csv`, which includes:

* **Satisfaction level**
* **Last evaluation**
* **Number of projects**
* **Average monthly hours**
* **Years spent in the company**
* **Work accident & promotions**
* **Department & salary level**

This data represents over **14,999 employees**, giving a broad view of workforce behavior.

---

### ⚙️ Machine Learning Models

Six models were trained and tested using Scikit-learn:

* Naive Bayes
* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)

Each model was evaluated on **accuracy**, **precision**, **recall**, **F₁**, and **F₂** scores to find the most reliable predictor.

---

### 📊 Model Performance Summary

| Model               | Accuracy (%) | Precision (%) | Recall (%) | F₁ (%)    | Remark               |
| ------------------- | ------------ | ------------- | ---------- | --------- | -------------------- |
| Random Forest       | **99.09**    | **99.09**     | **99.09**  | **99.08** | Best performer       |
| KNN                 | 94.02        | 94.40         | 94.02      | 94.13     | Stable and accurate  |
| SVM                 | 93.00        | 93.36         | 93.00      | 92.60     | Balanced performance |
| Decision Tree       | 85.62        | 86.10         | 85.62      | 83.70     | Moderate             |
| Logistic Regression | 79.29        | 77.08         | 79.29      | 77.14     | Acceptable baseline  |
| Naive Bayes         | 71.24        | 80.24         | 71.24      | 73.35     | Weakest              |

---

### 📈 Key Findings & Insights

* Employees who **worked longer hours (207 vs 199)** and had **lower satisfaction (0.44 vs 0.67)** were more likely to leave.
* Attrition was **highest among low-salary employees (2,172 left)**.
* **Sales and Technical departments** recorded the highest turnover.
* The data showed **class imbalance** — most employees stayed (76%) while 24% left.

These insights show that **employee satisfaction, workload, and compensation** are strong predictors of turnover.

---

### 🚀 Results Achieved

After model comparison and fine-tuning:

* The **Random Forest Classifier** emerged as the most accurate model, achieving **99.09% accuracy**.
* The model can now **predict potential attrition cases** with near-perfect precision.
* The findings can guide HR teams to **optimize work hours**, **adjust pay scales**, and **design better retention policies**.

This predictive framework transforms HR data into a **strategic decision-making tool** — empowering businesses to act before losing key employees.

---

### 🧰 Tech Stack

* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* **Tools:** Jupyter Notebook, Power BI (for visualization)
* **Techniques:** Feature Encoding, Model Comparison, Evaluation Metrics, Feature Importance


### 🧠 About the Author

**Danjuma Kabiru**
Data Analyst | Business Intelligence | Data Scientist
📍 Lagos, Nigeria

* 💼 Skilled in Python, Power BI, Excel, SQL, and Machine Learning
* 🌍 Passionate about using data to solve business and social problems
* 🔗 [LinkedIn](#) | [Email](#)

---

### 🏁 Final Thoughts

This project demonstrates how data, when modeled intelligently, can uncover the hidden heartbeat of an organization.
**Predicting attrition isn’t just about numbers — it’s about understanding people.**appealing* when uploaded?

