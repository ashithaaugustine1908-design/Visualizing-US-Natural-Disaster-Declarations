# Visualization of U.S. Natural Disaster Declarations

## 📌 Project Overview
This project analyzes **U.S. Natural Disaster Declarations (1953–2025)** to understand disaster patterns across states and identify trends over time.  
The analysis focuses on identifying high-risk states, major disaster types, and seasonal storm patterns using interactive Power BI dashboards.

The project includes two dashboards:

1. **From Texas to Tennessee – Unveiling U.S. Disaster Patterns**
2. **U.S. Storm Activity: State and Seasonal Trend**

These dashboards help reveal how disasters are distributed across the United States and how storm incidents vary by state and month.

---

# 📊 Dashboard 1: From Texas to Tennessee – Unveiling U.S. Disaster Patterns

This dashboard provides an **overall analysis of disaster declarations across the United States from 1953 to 2025**.

### KPIs Used
- **Total Disasters**
- **Total States**
- **Total Incident Types**
- **Total HM Declared**
- **Data Coverage:** 1953 – 2025

### Visualizations Used
- Pie Chart – Count of Incident Type by Declaration Type  
- Table – Incident Type vs Total Disasters  
- Bar Chart – Total Disasters by State Name  
- Line Chart – Total Disasters by Year  

### Key Insights
- **Texas recorded the highest number of disaster declarations** among all states.
- The most common disaster type observed is **Severe Storm**.
- Disaster declarations have increased significantly in recent years.
- **2020 recorded the highest number of disasters (907)** across the United States.
- Disaster occurrences vary widely across different states and regions.

---

# 🌩 Dashboard 2: U.S. Storm Activity – State and Seasonal Trend

This dashboard focuses specifically on **storm-related disasters** and analyzes their yearly and monthly patterns across states.

### KPIs Used
- **Total Storm Incidents**
- **Average Storms per Year**
- **Total Disasters**

### Visualizations Used
- Bar Chart – Total Storm Incidents by State Name  
- Line Chart – Total Storm Incidents by Year  
- Line Chart – Total Storm Incidents by Month  

### Key Insights
- Storm incidents occur across almost all U.S. states.
- There is a **clear seasonal trend** in storm activity.
- Each state shows a **peak month for storm incidents**.
- Identifying these peak months helps disaster management teams prepare better.
- Focusing on high-risk months can reduce the impact of storms.

---

# 📚 Dataset Description
The dataset contains **FEMA Disaster Declaration records** including disaster type, location, declaration information, and assistance programs declared.

### Key Dataset Columns
- `disaster_number`
- `state`
- `incident_type`
- `declaration_type`
- `declaration_date`
- `incident_begin_date`
- `incident_end_date`
- `region`
- `designated_area`
- `ih_program_declared`
- `ia_program_declared`
- `pa_program_declared`
- `hm_program_declared`

### Dataset Summary
- Covers disaster records from **1953 to 2025**
- Includes multiple disaster types such as storms, floods, hurricanes, and severe weather
- Used for **trend analysis, state comparison, and seasonal disaster analysis**

---

# 🧰 Tools Used
- **Power BI** – Data visualization and dashboard creation  
- **Power Query** – Data cleaning and transformation  
- **DAX (Data Analysis Expressions)** – KPI calculations  
- **GitHub** – Project documentation and version control  

---

# 📷 Dashboard Preview

<p align="center">
  <img src="SCREENSHOTS/dashboard 3.png" width="900">
</p>

---

<p align="center">
  <img src="SCREENSHOTS/dashboard 4.png" width="900">
</p>

---

# 📈 Future Enhancements
- Add predictive disaster trend analysis.
- Include regional disaster risk scoring.
- Integrate weather and climate datasets.
- Expand analysis to economic damage impact.





