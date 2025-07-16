# Inventory-Manager-Lite

📦 Inventory Manager Lite
Inventory Manager Lite is a simple, single-page web application designed to help you track product stock, manage reorder levels, identify out-of-stock items, and record sales. It's built with HTML, Tailwind CSS for styling, and vanilla JavaScript for functionality.

💡 Concept
This application provides a straightforward way to keep an eye on your product inventory. You can easily add new products, update existing ones, track their current stock, and get alerts when stock levels are low or depleted. The newly added sales feature allows you to deduct stock directly from your inventory.

🔧 Features
Add/Edit/Delete Inventory:

Add new products with a name, category, initial stock, and a reorder level.

Edit existing product details directly from the inventory list.

Delete products from your inventory with a confirmation step.

Stock Management (New!):

Record Sales: A dedicated section to select a product and enter the quantity sold, automatically deducting from the current stock.

Real-time stock updates reflected in the inventory list.

Reorder Alerts:

Products with a stock level at or below their defined reorder level are highlighted in yellow.

Products that are completely out of stock (stock = 0) are highlighted in red.

Search by Category:

Quickly filter your inventory list by entering a category name in the search bar.

Export CSV:

Download your entire inventory data as a CSV file for external use or record-keeping.

🚀 How to Use
Open the Application: Simply open the index.html file in your web browser.

Add Products:

Use the "Add New Product" form.

Fill in the Product Name, Category, Stock, and Reorder Level.

Click "Add Product".

Edit Products:

In the "Inventory List" table, click the "Edit" button next to the product you wish to modify.

The form will populate with the product's current details. Make your changes and click "Update Product".

Click "Cancel Edit" to discard changes and revert to "Add New Product" mode.

Delete Products:

In the "Inventory List" table, click the "Delete" button next to the product you wish to remove.

Confirm your action in the pop-up modal.

Record Sales:

Go to the "Sell Product" section.

Select a product from the "Select Product" dropdown.

Enter the "Quantity Sold".

Click "Record Sale". The stock will be updated, and a confirmation message will appear.

Search Inventory:

Type a category name into the "Search by category..." field to filter the table.

Export Data:

Click the "Export CSV" button to download your current inventory.

🔮 Future Enhancements
Data Persistence: Implement local storage or a backend (e.g., Firebase) to save inventory data so it persists even after closing the browser.

Purchase/Restock Feature: Add a dedicated feature to increase product stock.

Reporting: Basic reports on sales, low stock items, etc.

User Interface Improvements: More advanced filtering, sorting, and pagination for large inventories.

Notifications: Visual or auditory alerts for reorder points.
