# nyc-service-requests
Data Analytics Project 
# 311 NYC Service Requests Analysis

## Overview  
This project analyzes New York City’s 311 service request data to uncover patterns and trends in complaint types, timing, and geographic distribution. Using Python and data analysis libraries, it provides insights into how residents interact with city services.

## Data  
- Source: NYC Open Data portal - [311 Service Requests from 2010 to Present](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9)  
- Dataset size: Approximately 100,000+ records (sample subset used)  
- Key columns used: `Created Date`, `Complaint Type`, `Borough`

## Methods  
- Data cleaning: Converted date columns to datetime objects and handled missing values  
- Exploratory analysis: Grouped complaints by year, month, borough, and complaint type  
- Visualization: Created bar charts and line plots using Matplotlib and Seaborn to illustrate trends and distributions

## Key Findings  
- The most common complaint type is Illegal Parking  
- Complaint volumes vary seasonally, with peaks in December  
- Boroughs such as Brooklyn and Queens show higher complaint activity

## How to Run  
1. Clone or download this repository  
2. Ensure you have Python 3.x installed with the following libraries:  
   - pandas  
   - matplotlib  
   - seaborn  
3. Open the Jupyter notebook (`311_analysis_project.ipynb`) in JupyterLab or Jupyter Notebook  
4. Run the notebook cells sequentially to reproduce the analysis and visualizations

## Author  
Matthew Montefusco  
https://www.linkedin.com/in/matthew-montefusco-879123231/

---

*This project was completed as part of a data analysis portfolio demonstrating skills in Python, data cleaning, visualization, and exploratory data analysis.*
