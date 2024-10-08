# Product Manager

## Description
A PHP project, following along with our web development 2 lectures, for managing products with CRUD (Create, Read, Update, Delete) functionality. Integrated with a MySQL database via phpMyAdmin.

## Features
- Create new products
- Read product details
- Update existing products
- Delete products

## Installation
1. Clone the repository:  
   `git clone https://github.com/nekolaiv/product-manager.git`
   
2. Move the project directory to the XAMPP `htdocs` folder:  
   `mv product-manager /path/to/xampp/htdocs/`
   
3. Navigate to the `sql` folder and import the SQL database schema using phpMyAdmin:
   - Open phpMyAdmin in your browser (usually at `http://localhost/phpmyadmin`).
   - Create a new database.
   - Click on the "Import" tab.
   - Choose the SQL file `products.sql` located in `product-manager/sql/` and click "Go".

## Usage
- Start your XAMPP server.
- Access the application at `http://localhost/Product-Manager`.

## Contributing
Feel free to submit a pull request for improvements or bug fixes.

## License
This project is licensed under the MIT [License](LICENSE).
