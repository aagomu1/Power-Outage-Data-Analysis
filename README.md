# Power Outage Data Analysis: Geographic, Temporal, and Customer Impact Insights

## **Project Objective**

This project analyzes county-level **power outage data** from the **Maryland Open Data Portal** to identify **geographic trends**, **temporal patterns**, and **customer impact**. The goal is to deliver insights that help stakeholders **improve outage response**, **strengthen grid reliability**, and **enhance customer experience**.

## **Dataset Used**

- <a href="https://github.com/aagomu1/Power-Outage-Data-Analysis/blob/main/Power_Outages_-_County_20250826.microsoftexcelworksheet.xlsx">Power Outages County Data</a>

## **Questions(KPIs)**

-What is the **total number of outages** and **% of customers impacted** across all counties?

-Which county is **worst affected** (highest outages/ % of customers out)?

-How have outages and customer impact **trended over time** (spikes,recoveries)?

-Which **time periods** saw the largest spikes in service disruptions?

-How does **county size(customers served)** relate to outage severity?

-Which counties consistently show **higher outage impact**?

-What is the **correlation between customers served and outage scale**?

-How do outage percentages vary **geographically**(map)?

-Ranking: **Top 5 counties** with highest customer impact.

**KPI Dashboard** <a href="https://github.com/aagomu1/Power-Outage-Data-Analysis/blob/main/Power_Outage_Data_Analysis_Dashboard.pdf">Dashboard</a> 

## **Process**

\-**Collected, cleaned, and validated 47k+ outage records** for accuracy.
-**Standardized data types** for outages, customers, and timestamps.
-Conducted **exploratory analysis** and **time-series analysis** to detect **patterns** and **spikes**.
-Built **geospatial, ranking, and correlation visualizations** to uncover **high-risk areas**.
-Designed an interactive **Power BI-Dashboard** with **dynamic filters** and **KPIs** for stakeholders.

## **Dashboard**

(link-to-your-dashboard-image.png)

## **Project Insights**

-Conducted **time-series and trend analysis** on 47k+ outage records, revealing **779,270 total incidents** impacting **~110,242 customers** statewide.
-Identified **Baltimore County** as the **worst-affected region**, with **Baltimore County, Montgomery, Anne Arundel, and Prince George's** also ranking in the **Top 5 impacted Counties**.
-Discovered **outage spikes between 17:00-20:00**, aligning with peak demand periods and signaling critical windows for **grid vulnerability management**.
-Analysis showed **no correlation between county size and outage severity**, emphasizing that **smaller populations can still face high outage percentages**.
-Leveraged **geospatial visualization** to highlight **regional disparities** in **outage impact**, providiing valuable insights for **localized emergency response and resource planning**.
-Prioritized the **Top 5 high-impact counties** as candidates for **preventive infrastructure upgrades and targeted outage response strategies**.

## **Final Conclusion**

This project demonstrates how **data driven outage analysis** can be leveraged to support **decision-making for utilities and emergency planners**.

By applying **eexploratory, time-series, and geospatial analysis techniques**, the project:
-Enables **faster outage response** through monitoring of key KPIs (outages,percent impacted, peak outage windows).
-Provides a framework to **prioritize infrastructure investments** in counties with consistently higher outage rates.
-Highlights opportunities to **develop county-specific strategies** for smaller regions facing disproportionately high outage percentages.
-Reinforces the role of **data visulization and dashboarding** (Power BI) in translating raw outage data into **actionable business insights**.

## **Live Data Demo**

The dataset updates every **15 minutes** on the **Maryland Open Data Portal**.
For **stability and reproducibility**, the dashboard uses a **cleaned snapshot** of the dataset.

However, I also wanted to show that I can work with **real-time, messy, and continuously updating data**- a skill that is **highly valuable in real-world analytics roles**.
To highlight this, I created a **companion notebook**:

\-[live\_data\_demo.ipynb](./live_data_demo.ipynb)

This notebook:
-**Pulls the latest outage records** directly from the **Maryland Open Data API**.
-Performs **light cleaning**(convert outages/customers to numeric, standardize timestamps).
-Generates a quick **bar chart of current outages by county**.

By including this **Live Data Demo**, I demonstrated not only how I can build **stable dashboards**, but also how I can adapt to **dynamic data pipelines** that mirror **real business scenarios**.

