# Details
we have our tables in Big query
Project_id = my_muscle_chef
Customer Data : dataset_id = "Customer" ,table_id = "customer" 
schema = {CustomerID: INTEGER
First_Name: STRING
Last_Name: STRING
Age: INTEGER
Country: STRING}


Orders Data : dataset_id = "Orders", table_id = "orders"
scheam ={
Order_ID: INTEGER 
Item: STRING 
Amount: FLOAT 
Customer_ID: STRING 
}


Shipping data : dataset_id = "Shippings", table_id = "shippings"
schema ={
Shipping_ID: INTEGER 
Status: STRING 
Customer_ID: INTEGER 
}

