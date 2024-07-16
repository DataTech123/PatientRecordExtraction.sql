
The healthcare data project tracks patient transaction records through relevant systems based on two UW and Fred Hutchinson Cancer Center site locations.

This entire project uses two CTEs (Common Table Expressions) for different tasks, followed by a final summary query. Each CTE can be independently queried from the database for the desired data extraction. 
Part 1 CTE filters patients from the specific clinical care location. Part 2 CTE fetches patient test sample records from the past five years at these two locations. 
Finally, part3 is a summary data report that calculated how many test samples patients have at the earliest and latest times during this period.

Thank you for your review and questions regarding an update to the database design and query.
