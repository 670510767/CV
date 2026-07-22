# Forecasting PM2.5 in Chiang Mai Using Machine Learning & Time Series Model

โปรเจกต์วิเคราะห์และพยากรณ์ค่าฝุ่นละอองขนาดเล็ก (PM2.5) ในพื้นที่จังหวัดเชียงใหม่ โดยเปรียบเทียบประสิทธิภาพของโมเดล Machine Learning และ Time Series เพื่อค้นหาแบบจำลองที่แม่นยำที่สุดสำหรับการคาดการณ์คุณภาพอากาศล่วงหน้า สนับสนุนการเฝ้าระวังด้านสาธารณสุขและการเตรียมรับมือของหน่วยงานที่เกี่ยวข้อง

## Live Dashboard
**เข้าชมผลการวิเคราะห์:** [PM2.5 Forecasting Dashboard (Google Data Studio)](https://datastudio.google.com/reporting/c7bf9f4c-7417-4e49-bc7c-e5394777d006)

---

## Key Features & Objectives

- **Spatial Analysis (วิเคราะห์ระดับอำเภอ):** 
  ประเมินและพยากรณ์ค่าฝุ่น PM2.5 เชิงลึกในพื้นที่ 5 อำเภอหลักของจังหวัดเชียงใหม่ ได้แก่ ฝาง (Fang), ไชยปราการ (Chai Prakan), เวียงแหง (Wiang Haeng), หางดง (Hang Dong) และแม่แจ่ม (Mae Chaem)
- **Multi-Model Comparison (เปรียบเทียบโมเดล):** 
  พัฒนาและประเมินผลแบบจำลองการพยากรณ์ 4 รูปแบบ ได้แก่ `ARIMA`, `Exponential Smoothing`, `XGBoost` และ `Random Forest` เพื่อค้นหาโมเดลที่มีความเสถียรที่สุด
- **High-Accuracy Forecasting:** 
  ผลการทดสอบพบว่าโมเดล **XGBoost (Extreme Gradient Boosting)** มีประสิทธิภาพดีที่สุด โดยให้ค่าความคลาดเคลื่อน (MAPE) ต่ำสุดเมื่อเทียบกับโมเดลอื่นๆ ทำให้เป็นแกนหลัก (Core Model) ที่เหมาะสมที่สุดในการพยากรณ์ PM2.5 ในงานนี้
- **Interactive Dashboard:** 
  นำเสนอผลลัพธ์ข้อมูลผ่าน Google Data Studio (Looker Studio) เพื่อให้แสดงผลข้อมูลได้ชัดเจนและติดตามแนวโน้มฝุ่นละอองได้ง่าย

---

## Methodology & Tech Stack

**Modeling & Algorithms**
- `XGBoost` - Extreme Gradient Boosting (Best Performing Model)
- `Random Forest` - Ensemble Learning
- `ARIMA` - AutoRegressive Integrated Moving Average (Time Series)
- `Exponential Smoothing`

**Tools & Technologies**
- `Google Data Studio (Looker Studio)` - Data Visualization & Dashboard
- `R` - Data Modeling & Machine Learning Training (XGBoost)
- `SPSS` - Time Series Analysis (ARIMA, Exponential Smoothing)

**Evaluation Metrics**
- **MAPE (Mean Absolute Percentage Error):** ใช้เป็นเกณฑ์ในการวัดค่าเปอร์เซ็นต์ความคลาดเคลื่อนเฉลี่ยสัมบูรณ์ของโมเดล โดยคำนวณจากสูตร:
  
$$MAPE=\frac{1}{n}\sum\left|\frac{Y_{true}-Y_{pred}}{Y_{true}}\right|\times100$$

