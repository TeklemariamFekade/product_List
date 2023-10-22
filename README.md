****Product List System (CRUD Operations)***********************

Features
- Create new products with details such as name, price, and quantity and description.
- Read and display a list of all products in the system.
- Update the details of existing products.
- Delete products from the system.
  
**Requirements**

  
-PHP version 7.0 or higher.

  MySQL database.
  
Installation

Clone the repository:

bash

Copy
git clone (https://github.com/TeklemariamFekade/product_List.git)

Import the database

Create a new MySQL database.

Import the product_managment.sql file located in the repository to set up the required database schema.

Configure the database connection

Open dbcon.php file.
Update the database connection details such as host, username, password, and database name according to your MySQL configuration.
Start the application

Run a local server or configure your web server to serve the PHP files.
Access the application in your browser using the appropriate URL.


**Usage**
**Home Page**

The home page displays a list of all products in the system.
Each product is listed with its name, price, description.
![image](https://github.com/TeklemariamFekade/product_List/assets/106950388/e33a873e-06fe-454c-9848-7cd387bea47e)


Click on the "Add Product" link in the navigation menu to add a new product.
Provide the required details such as name, price,  quantity and description in the form.
Click the "Add" button to add the product to the system.
You will be redirected to the home page, where the new product will be displayed.


**View Product Details**

Click on the View Detail in the home page to view its details.
The product details page shows the name, price, and quantity, Description of the selected product.
You can also see an "order" button to order products.

![image](https://github.com/TeklemariamFekade/product_List/assets/106950388/564a7686-4133-4aa2-b638-3f5d1401dfdd)


**Update Products Product**

 click on the "Edit" button to modify the product details.
Update the desired fields in the form.
Click the "update" button to save the changes.
You will be redirected to the details page with the updated information.

![image](https://github.com/TeklemariamFekade/product_List/assets/106950388/ac9a8cd0-8ab1-4982-9135-0d3c9c827ac2)




**Delete Products**

 click on the "Delete" button to remove the product from the system.
You will be redirected to the home page, and the product will be removed from the list.
Contributing
Contributions to this project are welcome. If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

**In stock products**
click instock button to display products found in the stock
![image](https://github.com/TeklemariamFekade/product_List/assets/106950388/36bb2a0e-9228-43cf-8187-f1ff2b66bf44)



**out of stock products**
click instock button to display products that are out of the stock
![image](https://github.com/TeklemariamFekade/product_List/assets/106950388/fc62e27b-1d60-42db-b819-548d4ab8a795)


License
This project is licensed under the MIT License.



