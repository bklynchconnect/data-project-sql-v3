What issues will you address by cleaning the data?





Queries:
Below, provide the SQL queries you used to clean your data.


SELECT * FROM orders WHERE shipregion IS NOT NULL

SELECT * FROM orders WHERE shipvia = 2

SELECT * FROM order_details WHERE discount > 0