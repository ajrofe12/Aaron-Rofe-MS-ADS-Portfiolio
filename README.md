# **Aaron Rofe - Applied Data Science Portfolio**
### M.S. in Applied Data Science - Syracuse Univeristy
### Fall 2025

---


# Applied Data Science Portfolio - Overview

This portfolio highlights 3 projects completed throughout the MS ADS program plus my undergraduate senior thesis, and explains how each contributed to achieving the program's core learning outcomes.

---


## **Program Learning Outcomes**

### **1. Collect, store, and access data by identifying and leveraging applicable technologies**
Working with diverse data sources and storage systems - including SQL databased, APIs, and flat files (CSV) - to reliably acquire, organize, and retrieve data for analysis.

### **2. Create actionable insight across a range of contexts (e.g. societal, business, political), using data and the full data science life cycle**
Applying problem definition, exploration, cleaning, modeling, evaluation, and interpretation to derive meaningful insights using data.

### **3. Apply visualization and predictive models to help generate actionable insight**
Using tools like ggplot2, Shiny, Python visualisation, tableau and machine learning models to uncover patterns in data and support decisions.

### **4. Use programming languages such as R and Python to support the generation of actionable insight**
Writing reporoducable code in R and Python for data preparation, modeling, feature engineering, and dashboards to produce data-driven insights.

### **5. Communicate insights gained via visualization and analytics to a broad range of audiences (including project sponsors and technical team lead)**
Translating analytics results into clear visual dashboards, presentations, and written analyses for both technical and non-technical audiences.

### **6. Apply ethics in the development, use and evaluation of data and predictive models (e.g., fairness, bias, transparency, privacy)**
Address concerns such as fairness, bias, model transparency, and the appropriate use of sensitive variables when conducting an analysis.

---


## **High-Level Summaries of Included Projects**

### **1. Residential Energy Usage Shiny App (IST 687)**
Developed an interactive shiny app and random forest model to classify homes into low, medium or high energy usage based on more than 200 building, demographic, and climate variables.

### **2. Climate-Commodity Machine Learning Project (IST 707)**
Analyzed climate indicators (temperature, precipitation, anomalies) and their relationship seven common global commodity prices. Built a python-based pipeline for preprocessing, feature engineering and modeling.

### **3. Emergency Hospital Transportation Database (IST 659)**
Designed a full relational database system supporting emergency dispatch workflows. Included ERD diagrams, logical and conceptual models, full project writeup, and final presentation.

### **4. MLB Shirking Thesis (Undergraduate Senior Thesis)**
Used R, Fangraphs/Spotrac data, and GAM models to investigate whether MLB players show reduced performance after signing long-term contracts. Built predictive models for the 2025 free-agent class. 

---


## **How These Projects Demonstrate the Program Learning Outcomes**

### **1. Collect, store, and access data by identifying and leveraging applicable technologies**
- **Climate–Commodity ML Project:** Merged multiple CSV datasets containing global commodity prices and climate indicators, and built a reproducible Python preprocessing workflow.
- **MLB Shirking Thesis:** Used several data sources (`baseballr`, Fangraphs, Spotrac) to gather multi-year salary, performance, and demographic data for nearly 2,000 players.
- **Energy Usage Shiny App:** Cleaned and sampled a very large dataset (~8.5M rows) and produced modeling-ready CSV/RDS files for downstream analysis.

---

### **2. Create actionable insight using the full data science lifecycle**
- **Energy Usage Shiny App:** Built a Random Forest model and interactive dashboard to classify households into usage levels, offering insight into energy consumption behavior.  
- **MLB Shirking Thesis:** Determined how salary increases and contract length influence player performance decline, giving actionable guidance for contract risk evaluation in sports analytics.  
- **Climate–Commodity Project:** Performed exploratory analysis to evaluate how temperature, precipitation, and climate anomalies relate to price behavior across seven agricultural commodities.  
- **Hospital Database:** Designed a relational schema and relationships that improve emergency dispatch workflows and support efficient patient, hospital, and resource coordination.

---

### **3. Apply visualization and predictive models to generate insight**
- **Shiny App:** Implemented Random Forest classification, variable importance plots, and interactive data tables to support interpretability.  
- **MLB Shirking Thesis:** Used exploratory visualizations and GAM modeling to analyze performance decline patterns.  
- **Climate–Commodity Project:** Created time-series plots, climate vs. price comparisons, and correlation analyses using Python.

---

### **4. Use programming languages such as R and Python to support analytics**
- **R:** Applied heavily across the Shiny App (UI/server, preprocessing, modeling, visualizations) and MLB thesis (cleaning, GAM modeling, prediction, EDA).  
- **Python:** Used in the Climate–Commodity project for preprocessing, feature engineering, modeling, and visualization workflows.  
- **SQL:** Applied in the Hospital Database project for table creation, constraints, triggers, functions, and data population.

---

### **5. Communicate insights to both technical and non-technical audiences**
- **Shiny App:** Presented model outputs and explanations through a user-friendly, interactive dashboard.  
- **Hospital Database:** Communicated system design through ER diagrams, conceptual and logical models, and clear technical documentation.  
- **MLB Shirking Thesis:** Delivered a full written analysis with clear explanations of data collection, modeling choices, and interpretation.  
- **Climate–Commodity Project:** Produced notebooks and documentation summarizing trends, modeling steps, and key findings.

---

### **6. Apply ethics in data and model development**
- **Shiny App:** Removed leakage-prone variables and prevented overfitting by excluding direct energy consumption metrics.  
- **Hospital Database:** Considered privacy and sensitive medical information when designing tables and relationships.  
- **Climate–Commodity Project:** Identified where price–climate relationships broke down during COVID-era shocks and avoided overstating conclusions.  
- **MLB Shirking Thesis:** Carefully handled birthplace/demographic variables and discussed fairness considerations in modeling.

