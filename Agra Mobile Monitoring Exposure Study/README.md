# Agra Mobile Monitoring Exposure Study

This project documents exposure monitoring campaigns conducted to analyze PM₂.₅ and PM₁₀ exposure using low-cost sensors and high-resolution DustTrak data.

## 🎯 Objectives

- Evaluate on-road exposure to PM2.5 and PM10 across selected routes.
- Integration of sensor and DustTrak data for spatial exposure pattern analysis  
- Categorization by weekday/weekend and peak/lean hours to understand the variation of pollution during different times and urban settings

--

## 🛠 Tools & Libraries

- R (tidyverse, lubridate, openair, ggplot2)  
- QGIS for spatial overlays  
- Data collected via mobile and stationary platforms in Agra and Mumbai

---

## 🧪 Methodology

### PM Data Analysis Workflow

<img src=".Outputs/Data preprocessing.png" width="650"/>

- Raw data cleaning and time-zone standardization
- Merging of GPS and pollutant data using ±2 seconds logic
- Averaging and categorization of data by time and space
- Gridded interpolation and visualization over base maps using ggplot2 and QGIS

### GPS Interpolation Logic

<img src=".Outputs/Methodology.png" width="600"/>

---

## 📊 Sample Outputs

<p align="center">
  <img src=".Outputs/PM10 monitoring.png" width="400"/>
  <img src=".Outputs/PM2.5 monitoring.png" width="400"/>
  <img src=".Outputs/CO monitoring.png" width="400"/>
</p>

---

## 👩‍🔬 Author

**Sruthi Jayaraj**  
PhD in Environmental Engineering, IIT Madras  
Program Associate – Air Quality, WRI India  
📫 sruthijayaraj.19@gmail.com  

🛑 **Note:** All content in this repository is © 2025 Sruthi Jayaraj. Reuse, redistribution, or reproduction is not permitted without explicit written permission.
