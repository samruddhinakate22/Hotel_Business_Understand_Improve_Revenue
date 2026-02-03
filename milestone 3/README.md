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

Chart Type: Line Chart

Purpose: Shows historical booking trend

Months Displayed: January, February, March, July

Insight: Identifies seasonal dips and peaks in actual data

2️. Forecasted Bookings by Date

Chart Type: Line Chart

Data: Forecast data only (Forecast_bookings)

Purpose: Visualizes future booking demand

Insight: Shows predicted spike in upcoming months (e.g., August)

✅ This is the correct forecasting visual used in the report.

3️. Forecast vs Average Actual Bookings

Chart Type: Line Chart

Y-axis:

Forecast_bookings

Average of Total_Bookings (not sum)

Purpose: Compares predicted demand against historical average

Why Average: Prevents aggregation mismatch and false spikes

4️. Total Bookings by Season

Chart Type: Bar Chart

Purpose: Analyzes seasonal booking behavior

Insight: Identifies which season contributes most to bookings

5️. Cancellation Rate (%) by Month

Chart Type: Line Chart

Purpose: Tracks monthly cancellation trends

Insight: Helps identify high-risk months

6️. Sum of Cancellations by Month

Chart Type: Column Chart

Purpose: Shows volume of cancellations

Insight: Complements cancellation rate analysis

7️. Cancellation Rate (%) by Lead Time Bucket

Chart Type: Area / Line Chart

Lead Time Buckets:

0–7 days

8–14 days

Insight: Longer lead times show higher cancellation probability

🎛 **Filters / Slicers Used**

Season slicer (Spring, Summer, Winter)

Month slicer

Hotel Branch Key slicer

These allow interactive analysis across different dimensions.


✅ **Conclusion**

Milestone 3 successfully demonstrates:

Proper use of Python-based forecasting

Clean integration of forecast results into Power BI

Clear separation of actual vs predicted data

Insightful analysis of cancellations and seasonality

The report provides both historical insights and future demand predictions, supporting data-driven decision-making.