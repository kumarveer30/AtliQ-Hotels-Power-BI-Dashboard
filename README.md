# AtliQ-Hotels-Power-BI-Dashboard
An end-to-end Power BI dashboard project for AtliQ Hotels, analyzing revenue, occupancy, and customer satisfaction to drive business strategy.

### **Project Description**

This project features a comprehensive Power BI dashboard designed to provide a 360-degree view of business performance for AtliQ Hotels, a fictional hotel chain. The dashboard translates raw, disparate data into an interactive, actionable tool for stakeholders, enabling them to monitor key metrics, identify trends, and make data-driven decisions to boost revenue and enhance guest satisfaction.

This repository contains the Power BI source file (`.pbix`), the raw datasets used, and a summary of the project's objectives and outcomes.

---

### **Dashboard Key Features & Views**

The dashboard is organized into four interactive views:

1.  **Executive View:** A high-level summary of critical KPIs, including Total Revenue, Occupancy Rate, Average Daily Rate (ADR), RevPAR, and Average Customer Rating.
2.  **Revenue View:** A deep-dive into financial performance, with breakdowns by hotel property, room type, and booking platform. Includes Month-over-Month and Year-over-Year trend analysis.
3.  **Bookings View:** Detailed analysis of booking patterns, lead times, and cancellation rates to understand operational efficiency.
4.  **Customer Insights View:** Analysis of customer feedback and ratings to identify service strengths and areas for improvement across different properties.

---

### **Technical Skills & Concepts Demonstrated**

*   **Data Modeling:** Developed a robust star schema data model in Power BI, establishing relationships between fact and dimension tables to ensure data integrity and optimize query performance.
*   **ETL Processes:** Performed data cleaning, transformation, and loading using **Power Query** to handle inconsistencies, missing values, and standardize data from multiple CSV sources.
*   **DAX (Data Analysis Expressions):** Authored over 20 complex DAX measures to calculate critical hotel industry KPIs (e.g., RevPAR, Occupancy Rate, Cancellation Rate, MoM/YoY Growth).
*   **Data Visualization:** Designed an intuitive and visually appealing dashboard with a variety of charts, slicers, and cards to present insights effectively.
*   **UX/UI Design:** Implemented user-centric features like a top navigation bar (using bookmarks and buttons), dynamic filters, and informative tooltips to create a seamless user experience.

---


### **Data Sources**

The Dataset used in this Project is AtliQ Hotels dataset from the Codebasics challenge:
*   `dim_date.csv`
*   `dim_hotels.csv`
*   `dim_rooms.csv`
*   `fact_bookings.csv`
*   `fact_aggregated_bookings.csv`

---

### **Project Outcomes & Business Impact**

This dashboard successfully translates complex data into actionable intelligence. Key outcomes include:

*   **Identified High-Value Segments:** Analysis revealed that "Elite" type rooms, while having lower occupancy, generated a significantly higher ADR, informing a more targeted marketing and pricing strategy.
*   **Pinpointed Service Gaps:** Correlated low customer ratings with specific properties, providing management with data-driven evidence to investigate and improve service quality.
*   **Enabled Proactive Decision-Making:** The interactive nature of the dashboard allows stakeholders to move from reactive reporting to proactive analysis, exploring trends and drilling down into issues in real-time.
