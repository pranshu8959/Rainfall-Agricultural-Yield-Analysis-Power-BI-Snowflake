# 🌾 Rainfall & Agricultural Yield Analysis – Power BI + Snowflake

## 📌 Overview

This project presents a full-stack business intelligence solution analyzing agricultural data with a focus on rainfall, temperature, humidity, and crop yield. Using Snowflake for cloud-based data transformation and Power BI for multi-page reporting, it demonstrates SQL-driven data engineering, calculated groupings, and interactive visual storytelling tailored for decision-makers in agri-tech and environmental analytics.

---

## 🧰 Tools & Technologies

| Tool/Platform     | Purpose                                      |
|-------------------|----------------------------------------------|
| Snowflake          | Cloud data warehousing & SQL transformations |
| AWS S3             | Data staging and ingestion                   |
| Power BI Desktop   | Multi-page report development                |
| Excel              | Initial data validation and profiling        |

---

## 📂 Project Structure

```plaintext
├── Data Pipeline
│   ├── S3 Bucket Setup & Role Integration
│   ├── Snowflake Integration Object & Stage Creation
│   ├── SQL Transformations: Year Groups, Rainfall Groups
│   └── Data Profiling: Null checks, min/max, chart view
├── Power BI Report
│   ├── Page 1: Rainfall Analysis
│   ├── Page 2: Temperature Analysis
│   ├── Page 3: Humidity Analysis
│   ├── Page 4: Yield Analysis
│   └── Publishing to Power BI Service
```

---

## 📊 Key Features

- ✅ **SQL Transformations**: Year group classification, rainfall segmentation, area adjustments
- ✅ **Calculated Columns**: `year_group`, `rainfall_groups` based on defined thresholds
- ✅ **Power BI Visuals**:
  - Stacked bar charts for average rainfall, temperature, humidity, and yield
  - Segmentation by year, season, crop type, and location
  - Custom formatting: colors, labels, borders, shadows
- ✅ **Data Profiling**: Column distribution, quality checks, chart-based validation
- ✅ **Cloud Integration**: Snowflake + AWS S3 + Power BI connectivity

---

## 📈 Insights Delivered

- 🌦️ Rainfall trends across years, seasons, crops, and regions
- 🌡️ Temperature and humidity patterns by agricultural zone
- 🌱 Yield analysis segmented by soil type and irrigation method
- 📊 Grouped analysis using custom year and rainfall categories

---

## 🧠 Learning Outcomes

- Built a cloud-native data pipeline from AWS S3 to Snowflake
- Performed SQL-based transformations and profiling
- Created multi-page Power BI reports with consistent formatting
- Demonstrated business storytelling through environmental data
- Published reports to Power BI Service for stakeholder access

---

## 📤 Deployment Steps

1. Upload dataset to AWS S3  
2. Create Snowflake integration object and stage  
3. Transform data using SQL and validate with chart view  
4. Import final table into Power BI  
5. Build visuals and format reports  
6. Publish to Power BI Service
