# healthcare-revenue-patient-insights-analysis

 Brief Summary

 Interactive Power BI dashboard analyzing hospital operations, patient trends and revenue drivers with a focus on actionable insights.
_____

 Overview

 This project transforms raw healthcare data into a structured analytical dashboard to monitor patient flow, resource utilization and financial performance. It emphasizes storytelling through data by connecting operational metrics with revenue outcomes.
_____

 Problem Statement

 To identify key drivers of hospital revenue, understand patient distribution patterns and evaluate operational efficiency for better decision-making.
____

 Tools & Technologies
 
  * Power BI
  * Power Query (Data Cleaning & Transformation)
  * DAX (Data Analysis Expressions)
  ____
 
  Methods

 - Cleaned and transformed data using Power Query:
   - Handled missing follow-up dates (converted to null)
   - Standardized date formats and data types
 - Built DAX measures:
   - Total Billing
   - Total Patients
   - Average Billing = Total Billing / Total Patients
   -  Average Length of Stay (LOS) using DATEDIFF
 - Designed interactive dashboard with slicers and KPI cards
-  Applied data modeling and aggregation for meaningful insights
  ____
  
  Key Insights
  
 - Top diagnostic tests contribute ~60% of total patient volume, indicating operational concentration
 - Private wards generate ~65% of total revenue, acting as the primary revenue driver
 - Insurance contribution shows variability, impacting consistency of cash inflows
____

  Dashboard
  
  ![image alt](https://github.com/Geetika-ops/healthcare-revenue-patient-insights-analysis/blob/a79e850fe98a9db5dd3a0933ea12db83e3d7de69/PowerBI%20Dashboard.png)
  ___

  Results & Conclusion

  The dashboard highlights that revenue stability is primarily driven by private ward utilization, while insurance variability introduces financial uncertainty. It provides a          comprehensive view of operational and financial metrics, enabling data-driven healthcare decisions.
