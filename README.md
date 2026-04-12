
# DPWH Data Cleaning, Transforming, and Visualization Project

This project is a data-driven audit of **9,827 flood control related projects** under the Department of Public Works and Highways (DPWH), based on the data these projects totalled to about **₱545.4 Billion** in contract costs alone.

---

## Tech Used
<p align="center"> 
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" /> 
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" /> 
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" /> 
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" /> 
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" /> 
</p>

---

## Key Performance Indicators (KPIs)
* **Total Contract Cost:** Tracking ₱545.4B in public funds across multiple fiscal years.
* **Project Volume:** Audit of 9,827 infrastructure records.
* **Market Concentration:** Analyzing over 1,500 contractors to identify dominant market players and potential monopolies.
* **Efficiency Metric:** Average Turnaround Time (Days) calculated by measuring the gap between project start and actual completion dates.

---

## Project Details

### **EDA**
* Did exploratory data analysis to see the dataset and figure out how it works, which rows and columns it had, what questions needed to be answered, and if there are any null or missing values that are required to change.
* After this visualized some graphs to gain insights on things like number of projects per region, total investment per region, distribution of costs, and top ten contractors total project cost to name a few. 

### **Data Engineering & SQL**
* Exported the cleaned dataset as Flood.csv to be inserted into the MySQL instance using Docker. This allows for consistent data schema deployment and simplifies the handoff between data cleaning (Python) and visualization (Power BI).
* **Database Management:** Stored datasets in a **MySQL** for scalable querying and data integrity.
* **Data Cleaning:** Transformed data using **Python (Pandas)** to handle missing values, normalize date formats, and ensure data types were visual-ready.

### **Power BI**
* Used Power BI Microsoft for visualization and creating the dashboard for this project.

---

## Learnings and Takeaways
* Was able to perform EDA and bolster data cleaning and transformation techniques.
* Went deeper when it came to creating graphs and charts before using dedicated tools which helped in asking questions and seeing what visualizations I needed to make in order to answer these.

