# Solar Rooftop Scout: Industrial Solar Energy Assessment Dashboard

ระบบเว็บแอปพลิเคชันเชิงปฏิสัมพันธ์ (Interactive Web Dashboard) สำหรับประเมินศักยภาพพลังงานแสงอาทิตย์บนหลังคาโรงงานอุตสาหกรรม โดยนำผลการพยากรณ์ความเข้มรังสีดวงอาทิตย์เชิงพื้นที่ด้วย Deep Learning มาประมวลผลร่วมกับค่าพิกัดภูมิศาสตร์ เพื่อคำนวณกำลังการผลิตและพลังงานไฟฟ้าที่คาดว่าจะผลิตได้จริงแบบทันทีเมื่อระบุพิกัด (On-Demand Processing)

---

## Application & Technical Capabilities

* **Interactive Spatial Analysis:** พัฒนาหน้า Dashboard ด้วย **Streamlit & Folium** รองรับการระบุพิกัดละติจูด-ลองจิจูดของโรงงาน แสดงตำแหน่งพื้นที่เป้าหมายบน Interactive Map พร้อมดึงข้อมูลรังสีแสงอาทิตย์มาประมวลผลคำนวณได้ทันที
* **Solar Potential Calculation Engine:** ระบบคำนวณประเมินกำลังการผลิตติดตั้ง (kWp) และพยากรณ์พลังงานไฟฟ้าสะสมต่อปี (kWh) โดยคำนึงถึงค่า Performance Ratio (PR) และแนวโน้มความเข้มแสงแดดรายเดือน
* **Time-Series Irradiance Forecasting:** ใช้โมเดล **GRU (Gated Recurrent Unit)** เป็น Core Engine ในการพยากรณ์ความเข้มรังสีดวงอาทิตย์ล่วงหน้า 12 เดือน เพื่อช่วยวิเคราะห์ช่วงเดือนที่มีศักยภาพการผลิตไฟฟ้าสูงสุด
* **UI/UX Customization:** ออกแบบหน้าจอด้วย Custom CSS เน้นความสะอาด อ่านง่าย แสดงผลตัวเลขสำคัญ (Metrics Card) และกราฟแนวโน้ม (Line Chart) อย่างเป็นระบบ ช่วยให้ฝั่งธุรกิจหรือเจ้าของโรงงานนำข้อมูลไปวิเคราะห์จุดคุ้มทุน (ROI) ได้ง่ายขึ้น

---

## Tech Stack

* **Frontend / Dashboard:** Streamlit, Folium, Custom HTML/CSS
* **Core Machine Learning:** GRU (PyTorch/TensorFlow), Scikit-Learn (MinMaxScaler), NumPy, Pandas
* **Data Visualization:** Streamlit Charts, Folium Maps

---

## Web Application Demo
[เข้าใช้งาน Solar Rooftop Scout Dashboard](https://solarforecasting-f8c2ak6gvrbds4wztxjojr.streamlit.app)
