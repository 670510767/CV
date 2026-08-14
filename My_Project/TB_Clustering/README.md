# Comparative Analysis of Artificial Neural Networks and Machine Learning Models for Predicting Pulmonary Tuberculosis Treatment Outcomes

## 📌 Project Overview
This project focuses on developing machine learning models to predict the treatment outcomes of pulmonary tuberculosis (TB) patients in Thailand's Health Region 1 and Chiang Mai province. Utilizing a real-world dataset of over 25,239 records, the system classifies patients into two main categories:

* **Class 0 (Favorable Outcome):** Treatment completed / Cured
* **Class 1 (Unfavorable Outcome):** Died / Defaulted (loss to follow-up) / Drug-resistant / Diagnosis changed / Treatment failed

**Primary Objective:** To proactively detect and classify high-risk patients. This allows public health agencies to take preventative action, allocate medical resources precisely, and ultimately help reduce mortality and transmission rates in alignment with the WHO's **End TB Strategy**.

---

## 🚀 Key Highlights & Workflow

* **Model Benchmarking:** Conducted comparative experiments on four core algorithms—Artificial Neural Networks (ANN), Random Forest, XGBoost, and CatBoost—to accurately classify favorable versus unfavorable treatment outcomes.
* **Performance Evaluation:** Rigorously assessed each model's strengths using diverse statistical metrics, including Accuracy, Precision, Recall, F1-Score, and ROC-AUC. The evaluation revealed that **XGBoost** delivered the most outstanding and stable performance.
* **System Extension & Deployment:** Translated the research into a practical solution by deploying the winning XGBoost model as an interactive web application built with **Streamlit**.

---

## 🧠 Models Evaluated

* **Random Forest:** An ensemble learning method that constructs multiple decision trees and outputs the majority vote (Optimized via Random Search).
* **XGBoost (Extreme Gradient Boosting):** A gradient boosting algorithm that builds trees sequentially to correct previous errors, utilizing built-in regularization to prevent overfitting (Optimized via Random Search).
* **CatBoost (Categorical Boosting):** An algorithm utilizing symmetric trees, making it exceptionally efficient at handling categorical variables without extensive preprocessing (Optimized via Random Search).
* **ANN (Artificial Neural Network):** A deep learning model inspired by the human brain, well-suited for capturing complex, non-linear relationships within the dataset.

---

## 🛠️ Tech Stack & Capabilities

* **Core Focus:** Binary Classification, Model Evaluation, Performance Benchmarking
* **ML / DL Tools:** XGBoost, CatBoost, Scikit-Learn, PyTorch / TensorFlow
* **Data Processing & Visualization:** Pandas, NumPy, Matplotlib, Seaborn
* **Deployment:** Streamlit (Python)

---






เว็บไซต์ต้นแบบระบบพยากรณ์ (Demo System)
เพื่อให้นำไปใช้ประโยชน์ได้จริง คณะผู้วิจัยได้พัฒนาต่อยอดโมเดล XGBoost ไปสู่แพลตฟอร์มออนไลน์ในรูปแบบเว็บไซต์สำหรับประเมินผลลัพธ์การรักษาผู้ป่วยวัณโรคปอด




* **Streamlit App Link:** [TB Clustering Web Application](https://tbclustering-m2seylu2ucciwnzuczpckq.streamlit.app)





https://canva.link/vpday173bvi5wiu
