# Sales-Analysis-report
01_Regional_Sales_Analysis:-
<img width="707" height="713" alt="image" src="https://github.com/user-attachments/assets/23649066-a9d9-43fc-8563-2b187cf1315c" />

select state, sum(sales) as total_sales
into region_sales
from project
group by state

02_Segment_Profit_Analysis
<img width="735" height="635" alt="image" src="https://github.com/user-attachments/assets/34215f04-a975-4960-85b7-cbaf8ac5b038" />
drop table if exists region_sales
select state, sum(sales) as total_sales
into region_sales from project group by state

04_Customer_Order_Analysis
05_Product_Analysis
06_Performance_Analysis

Analyzed retail sales data using SQL to extract business insights across regions, customer segments, products, and customers. Performed regional sales, segment-wise profit, customer order, and performance analysis
