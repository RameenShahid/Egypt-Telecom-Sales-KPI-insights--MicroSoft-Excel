# 📈 Telecom Egypt KPI Dashboard - Multi-Brand Excel Analysis

This project presents an advanced **interactive Excel dashboard** built to analyze and visualize key sales and operational KPIs for **Telecom Egypt** across **seven major regional brands**. The solution provides deep insights into brand-level performance segmented by product category, region, and achievement against sales targets.

---
## 🧠 Project Overview

**Objective**  
To deliver a dynamic and visual data representation of Telecom Egypt's regional sales performance using Excel dashboards and advanced DAX functions.

**Dashboard Features**
- 📍 Regional store evaluation
- 📶 Product-wise segmentation: Mobile, ADSL, Postpaid, and Fixed
- 📈 Target vs. Achievement breakdown
- 🎯 Interactive slicers for filtering KPIs
- 📌 Centralized overview in the **Main Dashboard**
- 📄 Separate detailed analysis for each region (7 individual sheets)

  ---
## 🧭 Business Context

Telecom Egypt operates across diverse regions with varied performance metrics. This dashboard enables:
- Strategic decision-making at the regional and store level
- Easy tracking of achievement vs. targets across key service lines
- Visual identification of high-performing vs. underperforming areas

---

## 🌐 Brands Covered (Main Dashboard)

The central dashboard gives a consolidated view of the following **seven key brands**:

1. **ميدان الخضروات - المصريين**  
2. **حي الكويت**  
3. **من دمياط - دمينس**  
4. **قنا - جنوب سيناء**  
5. **الزقازيق الشرقي**  
6. **التل الكبير**  
7. **ميدان المنصورة - المصريين**

Each brand/region has a dedicated visual page for deep analysis.

---

- 📊 **KPIs Tracked**:
  - Fixed Line Achievements (Fixed ACH vs TGT)
  - ADSL Achievements (ADSL ACH vs TGT)
  - Postpaid (Post ACH & TGT)
  - Mobile Achievements (ACH & TGT)

---

## 📸 Visuals

### 🔹 Dashboard Previews by Brand

#### 🔸 Sheet 1 & Sheet 2  
<p align="center">
  <img src="https://github.com/RameenShahid/Egypt-Telecom-Sales-KPI-insights--MicroSoft-Excel/blob/220b2ed99d88762747ca708af1ec2f2c0ff6e3df/Visuals/Sheet%201.png?raw=true" width="45%" />
  <img src="https://github.com/RameenShahid/Egypt-Telecom-Sales-KPI-insights--MicroSoft-Excel/blob/220b2ed99d88762747ca708af1ec2f2c0ff6e3df/Visuals/Sheet%202.png?raw=true" width="45%" />
</p>

#### 🔸 Sheet 3 & Sheet 4  
<p align="center">
  <img src="https://github.com/RameenShahid/Egypt-Telecom-Sales-KPI-insights--MicroSoft-Excel/blob/220b2ed99d88762747ca708af1ec2f2c0ff6e3df/Visuals/Sheet%203.png?raw=true" width="45%" />
  <img src="https://github.com/RameenShahid/Egypt-Telecom-Sales-KPI-insights--MicroSoft-Excel/blob/220b2ed99d88762747ca708af1ec2f2c0ff6e3df/Visuals/Sheet%204.png?raw=true" width="45%" />
</p>

#### 🔸 Sheet 5 & Sheet 6  
<p align="center">
  <img src="https://github.com/RameenShahid/Egypt-Telecom-Sales-KPI-insights--MicroSoft-Excel/blob/220b2ed99d88762747ca708af1ec2f2c0ff6e3df/Visuals/Sheet%205.png?raw=true" width="45%" />
  <img src="https://github.com/RameenShahid/Egypt-Telecom-Sales-KPI-insights--MicroSoft-Excel/blob/220b2ed99d88762747ca708af1ec2f2c0ff6e3df/Visuals/Sheet%206.png?raw=true" width="45%" />
