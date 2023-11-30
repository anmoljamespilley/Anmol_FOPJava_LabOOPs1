'# Summary:'<br>
This e-commerce database is designed to manage suppliers, customers, products, orders, and ratings.<br>
The provided queries offer insights into customer behavior, supplier performance, and product categories. The sample data allows for testing and analysis.<br>
Additionally, a stored procedure is included to calculate average ratings for suppliers.<br>
<br>
#Database Schema:<br>
##ECOM Database:<br>
&bull; A container for the entire e-commerce database.<br>
**Supplier Table:**<br>
<br>
&bull; Stores information about suppliers, including ID, name, city, and phone number.<br>
**Customer Table:**<br>
<br>
&bull; Contains details about customers, such as ID, name, phone number, city, and gender.<br>
**Category Table:**<br>
<br>
&bull; Holds information about product categories, including ID and name.<br>
**Product Table:**<br>
<br>
&bull; Stores product details like ID, name, description, and the category it belongs to.<br>
**Supplier Pricing Table:**<br>
<br>
&bull; Manages pricing information from suppliers for various products.<br>
**Order Table:**<br>
<br>
&bull; Records order details, such as order ID, amount, date, customer ID, and pricing ID.<br>
**Rating Table:**<br>
<br>
&bull; Captures ratings given by customers for their orders.<br>
##Inserted Data:<br>
&bull; Suppliers, Customers, Categories, Products:<br>
Populated with sample data to simulate a diverse set of entities.<br>
&bull; Supplier Pricings:<br>
Reflects the pricing agreements between suppliers and products.<br>
&bull; Orders:<br>
Includes order information with associated customers and products.<br>
&bull; Ratings:<br>
Represents ratings given by customers for specific orders.<br>
<br>
##Queries:<br>
<br>
**Query 4:**<br>
&bull; Identifies the gender distribution of customers who made orders exceeding $3000.<br>
<br>
**Query 5:**<br>
&bull; Retrieves details of orders made by a specific customer (Customer ID = 2), including product names.<br>
<br>
**Query 6:**<br>
&bull; Lists suppliers with multiple pricings for different products.<br>
<br>
**Query 7:**<br>
&bull; Presents the lowest-priced product for each category.<br>
<br>
**Query 8:**<br>
&bull; Fetches order details for products ordered after a specific date (2021-10-05).<br>
<br>
**Query 9:**<br>
&bull; Lists customers whose names start with 'A' or contain 'A'.<br>
<br>
**Query 10:**<br>
&bull; Defines a stored procedure (SP) to calculate average ratings for suppliers and categorize their service.<br>
<br>
