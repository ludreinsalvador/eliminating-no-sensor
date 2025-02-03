# **Eliminating NO (Nitric Oxide) Air Quality Sensor for Project Cost Optimization**

---

## Overview
This project analyzes **air quality monitoring sensor data** to identify cost-optimization opportunities. Specifically, we assess the redundancy of the **`no` (Nitric Oxide) sensor** and determine if its removal would maintain data integrity while reducing costs.

---

## Objective
My goal is to evaluate whether the **`no` sensor can be eliminated** without losing crucial data. This is achieved through **statistical correlation analysis** and **linear regression modeling**, using **`no`, `no₂` (Nitrogen Dioxide), and `noₓ` (Nitrogen Oxides) sensor data**.

---

## Hypothesis
Eliminating the `no` sensor (Nitric Oxide) in N. Mai, Los Angeles California (CA), will have a minimal impact on overall air quality monitoring. This is based on the strong correlation, interdependence, or redundancy of `no` with other related pollutants, such as `no2` and `nox`. By leveraging data from these sensors, it can effectively derive `no` levels, thereby optimally reducing project expenses while maintaining the integrity of air quality data.

---

## Methodology
1. Data Preparation
2. Scatter Plot Analysis
3. Correlation Analysis
4. Line Plot Analysis
5. Linear Regression Model
   
---

## **Conclusion:** Strong correlations suggest sensor redundancy, making `no` a potential candidate for removal.
  - Eliminating the `no` sensor has minimal impact, as `no` can be predicted from `no₂` and `noₓ`.
  - Strong linear relationship and low RMSE confirm the `NO` sensor is redundant.
  - Removing the `NO` sensor reduces costs without affecting the quality of the data.
  - The approach can optimize sensor use in air quality monitoring systems.

---

## **Files and Reports**
- 📄 **[Project Selection Hypothesis](project-selection-hypothesis.pdf)** – I analyzed the criteria for selecting cost-effective projects. 
- 📄 **[Methodology Report](methodology.pdf)** – I outlined the research approach and data-processing techniques.   
- 📄 **[Results & Discussion](results-and-discussion)** – I summarized the key findings and conclusions.  
- 📊 **[Project Cost Optimization Notebook](project-cost-optimization.pdf)** – These are my Jupyter notebook for data analysis.  

---

## References
- Davda, K. (2024, June 27). What is low-cost air quality monitoring, and what are its Working principles? Oizom. https://oizom.com/what-is-low-cost-air-quality-monitoring/
- DD-Scientific. (n.d.). GS+7NO Nitric Oxide (NO) Sensor | Industrial specification. https://ddscientific.com/products/gs-7no-electrochemical-sensor-nitric-oxide-no
- Great Basin Unified Air Pollution Control District (n.d.). Low-Cost Air Quality Sensors. https://www.gbuapcd.org/AirMonitoringData/LowCostSensors/
- Kang, Y., Aye, L., Ngo, T. D., & Zhou, J. (2021). Performance evaluation of low-cost air quality sensors: A review. The Science of the Total Environment, 818, 151769–151769. https://doi.org/10.1016/j.scitotenv.2021.151769
- Kunak Technologies S.L. (2023, June 30). The power of low-cost air quality sensors for cleaner environments. Kunak. https://kunakair.com/low-cost-air-quality-sensors/
- OpenAQ Location ID 7936. (n.d.). OpenAQ Explorer. https://explore.openaq.org/locations/7936
- World Meteorological Organization. (2024, June 13). Low-cost sensors can improve air quality monitoring and people’s health. https://wmo.int/media/news/low-cost-sensors-can-improve-air-quality-monitoring-and-peoples-health
