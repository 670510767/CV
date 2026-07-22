#Medical Data AI Mapping Project (Hybrid Semantic Mapping)

โปรเจกต์พัฒนาระบบ AI สำหรับการจับคู่คำสั่งตรวจทางห้องปฏิบัติการ (Medical Lab Orders) ที่เป็นข้อความอิสระ (Free-text) ให้เข้ากับรหัสมาตรฐานสากล (TMLT และ SNOMED-CT) 

แสดงให้เห็นถึงทักษะขั้นสูงทางด้าน **AI, Machine Learning และ Natural Language Processing (NLP)** ซึ่งสามารถนำมาประยุกต์ใช้กับเทคโนโลยี Fintech ได้ (เช่น การวิเคราะห์ข้อมูลธุรกรรม หรือ Fraud Detection)

### เทคโนโลยีและกระบวนการทำงานที่โดดเด่น:
* **Deep Learning (NLP):** ใช้โมเดล `SapBERT` (ผ่าน Hugging Face/Sentence Transformers) ในการแปลงข้อความทางการแพทย์เป็น Vector (Embeddings) และคำนวณความคล้ายคลึงทางความหมาย (Cosine Similarity)
* **Hybrid Validation:** มีการใช้ Rule-Based Systems ควบคู่กับ LLM (Gemini 1.5 Pro) ในการตรวจสอบผลลัพธ์ที่มีความกำกวม
* **Performance Evaluation:** เขียนสคริปต์เพื่อประเมินความแม่นยำของ AI ด้วยโมเดลสถิติ (Precision, Recall, F1-Score)
* **Language & Tools:** Python, PyTorch, Pandas, Scikit-Learn

**GitHub Repository:** https://github.com/chanidapa14092547/Mapping-Project.git
