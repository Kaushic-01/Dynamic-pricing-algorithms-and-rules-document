# Dynamic-pricing-algorithms-and-rules-document
A data-driven project implementing a rules-based dynamic pricing strategy to optimize revenue and class attendance for a fitness studio.The project analyzes historical class booking data to identify peak demand periods and top-performing classes, then defines a concrete set of algorithms for price adjustments.

**Key Dynamic Pricing Rules Implemented**

- The model uses three primary pricing rules based on patterns identified in the historical data (April to June 2018):

_**Surge Pricing (Demand-Based):**_

- Action: Implement a 5–10% price increase.

- Trigger: Classes scheduled on weekends and during peak evening hours to capitalize on high demand.

_**Premium Pricing (Popularity-Based):**_

- Action: Add a 10% premium.

- Trigger: Applied to the top 5 most popular classes to leverage their established brand and consistent booking rates.

_**Off-Peak Discounts (Resource Optimization):**_

- Action: Introduce a 5% discount.

- Trigger: Classes held during weekdays and non-peak hours to stimulate demand and optimize resource utilization during slower periods.

__**Technical Stack**__

The entire project workflow, from data cleaning to rule definition, is captured in the included Jupyter Notebook:

- _**Language Used**_ : Python

- __**Libraries**__: Pandas and NumPy for data manipulation and calculation, Matplotlib and Seaborn for exploratory data visualizations.

- __**Input Data**__: Historical fitness class data (Classes April-May 2018.csv, Classes June 2018.csv).

- __**Output**__: **Cleaned_Classes_Data.csv** (pre-processed dataset) and the final documented pricing rules.

__**Implementation & Next Steps**__

This notebook serves as the documentation for the pricing logic and the data processing pipeline.

__**Future steps include:**__

- Developing and deploying the final dynamic pricing algorithm into the live booking system.

- Monitoring the performance of the new pricing strategy and collecting customer feedback.

- Continuously refining the pricing model using new data to further optimize revenue and attendance.