</p>

#### 🔸 Sheet 7  
<p align="center">
  <img src="https://github.com/RameenShahid/Egypt-Telecom-Sales-KPI-insights--MicroSoft-Excel/blob/220b2ed99d88762747ca708af1ec2f2c0ff6e3df/Visuals/Sheet%207.png?raw=true" width="50%" />
</p>

## ⚙️ Project Process

### 1. 📥 Data Collection
- Aggregated sales and operational KPIs by brand, region, and product category.
- Data sources include store-level reports and regional sales sheets.

### 2. 🧹 Data Cleaning
- Removed duplicates and null entries
- Standardized brand names and formats
- Converted target/achievement values to consistent numerical formats
- Mapped product category labels across sheets

### 3. 🔁 Data Transformation
- Used formulas like `SUMIFS`, `IFERROR`, and `VLOOKUP` for consolidation
- Created derived columns for Achievement Rate = (ACH / TGT)
- Structured Excel tables for slicer compatibility

### 4. 📊 Data Visualization
- Designed individual dashboards for each brand/region
- Centralized the core KPIs in a **Main Dashboard**
- Interactive slicers for dynamic filtering
- Conditional formatting to highlight performance gaps

---

## 📊 Key Metrics Tracked

| Category     | Target (TGT) | Achieved (ACH) | Achievement % |
|--------------|--------------|----------------|----------------|
| 📱 Mobile     | ✅            | ✅              | ✅              |
| 🌐 ADSL       | ✅            | ✅              | ✅              |
| 📞 Postpaid   | ✅            | ✅              | ✅              |
| ☎ Fixed Line | ✅            | ✅              | ✅              |

---

## 🧠 Features

✅ Region-wise brand performance  
✅ Product-level segmentation  
✅ Achievement vs. Target variance  
✅ Interactive slicers by product & region  
✅ Drill-down dashboards for detailed analysis  
✅ Heat indicators using color-coded visuals  
✅ Side-by-side comparison across multiple zones  

---
## 📁 Files Overview

| Sheet Name | Description |
|------------|-------------|
| DASHBOARD  | Main interactive panel with full KPI visual summary |
| Sheet 1-7  | Individual brand performance breakdowns |
| DATASET    | Raw & processed data supporting visualizations |

---
---

## 📊 Key Excel & DAX Functions Used

- `IF`, `VLOOKUP`, `SUMIFS`, `INDEX-MATCH`
- **Dynamic slicers** using Excel Tables
- **Conditional formatting** for KPI indicators
- **Pivot Charts** with slicer integration
- **Custom DAX measures** in Power Pivot
---

### Database
<p align="center">
  <img src="https://github.com/RameenShahid/Egypt-Telecom-Sales-KPI-insights--MicroSoft-Excel/blob/93a8a51ee23cf845715b6e97b9a8dd5ebc798e16/Visuals/Database.png?raw=true" width="50%" />
</p>

---
## 📁 Repository Structure

```plaintext
📦 telecom-egypt-brand-performance-dashboard/
├── 📊 Dashboard.png           # Main consolidated dashboard (7 brands)
├── 📄 Sheet 3.png             # Brand Dashboard - حي الكويت
├── 📄 Sheet 5.png             # Brand Dashboard - من دمياط - دمينس
├── 📄 Sheet 6.png             # Brand Dashboard - قنا - جنوب سيناء
├── 📄 Sheet X.png             # (Additional sheets for remaining brands)
├── 📈 Excel_File.xlsx         # Full interactive dashboard (optional upload)
├── 📜 README.md               # Project overview and documentation
# 📊 Telecom Egypt Brand Performance Dashboard

---
This project presents an advanced **interactive Excel dashboard** built to analyze and visualize key sales and operational KPIs for **Telecom Egypt** across **seven major regional brands**. The solution provides deep insights into brand-level performance segmented by product category, region, and achievement against sales targets.

