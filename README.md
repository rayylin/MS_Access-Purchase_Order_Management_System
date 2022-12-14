# MS-Access-Purchase-Order-Management-System
This project will use MS Access to manage purchase order data

# Raw Data
There are 10934 observations in the dataset.
The original data has been preprocessed and removed all personal information. We need to be careful when preprocessing the data. For example, currency type values need to deal with $, ',', and '.00' and then remove the rows that are not an integer.

![image](https://user-images.githubusercontent.com/58899897/196317143-e447ceb1-765a-4c0a-b607-3bdef6c59591.png)

# Data Partition
To better manage the data and maintain data consistency, we divide the raw data into four tables.
Customer table: Customer ID,	Customer Name,	Address, and	State
Invoice table: PO ID, Product ID, and Quantity
PO data table: PO ID, Order Date, Shipping Date, Delivery Method, Revenue, Profit, and Customer ID
Product table: Product ID, Product Name, Product Category, and Unit Price

We need to specify the relationships among tables so that data can refer to data in other tables. The relationship is shown below.

![image](https://user-images.githubusercontent.com/58899897/196317952-301d45fc-648f-4c8f-b59e-c459104a258d.png)

# Create a form to manage data
We could use form wizard to create a form and perform data manipulation. The form would look like this, and there is an invoice subform.

![image](https://user-images.githubusercontent.com/58899897/196319446-a7e2e1a2-fb25-44e4-96ff-23f3f234a5fa.png)

Then we could use this form to manage our database

![image](https://user-images.githubusercontent.com/58899897/196319809-8a191103-f03c-4f74-bec8-1767deb76d6c.png)

The data we input will be automatically updated to tables, and we do not need to perform this task manually.

![image](https://user-images.githubusercontent.com/58899897/196319991-52244824-473c-455a-b3fc-6402f366ef59.png)

We could use query design and report wizard to generate reports

![image](https://user-images.githubusercontent.com/58899897/196320464-b1801a7e-4d83-4530-ad00-7fa33d06d253.png)

![image](https://user-images.githubusercontent.com/58899897/196320730-4f0f2c29-a2af-45b3-9e6c-084fd70b1b7a.png)

![image](https://user-images.githubusercontent.com/58899897/196320875-3dfb2430-ac6e-411d-94e0-9da14c12cbee.png)




