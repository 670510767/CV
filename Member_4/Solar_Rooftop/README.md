# Solar Rooftop Scout: Industrial Solar Energy Assessment Dashboard

แพลตฟอร์ม Web Dashboard เชิงปฏิสัมพันธ์ (Interactive) สำหรับประเมินศักยภาพการติดตั้งแผงพลังงานแสงอาทิตย์บนหลังคาโรงงานอุตสาหกรรม ระบบนี้ขับเคลื่อนด้วยโมเดล Deep Learning เพื่อพยากรณ์ความเข้มรังสีดวงอาทิตย์เชิงพื้นที่ และประมวลผลร่วมกับพิกัดภูมิศาสตร์ (GIS) เพื่อคำนวณกำลังการผลิตไฟฟ้าแบบ On-Demand

## Live Application Demo
**ทดลองใช้งานระบบ:** [Solar Rooftop Scout Dashboard](https://solarforecasting-f8c2ak6gvrbds4wztxjojr.streamlit.app/)

---

## Key Features & Capabilities

- **On-Demand Spatial Analysis:** 
  รองรับการปักหมุดระบุตำแหน่งโรงงานผ่าน Interactive Map ระบบจะดึงพิกัด ละติจูด-ลองจิจูด ไปประมวลผลสภาพแสงอาทิตย์ในพื้นที่เป้าหมายแบบเรียลไทม์
- **Smart Solar Potential Engine:** 
  คำนวณประเมินกำลังการผลิตติดตั้งสูงสุด (kWp) และพยากรณ์ปริมาณพลังงานไฟฟ้าสะสมรายปี (kWh) โดยอิงตามค่าประสิทธิภาพของระบบ (Performance Ratio - PR) และความผันผวนของแสง
- **Deep Learning Forecasting:** 
  ใช้สถาปัตยกรรม **GRU (Gated Recurrent Unit)** เป็น Core Engine ในการพยากรณ์ข้อมูล Time-Series ของความเข้มรังสีดวงอาทิตย์ล่วงหน้า 12 เดือน เพื่อหาช่วงเวลาที่มีศักยภาพสูงสุด
- **Business-Ready UI/UX:** 
  ออกแบบและปรับแต่งหน้าจอด้วย Custom CSS เน้นความสะอาดตา ข้อมูลถูกสรุปออกมาเป็นตัวเลขสำคัญ (Metrics Card) และกราฟแนวโน้ม (Line Chart) ช่วยให้เจ้าของธุรกิจนำไปประเมินความคุ้มค่า (ROI) ได้ทันที

---

## Technology Stack

**Frontend & Visualization**
- `Streamlit` - Web Application Framework
- `Folium` - Interactive Map
- `Streamlit Charts` - Data Visualization
- `Custom HTML/CSS` - UI Customization

**Machine Learning & Data Processing**
- `PyTorch / TensorFlow` - Deep Learning Framework (GRU Model)
- `Scikit-Learn` - Data Preprocessing (MinMaxScaler)
- `Pandas` & `NumPy` - Data Manipulation

---
