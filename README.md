
The healthcare data project tracks patient transaction records through patient service systems(this is just an example of a patient service system)based on two UW and Fred Hutchinson Cancer Center site locations.

This entire project uses two CTEs (Common Table Expressions) for different tasks, followed by a final summary query. Each CTE can be independently queried from the database for the desired data extraction. 

Part 1: CTE filters patients from the specific clinical care location.

Part 2: CTE fetches patient test sample records from the past five years at these two locations. 

Part 3 : A summary data report that calculated how many test samples patients have at the earliest and latest time during this period.

Thank you for your review and questions regarding an update to the database design and query.
