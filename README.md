# Global Tourism – Data Visualization

*Visual exploration of global tourism indicators through structured time-series analysis and comparative charts.*

This repository represents the **Data Visualization** phase of the **Global Tourism Statistics** project. 
It follows the  
[Data Warehouse (DWH)](https://github.com/Daniele1388/DWH---Global-Tourism-Project) and
[Exploratory Data Analysis (EDA)](https://github.com/Daniele1388/EDA---Global-Tourism-Project),
and precedes the
[Advanced Analytics](https://github.com/Daniele1388/ADVANCED-ANALYTICS---Global-Tourism-Project).  

While the **DWH** defines the data structure and the **EDA** validates data quality and consistency,  
this **Visualization phase** focuses on translating structured tourism indicators into clear visual trends.

The objective is to observe patterns over time and highlight structural changes in tourism performance.

---

## Scope of Visualization

The notebook includes visual analysis of:

- Domestic tourism  
- International arrivals (Inbound)  
- International departures (Outbound)  
- Tourism industries  
- Selected SDG indicators  

France is used as a reference country due to consistent coverage across indicators.

---

## Technical Stack

- SQL Server (Gold Layer extraction)  
- Python  
- Pandas  
- Matplotlib  
- Jupyter Notebook  

---

## Analytical Workflow

1. Data extraction from the Gold Layer  
2. Fact and dimension joins  
3. Data filtering and preparation  
4. Time-series visualization  
5. Trend observation  

Special attention is given to SDG indicators that contain multiple reporting series  
(e.g., SEEA and TSA frameworks), which are preserved as distinct measurements.

---

## Project Architecture Overview

```
Global Tourism Statistics Project
│
├── Data Warehouse (DWH)
├── Exploratory Data Analysis (EDA)
├── Advanced Analytics
└── Data Visualization
```

---

### Position within the Project

- **DWH** → Data modeling and structured architecture  
- **EDA** → Data validation and structural checks  
- **Advanced Analytics** → Segmentation and performance metrics   
- **Data Visualization** → Graphical interpretation of trends

---

## About Me

Hi, I’m **Daniele Amoroso**   
I like working with data and I’m interested in Data Analytics, Data Science, and AI Automation. 
I build data projects to understand information and find insights.

Connect with me on [LinkedIn](https://www.linkedin.com/in/daniele-a-080786b7/).
