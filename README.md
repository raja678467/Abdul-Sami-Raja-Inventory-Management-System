This Python script provides a complete implementation of the Inventory Management System with the following features:

User Authentication and Role-based Access Control:

Admin users have access to product management features like adding, editing, deleting, and adjusting stock levels.
User role users have read-only access to view and search for products.
Product Management:

Admins can perform various product operations such as adding, editing, deleting, viewing, searching, and adjusting stock levels for products.
Key Points of the System:
Classes:

User: Represents a user with username, password, and role.
Product: Represents a product with product_id, name, category, price, and stock_quantity.
InventoryManagementSystem: Main class that handles product and user operations, and manages user roles and authentication.
Main Features:

Admin Operations:
Add Product: Allows admins to add a new product to the inventory.
Edit Product: Allows editing details of an existing product.
Delete Product: Removes a product from the inventory.
View Products: Lists all products and highlights low-stock items.
Search Product: Enables searching for products by name or category.
Adjust Stock: Modifies the stock quantity of a product.
User Operations:
View Products: Users can view the list of products.
Search Product: Users can search for products by name or category.
Low Stock Alerts:

Products below a stock threshold (default is 10) are marked as "(Low stock)" in the product view list.
Sample Login Credentials:
Admin: Username: admin, Password: adminpass
User: Username: user, Password: userpass
