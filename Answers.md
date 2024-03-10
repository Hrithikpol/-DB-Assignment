# -DB-Assignment
Assignment
1. The relationship between the "Product" and "Product_Category" entities is one-to-many. This means that one product can belong to one category, but a category can have many products.
2. Here are two ways to ensure that each product in the "Product" table has a valid category assigned to it -
   1. Add a foreign key constraint to the "category_id" field in the "Product" table.
   2. Make the "category_id" field in the "Product" table not nullable.
