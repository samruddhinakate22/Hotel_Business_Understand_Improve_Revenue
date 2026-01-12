This project analyzes hotel booking data to understand business performance and identify opportunities to improve revenue. 
Power BI is used for data cleaning, modeling, and visualization following a star schema approach.

Data Modeling Steps
The data model follows a Star Schema for better performance and clarity.

Fact Table-
  fact_booking

Dimension table- 
  dimension_date
  dimension_room
  dimension_hotel_branch
  dimension_customer

  
Modeling Actions- 

Created surrogate keys for all dimension tables
Established one-to-many relationships
Ensured single-direction filters from dimensions to fact table
Removed unused and redundant columns


Relationships - 

Each dimension table has a one-to-many relationship with the fact table
Filters flow from dimension → fact
No relationships exist between dimension tables
