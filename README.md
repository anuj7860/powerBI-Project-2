# powerBI-Project-2 
this is a Power BI model with three tables:

State_list: This table contains information about states, including the state name and state code.
Sales_Data: This table contains sales data, including the assigned supervisor, brand, category, cost, customer name, order date, order number, product, and quantity.
Supervisor: This table contains information about supervisors, including their image URL and supervisor name.
The relationships between the tables are as follows:

State_list has a one-to-many relationship with Sales_Data based on the State_Code column. This means that each state can have multiple sales records.
Sales_Data has a one-to-many relationship with Supervisor based on the Assigned Supervisor column. This means that each supervisor can have multiple sales records.
Based on this information, we can see that Power BI is being used to analyze sales data. The model allows users to filter sales data by state, supervisor, brand, category, customer, product, and order date.

It is unclear from the image what the specific goals of the analysis are. However, the model suggests that the user is interested in understanding sales trends, performance by state, and the performance of individual supervisors.

Here are some potential reports that could be created from this model:

A report showing total sales by state.
A report showing sales trends over time.
A report showing the top-performing supervisors.
A report showing the performance of different product categories.

# project visuals :
