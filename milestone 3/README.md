📊 **Milestone 3 – Forecasting and Cancellation Trend Analysis**

📌 Objective

The objective of Milestone 3 is to analyze historical hotel booking data and apply time series forecasting to predict future bookings. This milestone also focuses on understanding cancellation patterns, seasonal trends, and lead-time behavior using Power BI visualizations and Python-based forecasting.


🔮 **Forecasting Approach**

Forecasting is performed outside Power BI using Python (time series model).

The output forecast file (forecast.csv) contains:

ds → date

yhat → predicted bookings

This forecast data is imported into Power BI as a separate table.

Actual and forecast data are not mixed incorrectly (no aggregation mismatch).

📊 **Key KPIs (Cards)**

The following KPIs are displayed at the top of the report:

Peak Forecast Month – Month with highest predicted bookings

Total Forecasted Bookings – Sum of predicted bookings

Cancellation Rate (%)

No-Show Rate (%)

These KPIs provide a quick summary of future demand and booking risk.

📈 **Visualizations Included in the Report**
1️. Total Bookings by Month (Actual)

Insight: Identifies seasonal dips and peaks in actual data

2️. Forecasted Bookings by Date

Insight: Shows predicted spike in upcoming months (e.g., August)

✅ This is the correct forecasting visual used in the report.

3️. Forecast vs Average Actual Bookings

 Compares predicted demand against historical average

4️. Total Bookings by Season

Identifies which season contributes most to bookings

5️. Cancellation Rate (%) by Month

 Helps identify high-risk months

6️. Sum of Cancellations by Month

 Complements cancellation rate analysis

7️. Cancellation Rate (%) by Lead Time Bucket

 Longer lead times show higher cancellation probability

🎛 **Filters / Slicers Used**

 - Season slicer (Spring, Summer, Winter)

-  Month slicer

- Hotel Branch Key slicer


✅ **Conclusion**

Milestone 3 demonstrates:

* Proper use of Python-based forecasting

* Clean integration of forecast results into Power BI

* Clear separation of actual vs predicted data

* Insightful analysis of cancellations and seasonality


The report provides both historical insights and future demand predictions, supporting data-driven decision-making.
