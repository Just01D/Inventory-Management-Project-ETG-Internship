# Inventory-Management-Project-ETG-Internship
Inventory Management System (IMS) using JSON to read data as well as to write data back in JSON format. The products in the inventory are stored using nested dictionary. 

### record.json
This json file contains the all the products and its specifications that are in your inventory.

### sales.json
This json file contains the total amount of sales you have made on each product.

### Inventory Management System.ipynb
It is a python file of the IMS. 

## Layout of the system
### Adding to the inventory
#### ADD
You can add a new product to your inventory. The new product will get saved in the inventory with the date and the time of its inclusion. If a product is already in the inventory and you try to add it in the inventory again you will get the message that the product is already there in the inventory. It also doesn't allow the user to store a negative value for the quantity.

#### EDIT
The specifications of a product already in the inventory like name, quantity can be changed and it will be updated in the inventory. For example, if a new batch of product comes in you can update its quantity in the inventory.

#### REMOVE
This function will enable the user to remove a product from the inventory.

#### LIST
This function will show you the the whole catalogue of products in your inventory with its attributes such as name, price, quantity, etc.

### Buying products from the inventory
#### Inquire about a part
While buying a product you need to enter the product ID of the product you want to buy. This function helps to know the specifications of particular product corresponding to its unique product ID.

#### Add  product to cart
This function helps us to add the required products to the cart. The cart is made of dictionary data structure so has to multiple values. This helps us to buy multiple products from the inventory at the same time.

#### Show product in the cart
Displays all the products you have selected to buy from the inventory.

#### Remove item from cart
This function helps us to remove a product from the cart and it accordingly updates the inventory and your cart about the deletion of the product from your cart i.e if you remove a roduct from the cart the quatity of the product in the inventory will be updated.

#### Checkout
It will show you your cart and produce a bill of the products in your cart. The bill will be timestamped and this is done my importing the datetime module.

#### Help
As it is a menu driven IMS, this functionality helps us to see all the option on the menu.

#### Quit 
This will quit the IMS program and come out of it.

## About the Author
My name is Justin Davis. I am second year computer science undergraduate student at D.Y Patil Institute of Technology, Pune.
E-mail: 01justindavis@gmail.com
Phone: 7972604472
LinkedIN: www.linkedin.com/in/justin-davis-2002

