# Hotel_Business_Understand_Improve_Revenue
AI Driven Revenue Analysis for Hotels
1. Dataset Description

The dataset contains daily hotel performance data, including bookings, revenue, room occupancy, and guest information. It tracks financial metrics like ADR, RevPAR, total revenue, expenses, and profit, as well as operational details such as check-ins, no-shows, and cancellations. Marketing spend, booking channels, guest type, and seasonality are included to analyze demand patterns and improve revenue management.

2. Data Modeling Steps

Dimension Tables Created :

Hotel Branch Dimension: HotelBranch_Key, Total_Rooms
Room Dimension: Room_Key, Room_Category
Date Dimension: Date_Key, Date, Month, Year, Weekday, Season, Holiday

Fact Table Created:

Fact_Booking : created Booking Duration, Room Category, Stay Type (Short / Medium / Long)


Calculated Measures in Power BI -
   Total Bookings = SUM(New_Bookings)
   Total Revenue = SUM(Revenue)
   Profit = Total Revenue – Total Costs

Star Schema Applied -

Fact table linked to dimension tables using 1: relationships*
Ensures efficient reporting and clear data flow

3. key observations:
   
standard rooms have high occupancy but lower revenue per room.
Most bookings are online, suggesting potential for loyalty programs and targeted marketing.
