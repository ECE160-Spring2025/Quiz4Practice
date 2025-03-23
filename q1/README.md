# Pi Day (10 points)

It is Pi Day, a day named after the mathematical constant that is the ratio of a circle's circumference to its diameter. In celebration of Pi Day, you decide to create an app where you can buy pies! Write a program in C to capture the main logic of this app with the following requirements:

* **(2)** Create a Pie structure that contains the following properties. Choose the most appropriate types for these properties.
  * flavor (up to 50 characters)
  * price for one pie
  * quantity

* **(2)** Create a Cart structure that contains the following properties. Choose the most appropriate types for these properties.
  * customer name (up to 50 characters)
  * number of unique pies (e.g. 1 blueberry and 2 apple pies is 2 unique pies)
  * pies (hint: an array of up to 10 pies)
  * total cost of the cart

* **(2)** Write a function that adds n Pies into the Cart. The following function prototype should be used:
  * `void addPieToCart(struct Cart *c, struct Pie *p, int n);`

* **(2)** Write a function that computes the total cost of the cart and stores it in the total cost of the cart property of the Cart. Add NYC tax to the total cost, which is 8.875% of the total cost. The following function prototype should be used:
  * `void computeCartTotal(struct Cart *c);`

* **(2)** Write a main that does the following:
  * Create a Pie with the following properties:
    * flavor: “Blueberry”
    * price for one pie: $10.00
  * Create a Pie with the following properties:
    * flavor: “Apple”
    * price for one pie: $8.50
  * Create a Cart with the following properties:
    * customer name: “Archimedes”
  * Add 1 blueberry pie and 2 apple pies into the Cart.
  * Compute the cart total.
  * Print out the contents of the cart. Be sure to include the pie’s flavor, price for one pie, and quantity in the cart.
  * Print out the cart total.