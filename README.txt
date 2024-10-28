Product Catalog System
This project is a Product Catalog System developed using Spring Boot, Spring Data JPA, and Thymeleaf. The application allows users to add new products and display a catalog of all products, categorized by product name, price, and category.

Features
Home Page: Provides options for users to either add a new product or view the product catalog.
Add Product: Users can enter product details, including name, price, and category, through a form. The details are then saved to the database.
Display Product: Users can view all products stored in the database in a tabular format on a single page.
Endpoints and Functionalities
Home Page

URL: /homePage
Description: Displays the home page with options to add a product or view the product catalog.
Template: index.html
Add Product Page

URL: /addProductDetails
Description: Displays a form where users can input product details (name, price, category).
Template: addNewProduct.html
Save Product

URL: /save
Method: POST
Description: Saves the new product details to the database and redirects to the homepage.
Display Product Catalog

URL: /getProductDetails
Description: Displays all products from the database in a table format.
Template: getProductDetails.html
Technologies Used
Spring Boot: For building and managing the backend.
Spring Data JPA: For database interactions and ORM.
Thymeleaf: For rendering dynamic HTML pages.
MySQL: Used as the database to store product information.