# Comparative Analysis of Artificial Neural Networks and Machine Learning Models for Predicting Pulmonary Tuberculosis Treatment Outcomes

โปรเจกต์พัฒนาระบบและเปรียบเทียบประสิทธิภาพของโมเดลในการพยากรณ์ผลการรักษาวัณโรคปอด (Pulmonary Tuberculosis) โดยมุ่งเน้นการทดสอบเชิงเปรียบเทียบระหว่าง **Artificial Neural Networks (ANN)** และ **Machine Learning (RF, XGBoost, CatBoost)** เพื่อค้นหาโมเดลที่ตอบโจทย์และให้ผลลัพธ์ดีที่สุด ก่อนนำมาต่อยอดใช้งานผ่าน Web Application

---

## Key Highlights & Workflow

* **Model Benchmarking:** ทดลองและเปรียบเทียบประสิทธิภาพของ 4 อัลกอริทึมหลัก ได้แก่ **ANN, Random Forest, XGBoost และ CatBoost** ในการจำแนกผลการรักษาออกเป็นกลุ่มพึงประสงค์ และ ไม่พึงประสงค์ (Favorable vs Unfavorable Outcome)
* **Performance Evaluation:** ประเมินผลโมเดลอย่างถี่ถ้วนด้วยตัววัดผลทางสถิติที่หลากหลาย (Accuracy, Precision, Recall, F1-Score, ROC-AUC) เพื่อวิเคราะห์จุดแข็งของแต่ละโมเดล จนพบว่า **XGBoost** มีประสิทธิภาพโดดเด่นและเสถียรที่สุด
* **System Extension:** นำโมเดล XGBoost มาพัฒนาต่อยอดให้ใช้งานได้จริง ผ่านการสร้าง Interactive Web Application ด้วย **Streamlit**

---

## Tech Stack & Capabilities

* **Core Focus:** Binary Classification, Model Evaluation, Performance Benchmarking
* **ML / DL Tools:** XGBoost, CatBoost, Scikit-Learn, PyTorch / TensorFlow
* **Data Processing:** Pandas, NumPy, Matplotlib, Seaborn
* **Deployment:** Streamlit (Python)

---

## Repository Link

[GitHub Repository](https://github.com/yeoauqt/TB_Clustering)
