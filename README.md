# Visualization of US Natural Disaster Declaration
## 📌 Project Overview
This project analyzes global landslide incidents from **2007–2017** to identify patterns, risk zones, fatalities, and country-wise trends.  
The interactive dashboard helps in understanding disaster distribution, severity, and seasonal trends.

## 🔎 Problem Statement
* U.S. natural disaster declaration data is available in large, unstructured formats that are difficult to interpret.
* Identifying disaster trends and high-risk regions from raw data requires extensive manual analysis.
* Lack of clear visualizations limits effective understanding and data-driven decision-making.
## 📚Data Set Discription
The dataset contains detailed records of natural disaster events, primarily focusing on landslides, mudslides, and other related incidents globally. It is compiled from multiple sources including news agencies and disaster reporting organizations.
#### Key features of the dataset include:
* Source Information: source_name, source_link – origin of the report.
* Event Details: event_id, event_date, event_time, event_title, event_description – identification and description of each event.
* Location Data: location_description, location_accuracy, admin_division_name, admin_division_population, country_name, country_code, longitude, latitude – geographic details including administrative division and coordinates.
* Disaster Characteristics: landslide_category, landslide_trigger, landslide_size, landslide_setting – type, cause, and scale of the disaster.
* Impact Metrics: fatality_count, injury_count – human impact of the event.
* Supplementary Data: storm_name, photo_link, notes, event_import_source, event_import_id – additional context and references.
* Administrative Data: gazeteer_closest_point, gazeteer_distance – nearest reference point and distance.
* Tracking Information: submitted_date, created_date, last_edited_date – data submission and update timestamps.

####  Dataset Summary:
* Contains 31 columns capturing detailed event and location attributes.
* Covers events from multiple countries including the United States, Philippines, Nepal, China, and Peru.
* Useful for trend analysis, geographic mapping, risk assessment, and disaster visualization dashboards
 
## 🧮 Key Performance Indicators (KPIs)

- **Total Events:** 413  
- **Total Fatalities:** 3,790  
- **Fatalities per Event:** 9.19  
- **Highest Risk Zones:** High & Medium Risk Regions  
- **Most Affected Country:** China  

---

## 🔍 Key Insights

- Landslide occurrences show noticeable seasonal trends in certain regions.
- High-risk zones contribute significantly to overall fatalities.
- China recorded a comparatively higher number of landslide events.
- The fatality-per-event ratio indicates severe impact in vulnerable areas.
- Recurring peaks are observed in specific months, indicating weather influence.

---

## 📝 Recommendations

- Improve early warning systems in high-risk zones.
- Strengthen infrastructure in landslide-prone regions.
- Increase awareness programs in vulnerable communities.
- Allocate more disaster management resources during high-frequency months.
- Implement better land-use planning and slope stabilization techniques.

---

## 🧰 Tools Used

- **Power BI** – Data visualization and dashboard creation  
- **Microsoft Excel** – Data cleaning and preprocessing  
- **DAX (Data Analysis Expressions)** – KPI calculations and measures  
- **GitHub** – Project documentation and version control  

---


## 📷Dashboard Preview

<p align="center">
  <img src="SCREENSHOTS/dashboard 3.png" width="900">
</p>

---
<p align="center">
  <img src="SCREENSHOTS/dashboard 2.png" width="900">
</p>

---



## 📈 Future Enhancements

- Add predictive analysis using historical trends.
- Integrate real-time disaster datasets.
- Expand analysis to include economic loss impact.

