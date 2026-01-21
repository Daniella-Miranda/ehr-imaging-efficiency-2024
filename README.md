## Tableau Public Dashboard: https://public.tableau.com/views/Hospital_EHR_Interop_Imaging_Efficiency_2024/Dashboard2?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

# ehr-imaging-efficiency-2024
This project analyses whether EHR interoperability adoption within the state-level result in better outpatient imaging efficiency. This analysis uses Tableau, Excel, and publicly available CMS datasets

## Tools
- Excel (data cleaning, pivot tables)
- Tableau Public (visualization, dashboarding)
  
## Datasets
- CMS Promoting Interoperability - Hospital dataset
- CMS Outpatient Imaging Efficiency - State dataset

## Key Insights
- States with higher EHR ineroperability adoption do not show measurable improvements in outpatient imaging efficicency.
- States with low EHR interoperability adoption show **higher average outpatient imaging efficiency** score.
- New York was the state with the **highest interoperability adoption**, showing an average 18.975.
- Conneticut had the **highest low-interoperability value** with an average efficiency of 18.2.
- Scatter plot analysis shows low interoperability states have a **downward trend**, while high interoperability states are mostly flat across efficiency values.
- Geographic map visualization highlighted **outlier states** where efficiency does not match expected interoperability levels. 

## How to Explore
1. Open the Tableau workboos in "tableau_workbooks/"
2. Review dashboards and KPIs

## Dashboard Preview

## US State Efficiency 2024

![US State Efficiency Dashboard](ehr_dashboard.png.png)
*This dashboard visualizes geographic distribution of efficiency and high vs low interoperability categories.*

## Conclusion/Interpretation

The analysis indicates that higher interoperability adoption does not always correspond to higher outpatient imaging efficiency (this was analyzed at the state level). The findings suggest that other operational or policy factors may influences imgaing efficiency, and also suggests technology is not the sole driver of improvement. The Dashboard provides insights for stakeholders to explore state-level patterns and identify outliers to further investigate. 
