# Hotel Revenue Analysis 

This project analyzes hotel booking data to understand business performance and identify opportunities to improve revenue.  
Power BI is used for data cleaning, modeling, and visualization, following a star schema approach.


## Data Model Overview

The model follows a **Fact–Dimension** approach where `fact_booking` is the central table connected to multiple dimension tables:

- **fact_booking** (Central fact table)  
- **dimension_customer**  
- **dimension_date**  
- **dimension_room**  
- **dimension_hotel_branch**  

This structure enables efficient slicing and dicing of metrics by customer, date, room category, and hotel branch.



## Data Modeling Steps

The data model follows a **Star Schema** for better performance and clarity.

### Fact Table
- `fact_booking`

### Dimension Tables
- `dimension_date`  
- `dimension_room`  
- `dimension_hotel_branch`  
- `dimension_customer`  

### Modeling Actions
- Created surrogate keys for all dimension tables  
- Established one-to-many relationships  
- Ensured single-direction filters from dimensions to fact table  
- Removed unused and redundant columns  


## Key Analysis Use Cases

- Revenue analysis by season, month, and hotel branch  
- Customer segmentation by country and type  
- **Standard rooms** have the highest bookings, followed by **Economy**; **Premium** has the least  
- **Economy rooms** generate the highest revenue, even with slightly fewer bookings than Standard  
- **Premium rooms** contribute minimally to both bookings and revenue  
- **Medium Stay** is the most common stay type; Long Stay bookings are very low  



## Relationships

- Each dimension table has a **one-to-many relationship** with the fact table  
- Filters flow from **dimension → fact**  
- No relationships exist between dimension tables  



