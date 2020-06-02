# Shopping-Cart
This is a project that I worked on with a group in my Java class in Fall 2019 at TCC. I moved a copy of it here so it's easier to find.

(1) Extend the ItemToPurchase class per the following specifications:

   Private fields
   string itemDescription - Initialized in default constructor to "none"
   Parameterized constructor to assign item name, item description, item price, and item quantity (default values of 0). (1 pt)
   Public member methods
   setDescription() mutator & getDescription() accessor (2 pts)
   printItemCost() - Outputs the item name followed by the quantity, price, and subtotal
   printItemDescription() - Outputs the item name and description.

(2) Create two new files:

   ShoppingCart.java - Class definition
   ShoppingCartManager.java - Contains main() method

Build the ShoppingCart class with the following specifications. Note: Some can be method stubs (empty methods) initially, to be completed in later steps.

   Private fields

   String customerName - Initialized in default constructor to "none"

   String currentDate - Initialized in default constructor to "January 1, 2016"

   ArrayList cartItems

   Default constructor

   Parameterized constructor which takes the customer name and date as parameters (1 pt)

   Public member methods

   getCustomerName() accessor (1 pt)

   getDate() accessor (1 pt)

   addItem()
       Adds an item to cartItems array. Has parameter ItemToPurchase. Does not return anything.

   removeItem()
       Removes item from cartItems array. Has a string (an item's name) parameter. Does not return anything.
       If item name cannot be found, output this message: Item not found in cart. Nothing removed.

   modifyItem()
       Modifies an item's description, price, and/or quantity. Has parameter ItemToPurchase. Does not return anything.
       If item can be found (by name) in cart, check if parameter has default values for description, price, and quantity. If not, modify item in cart.
       If item cannot be found (by name) in cart, output this message: Item not found in cart. Nothing modified.

   getNumItemsInCart() (2 pts)
       Returns quantity of all items in cart. Has no parameters.

   getCostOfCart() (2 pts)
       Determines and returns the total cost of items in cart. Has no parameters.

   printTotal()
       Outputs total of objects in cart.
       If cart is empty, output this message: SHOPPING CART IS EMPTY

   printDescriptions()
       Outputs each item's description.
