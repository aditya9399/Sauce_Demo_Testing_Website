# Sauce_Demo_Testing_Website
Task 1: Login Validation
Open SauceDemo homepage.
Automate login using:Valid Credentials: Verify successful login and redirection to /inventory.html.
Invalid Credentials: Verify error message.

Task 2: Add Items to Cart from Inventory Page
Log in with valid credentials.
Change filter to "Price (low to high)".
Add Sauce Labs Backpack and Sauce Labs Bike Light to the cart.
Verify:Items are added to the cart.Cart icon shows count as 2
.
Task 3: Add Items to Cart from Inventory Item Page
From inventory, open the Sauce Labs Onesie details page.
Add the item to the cart.
Verify:Item is added to the cart.Cart icon shows count as 3.

Task 4: Remove Items from Cart
Navigate to the cart page.
Remove the item priced between $8 and $10.
Verify: Item is removed.Cart icon reflects count as 2.

Task 5: Checkout Workflow
Click "Checkout" on the cart page.
Fill the checkout form with:
First Name: [Your Name]
Last Name: [Your Last Name]
Postal Code: [Your Postal Code]
Verify:Items appear on the checkout overview page.Print the total amount.Complete purchase by clicking "Finish".
Verify the success message: THANK YOU FOR YOUR ORDER.

Task 6: Logout Functionality
Click the menu (burger) icon.
Select "Logout".
Verify redirection to the login page.
