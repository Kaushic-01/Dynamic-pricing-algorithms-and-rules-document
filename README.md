# Dynamic-pricing-algorithms-and-rules-document
A data-driven project implementing a rules-based dynamic pricing strategy to optimize revenue and class attendance for a fitness studio.The project analyzes historical class booking data to identify peak demand periods and top-performing classes, then defines a concrete set of algorithms for price adjustments.

**Key Dynamic Pricing Rules Implemented**

The model uses three primary pricing rules based on patterns identified in the historical data (April to June 2018):

Surge Pricing (Demand-Based):

Action: Implement a 5–10% price increase.

Trigger: Classes scheduled on weekends and during peak evening hours to capitalize on high demand.

Premium Pricing (Popularity-Based):

Action: Add a 10% premium.

Trigger: Applied to the top 5 most popular classes to leverage their established brand and consistent booking rates.

Off-Peak Discounts (Resource Optimization):

Action: Introduce a 5% discount.

Trigger: Classes held during weekdays and non-peak hours to stimulate demand and optimize resource utilization during slower periods.

Technical Stack
The entire project workflow, from data cleaning to rule definition, is captured in the included Jupyter Notebook:

Language: Python

Libraries: Pandas and NumPy for data manipulation and calculation, Matplotlib and Seaborn for exploratory data visualizations.

Input Data: Historical fitness class data (Classes April-May 2018.csv, Classes June 2018.csv).

Output: Cleaned_Classes_Data.csv (pre-processed dataset) and the final documented pricing rules.
