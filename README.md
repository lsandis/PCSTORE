# Documentation - software developer kit 

E-commerce Site in PHP

Project Overview

The PCSTORE site project is developed using PHP, CSS, Bootstrap, and JavaScript. The project includes essential features for both users and administrators. On the user side, individuals can browse product categories, add products to the cart, and proceed to checkout. On the administration side, users can view sales, manage products and categories, and access daily sales reports. Users also have the option to leave comments on each product.

# System Features
Admin Control: The administrator has full control over the system, with the ability to view daily/monthly sales reports, manage users, and handle product and category information.

Sales Reports: Monthly sales reports are presented through bar graphs, offering a visual representation of sales data.

Product Management: The admin can add, view, edit, and delete products. When adding a product, details such as name, category, price, photo upload, and description are required.

Category Management: Adding a product category is a straightforward process, with the admin providing the category name.

Product Display: Product images magnify when the cursor is hovered over them, providing a closer look.

Checkout Process: The system redirects to Paypal for the checkout process.

Responsive Dashboard: A responsive dashboard is provided in the admin panel for easy site management.

# How To Run
To run this project:

1. Install a virtual server like XAMPP on your PC (for Windows).
2. Download and extract the project files.
3. Copy the main project folder to xampp/htdocs/.
4. Open a browser and go to the URL “http://localhost/phpmyadmin/”.
5. Click on the databases tab and create a database named “ecomm”.
6. Click on the import tab, browse for the "ecomm.sql" file inside the "database" folder, and click go.
7. Open a browser and go to the URL “http://localhost/ecommerce/”.
8. To access the admin panel, login from the user's login side using the admin login details.

username - admin@admin.com
password - password

Important Note
For accessing the admin panel, use the admin login details on the user's login side. Avoid going directly to "http://localhost/ecommerce/admin".
Follow steps as said.


# Features

Admin Panel: Comprehensive admin control for efficient site management.

Login/Sign Up: User authentication for secure access.

Magnify Product Image: Enhanced product viewing with image magnification.

Product Cart: Convenient shopping cart functionality for users.

Google ReCaptcha: Implementation of Google's ReCaptcha for added security.

Checkout using Paypal: Seamless and secure checkout process via Paypal.

Add, Edit, Remove, and View Products: Complete product management features.

User Management: Efficient management of user information.

View Daily/Monthly Sales: Detailed reports for sales analysis.
