# **Tesla Deliveries Exploratory Data Analysis (2015-2025)**


## **Executive Summary**
This project conducts an Exploratory Data Analysis (EDA) on Tesla's global electric vehicle data, spanning from **2015 to 2025**. The dataset captures Tesla's decade-long journey of innovation, production scaling, market growth, and environmental impact. By examining delivery trends, production efficiency, vehicle specifications, and sustainability metrics, the analysis highlights Tesla's evolution as a leader in electric mobility. It identifies key performance patterns that support future forecasting, pricing optimization, and sustainability initiatives.

### **Business Problem**
Tesla’s growth strategy relies on balancing production capacity, market demand, and technological innovation. Understanding how these metrics interact across time, region, and model helps reveal what drives delivery performance, where efficiency gaps exist, and how sustainability efforts correlate with output.


## **Methodology**

### **Data Preparation**
- Inspected data structure, types, and completeness  
- Cleaned missing or inconsistent values  
- Created new features for date and growth analysis  
- Verified data integrity (no duplicates, consistent types)

### **Exploratory Data Analysis (EDA)**
- Descriptive statistics and visual summaries  
- Trend and correlation analysis  
- Outlier detection and distribution plotting  
- Time-series and regional breakdowns

### **Skills**
- **Language:** Python
- **Libraries:** Pandas, Numpy, Matplotlib, Seaborn, Plotly
- **Tools:** Power BI, Jupyter Notebook
- **Techniques:** Data Cleaning, EDA, Correlation Analysis, Statistical Summary, Time-Series Visualization

## **Key Performance Indicators (KPIs)**

| **Category** | **KPI** | **Value / Insight** |
|---------------|----------|---------------------|
| **Data Quality** | Missing Values | 0 |
|  | Duplicate Records Removed | 22 |
|  | Derived Date Field | Combined from Year & Month |
| **Performance Metrics** | Production–Delivery Correlation | 0.99 (High Efficiency) |
|  | Avg. Deliveries per Year | ~880,000 vehicles |
|  | Peak Delivery Year | 2023 |
|  | Lowest Delivery Year | 2015 |
| **Technology Metrics** | Avg. Battery Capacity | 78.5 kWh |
|  | Avg. Range | 510 km |
|  | Avg. Vehicle Price | \$56,000 USD |
| **Sustainability Metrics** | Total CO₂ Saved (2015–2025) | ~1.8 million tons |
|  | Avg. CO₂ Saved per Vehicle | 0.9 tons |
|  | Charging Station Growth | +320% (2015–2025) |
| **Statistical Summary** | Mean Deliveries | 876,000 |
|  | Median Deliveries | 890,000 |
|  | Std. Deviation | ±130,000 |
|  | Distribution Shape | Right-skewed (growth trend) |

#### *Insight*
Tesla’s data reveals exponential growth and operational precision. The near-perfect correlation between production and deliveries (≈0.99) highlights the distinctive synchronization of the supply chain. Battery and range improvements (20–25%) alongside reduced average prices reflect technological advancements and cost optimization.  Environmental indicators, such as CO₂ saved and charging expansion, showcase Tesla’s growing sustainability footprint.

## Results
- Tesla maintained a near-perfect production-to-delivery correlation (0.99), showing excellent capacity management.  
- Deliveries surged post-2019 with the release of Model 3 and Model Y.  
- Battery capacity and vehicle range grew 20–25% while price declined ~10%, reflecting improved efficiency.  
- Global charging stations grew 320%, and Tesla prevented ~1.8 million tons of CO₂ emissions over the decade.  
- North America and Europe lead in total deliveries; Asia-Pacific showed the fastest growth after 2021.  
- Data distributions show right-skewed growth, validating Tesla’s accelerating global adoption.

### Operational Recommendations
- **1. Optimize Production Forecasting:**  
  Implement predictive models to forecast demand by model and region for resource alignment.  
- **2. Expand Charging Infrastructure in Emerging Markets:**  
  Target infrastructure investment in the Asia-Pacific region, driven by rising adoption.  
- **3. Continue Cost Reduction through Battery Innovation:**  
  Enhance energy density to maintain profitability while improving performance.  
- **4. Strengthen Sustainability Reporting:**
  Integrate CO₂ and charging growth metrics into executive dashboards for strategic tracking.

### Key Takeaway
Tesla’s decade-long performance reflects the synergy between innovation, production efficiency, and sustainability. EDA confirms Tesla’s strategic success in scaling operations efficiently while continuously improving environmental outcomes and product accessibility.

---

## Dataset Overview

**Source:** Aggregated dataset representing Tesla’s electric vehicle production, deliveries, and sustainability metrics worldwide between **2015 and 2025**. The dataset compiles insights on manufacturing scale, technological advancement, pricing evolution, and environmental impact across Tesla’s major global regions and vehicle models.

**File:** [`cleaned_tesla_deliveries.csv`](https://github.com/raidarasul-sys/raida-portfolio/blob/main/cleaned_tesla_deliveries.csv)

**Contents:**
- `year` — Year of record (2015–2025)  
- `month` — Month of record (1–12)  
- `region` — Geographic region (e.g., North America, Europe, Asia-Pacific)  
- `model` — Tesla vehicle model (e.g., Model S, 3, X, Y)  
- `production_units` — Total number of vehicles produced during the period  
- `estimated_deliveries` — Number of vehicles delivered to customers  
- `avg_price_usd` — Average selling price per vehicle in U.S. dollars  
- `battery_capacity_kwh` — Average battery capacity in kilowatt-hours (kWh)  
- `range_km` — Average driving range per full charge in kilometers  
- `co2_saved_tons` — Estimated CO₂ emissions saved through EV adoption
- `charging_stations` — Number of operational Tesla charging stations worldwide 

> *Note: This dataset is a cleaned, aggregated representation intended for analytical demonstration.*
