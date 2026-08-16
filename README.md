# Sales-Analysis-report-SQL
01_Regional_Sales_Analysis alongwith query:-
<img width="707" height="713" alt="image" src="https://github.com/user-attachments/assets/23649066-a9d9-43fc-8563-2b187cf1315c" />

SELECT state, SUM(sales) AS total_sales
INTO region_sales
FROM project
GROUP BY state

02_Segment_Profit_Analysis alongwith query:-
<img width="717" height="368" alt="image" src="https://github.com/user-attachments/assets/369b4b98-747e-460f-b248-2332b842bdef" />

DROP table if exists region_sales
SELECT state, SUM(sales) as total_sales
INTO region_sales FROM project GROUP BY state

03_Customer_OrderPlaced_Analysis alongwith query:-
<img width="852" height="633" alt="image" src="https://github.com/user-attachments/assets/8207efef-7173-4c2e-ab4b-19606512ccc5" />

DROP table if exists segment_profit
SELECT segment, SUM(profit) as total_profit
INTO segment_profit FROM project GROUP BY segment


Analyzed retail sales data using SQL to extract business insights across regions, customer segments, products, and customers. Performed regional sales, segment-wise profit, customer order, and performance analysis
