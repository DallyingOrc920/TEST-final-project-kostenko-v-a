***Microgreen***

***Vision***

"Microgreen" is a is web-application which allows users to record information about vegetable greens.

Application should provide:

* Display list of orders and their status;
* Updating the list of orders (adding);
* Display list of clients;
* Updating the list of clients (adding, editing, removing);
* Display list of product;
* Filtering by cost microgreens;
* Filtering by alphabeth.

***1. Orders Product***

***1.1 Display list of orders and their status***

The mode is designed to view the list of orders, if it possible to display the number of orders for a specified
period of time.

***Main scenario:***

* User selects “Orders & status”;
* Application displays list of Orders and their status.

![Orders and their status](https://github.com/DallyingOrc920/TEST-final-project-kostenko-v-a/blob/main/Documentation/Diagrams_T/abc.png?raw=true)

Pic. 1.1 View the Orders list.

The list displays the following columns:

* ID - unique client number and order date;
* Status - current order status (if click on tringle you can see, what will be the next order status);
* Goods - goods included in the order;
* Order cost - order cost;
* Customer - the person who owns the goods.

***1.2 Add order***

***Main scenario:***

* User clicks the “Create order” button in the order & status and he sees the details of the order;
* User enters order data and presses “Create order” button;
* If user cliks "Add new row" a new row is created
* If any data is entered incorrectly, incorrect data messages are displayed;
* If error occurs, then error message is displaying;
* If new order record is successfully added, then list of orders with added records is displaying.

![Add order](https://github.com/DallyingOrc920/TEST-final-project-kostenko-v-a/blob/main/Documentation/Diagrams_T/Add_order.png?raw=true)

Pic. 1.2 Add order.

***Cancel operation scenario:***

* User clicks the “Add order” button in the order list view mode;
* Application displays the goods which will be order by the client;
* User enters order data and presses “Cancel” button;
* Data don’t save in data base, then list of orders records is displaying to user;
* If the user selects the menu item "Orders & status”, ”Product, Description & Remaining Quantity” or "Clients", the data will not be saved to the database.

Constraints for data validation:

* Total price – maximum length of 20 characters;
* Delivery details – maximum length of 40 characters;

***2. Product, Descriptions and Remaining Quantity***

***2.1 Product & Descriptions***

***Main scenario:***

* User clicks the “Product, Description and Remaining Quantity” and he sees the details of product;
* If the user clicks on the pencil, he can change the product;
* If the user clicks on the wastebasket, he can delite the product;
* Application displays confirmation dialog “Please confirm delete product?”;
* User press “Cancel” button;
* List of clients without changes is displaying.

![Product, Descriptions and Remaining Quantity](https://raw.githubusercontent.com/DallyingOrc920/TEST-final-project-kostenko-v-a/35d292ce16dd8702ce0e25eaa53dcd1d97eb2255/Documentation/Diagrams_T/Product_and_Descriprion.png?token=AY57SHRTAWKB2WOSWM6VGFDD6PLRI)

Pic. 2.1 Product, Descriptions and Remaining Quantity.

The list displays the following columns:

* Product - name of product;
* Description - detailed product description;
* Quantity - quantity of goods available;
* Price for one - price for one unit of goods.

***2.2 Add order***

***Main scenario:***

* User clicks the “Add order” button in the Product, Descriptions and Remaining Quantity and he sees the details of the order;
* If user cliks "Add order" a new order is created;
* If any data is entered incorrectly, incorrect data messages are displayed;
* If error occurs, then error message is displaying;
* If new order record is successfully added, then list of orders with added records is displaying.

![Add Product and Descriptions add order button](https://raw.githubusercontent.com/DallyingOrc920/TEST-final-project-kostenko-v-a/d1fa0c3af56c9ad658414b3081aa1ad49edbabe4/Documentation/Diagrams_T/Product_and_Descriprion_Add_Order_button.png?token=AY57SHW4YIE3N6WRNKGUUPLD6PLTC)

Pic. 2.2 Product and Descriptions Add order button

***Cancel operation scenario:***

* User clicks the “Add order” button in the order list view mode;
* Application displays the goods which will be order by the client;
* If the user checks the order details and presses “Cancel” button;
* Data don’t save in data base, then list of orders records is displaying to user;
* If the user selects the menu item "Orders & status”, ”Product, Description & Remaining Quantity” or "Clients", the data will not be saved to the database.

Constraints for data validation:

* Quantity – maximum length of 25 characters;
* Price for one – maximum length of 15 characters;

***3. Clients list***

***3.1 Displaying the list of clients***

***Main scenario:***

* User selects item “Clients”;
* Application displays list of clients.
* If the user clicks on the pencil, he can change first and last name;
* If the user clicks on the wastebasket, he can delete first and last name;
* Application displays confirmation dialog “Please confirm delete client?”;
* User press “Cancel” button;
* List of clients without changes is displaying.

![Add Clients diagram](https://github.com/DallyingOrc920/TEST-final-project-kostenko-v-a/blob/main/Documentation/Diagrams_T/Clients.png?raw=true)

Pic. 3.1 Displaying list of clients

The list displays the following columns:

* First name - client’s first name;
* Last name - client’s last name;
* Company - name of company;
* ID - unique client number.

Constraints for data validation:

* First name – maximum length of 30 characters;
* Last name – maximum length of 30 characters;

***3.2 Add button***

***Main scenario:***

* User clicks the “Add” button in the Displaying the list of clients and he sees the details of the client;
* If user cliks "Save" a new client is created;
* If any data is entered incorrectly, incorrect data messages are displayed;
* If error occurs, then error message is displaying;
* If new client record is successfully added, then list of clients with added records is displaying.

![Add button in Displaying list of clients](https://github.com/DallyingOrc920/TEST-final-project-kostenko-v-a/blob/main/Documentation/Diagrams_T/Clients_button.png?raw=true)

Pic. 3.2 Button in Displaying list of clients

The list displays the following columns:

* First name - client’s first name;
* Last name - client’s last name;
* Company - name of company;
* ID - unique client number.

***Cancel operation scenario:***

* User clicks the “Save” button in the Displaying the list of clients;
* Application displays the list of clients with added;
* If the user presses “Cancel” button data don’t save in data base;
* If the user selects the menu item "Clients”, ”Product, Description & Remaining Quantity” or "Orders & status", the data will not be saved to the database.

Constraints for data validation:

* First name – maximum length of 30 characters;
* Last name – maximum length of 30 characters.
