# **COVID-19 Analysis Using Power BI**  

This Power BI dashboard analyzes the impact of COVID-19 on humanity from January 22 to July 27, 2020.It consists of two main pages:  

1. **Overview Page**: Provides a summary of the pandemic's overall effects on mankind and its global impact.  
2. **Global View Page**: Offers a detailed breakdown of active cases, deaths, confirmed cases, and recoveries across each WHO region.  

Interactive filters for WHO region, countries, and dates are available on both pages for deeper insights.  

### Steps to Create the Dashboard  

1. **Data Import**:  
   The dataset was imported into Power BI from an Excel file.  

2. **Data Cleaning**:  
   Using Power Query Editor, basic cleaning processes were applied:  
   - Removing duplicates  
   - Adjusting data types  
   - Replacing null values  

3. **Data Modeling**:  
   - Established relationships between tables to ensure data connectivity.  

4. **Measure Creation**:  
   - Developed calculated measures for effective analysis.  

5. **Dashboard Design**:  
   - Customized visuals and layouts with necessary details for clarity and usability.
   - ----
### Pages in the Dashboard  

#### **Overview Page**  
This page presents a high-level summary of the pandemic's impact.  
![Screenshot 2024-12-09 122725](https://github.com/user-attachments/assets/2fe6635f-6af3-4c1d-aad1-800e366a552e)
**Key Visual Elements**:  

- **Slicers**: Filters for Country, WHO Region, and Date.  
- **Cards**: Display aggregate values for:  
  - Active Cases  
  - Confirmed Cases  
  - Deaths  
  - Recovered Cases  
- **Stacked Column Chart**:  
  - Compares Active and Recovered cases across WHO regions using distinct colors for clarity.  
- **Pie Chart**:  
  - Visualizes the percentage distribution of Confirmed Cases across WHO regions.  
- **Clustered Bar Chart**:  
  - Highlights the Recovery Rate in each WHO region.  
- **Line and Clustered Column Chart**:  
  - Displays:  
    - Confirmed and Recovered cases (Bars)  
    - Death cases (Line) in WHO regions.  
- **Table**:  
  - Summarizes data by Country/Region, showing the total Confirmed Cases, Deaths, and their aggregates.  
---
#### **Global View Page**  
This page uses geographical visuals to explore the pandemic's global trends.  
![Screenshot 2024-12-09 122746](https://github.com/user-attachments/assets/93cff326-a23c-4f43-8a0e-c5a4be151c3d)
**Key Visual Elements**:  
- **Slicers**: Filters for Country, WHO Region, and Date.  
- **Map Visuals**: Four maps display WHO regions based on:  
  1. Active Cases  
  2. Recovered Cases  
  3. Confirmed Cases  
  4. Deaths  
This layout enables a comprehensive understanding of COVID-19's global progression, facilitating informed decision-making.  
