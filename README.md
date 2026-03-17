# 🍞 Bakery Sales & Customer Behavior Analysis
โปรเจกต์วิเคราะห์ข้อมูลการขายและพฤติกรรมลูกค้าของร้านเบเกอรี่ เพื่อการตัดสินใจเชิงธุรกิจ

## 🚀 ข้อมูลโครงการ
- **เครื่องมือที่ใช้:** Excel, Power BI, DAX
- **ชุดข้อมูล:** [The Bread Basket Dataset จาก Kaggle](https://www.kaggle.com/datasets/mittalvasu95/the-bread-basket)
- **ภาษาที่ใช้สรุปงาน:** HTML/CSS (GitHub Pages)

## 📊 สิ่งที่ได้จากโปรเจกต์นี้
1. **Sales Overview:** สรุปยอดขายรวม จำนวนบิล และพฤติกรรมการซื้อ
2. **Product Insights:** วิเคราะห์สินค้าขายดีเพื่อวางแผนสต็อก
3. **Customer Behavior:** เจาะลึกช่วงเวลา Peak Hours และความแตกต่างระหว่างวันธรรมดากับวันหยุด

## 🛠️ สูตร DAX ที่สำคัญ
- `ยอดขายวันหยุด = CALCULATE([จำนวนที่ขายได้], 'Bakery'[DayType] = "Weekend")`
- `เฉลี่ยชิ้นต่อบิล = [จำนวนที่ขายได้] / [จำนวนใบเสร็จทั้งหมด]`

---

