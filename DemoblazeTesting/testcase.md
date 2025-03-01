TC_001
Summary: Successful registration with valid data

Preconditions: The user must be on the homepage of the site https://www.demoblaze.com/index.html.

Test Steps:

Click on Sign Up.
Enter a valid username (e.g., testuser123).
Enter a valid password (e.g., Test@1234).
Click the Sign Up button.
Expected Result:
The user should be successfully registered (a confirmation message should appear), and the system should allow login with the new credentials.

Actual Result: To be filled after execution

Status: In Process

TC_002
Summary: Unsuccessful registration with empty fields

Preconditions: The user must be on the homepage of the site https://www.demoblaze.com/index.html.

Test Steps:

Click on Sign Up.
Leave the Username field empty.
Leave the Password field empty.
Click the Sign Up button.
Expected Result:
The user should not be able to register with empty fields. A pop-up message should appear, warning about incorrect input, or the form validation should prevent submission.

Actual Result: To be filled after execution

Status: In Process

TC_003
Summary: Unsuccessful registration with boundary testing

Preconditions: The user must be on the homepage of the site https://www.demoblaze.com/index.html.

Test Steps:

Click on Sign Up.
Enter a very long username (e.g., 50+ characters).
Enter a single-character password (e.g., "G").
Click the Sign Up button.
Expected Result:
The form should validate the input. Either an error message should be displayed, or input should be restricted to allowed limits.

Actual Result: To be filled after execution

Status: In Process

TC_004
Summary: Unsuccessful registration with invalid characters

Preconditions: The user must be on the homepage of the site https://www.demoblaze.com/index.html.

Test Steps:

Click on Sign Up.
Enter an invalid username (e.g., special characters "?!№").
Enter a password with only numbers (e.g., "12345").
Click the Sign Up button.
Expected Result:
The form should reject invalid input. A validation message or a pop-up should warn the user about incorrect data entry.

Actual Result: To be filled after execution

Status: In Process

TC_005
Summary: Registration attempt with an existing username

Preconditions:

The user must be on the homepage of the site https://www.demoblaze.com/index.html.
The Username (e.g., testuser123) is already registered in the system.
Test Steps:

Click on Sign Up.
Enter an already registered Username (e.g., testuser123).
Enter a valid password.
Click the Sign Up button.
Expected Result:
The system should prevent registration with an existing username.
A pop-up or error message should appear, stating that the username is already taken.

Actual Result: To be filled after execution

Status: In Process

TC_006
Summary: Successful login with correctly entered registered user credentials

Preconditions:

The user must be on the homepage of the site https://www.demoblaze.com/index.html.
The user already has an account (valid username and password).
Test Steps:

Click on Log In.
Enter a registered username (e.g., testuser123).
Enter a valid password.
Click the Log In button.
Expected Result:
🔹 The user successfully logs into the system.
🔹 The username is displayed in the top right corner.
🔹 The Log In / Sign Up buttons change to Log Out.

Actual Result: To be filled after execution

Status: In Process

TC_007
Summary: Unsuccessful login attempt with a non-existent user

Preconditions:

The user must be on the homepage of the site https://www.demoblaze.com/index.html.
Test Steps:

Click on Log In.
Enter a non-registered username (e.g., POP123).
Enter a random password.
Click the Log In button.
Expected Result:
🔹 The user cannot log in.
🔹 A pop-up message appears, requesting valid credentials.
🔹 Field validation prevents login with non-existent credentials.

Actual Result: To be filled after execution

Status: In Process

TC_008
Summary: Unsuccessful login attempt with empty fields

Preconditions:

The user must be on the homepage of the site https://www.demoblaze.com/index.html.
Test Steps:

Click on Log In.
Leave the Username field empty.
Leave the Password field empty.
Click the Log In button.
Expected Result:
🔹 The user cannot log in.
🔹 A warning pop-up appears or field validation prevents login.

Actual Result: To be filled after execution

Status: In Process

TC_009
Summary: Unsuccessful login attempt with incorrect password

Preconditions:

The user must be on the homepage of the site https://www.demoblaze.com/index.html.
The user already has an account (valid username and password).
Test Steps:

Click on Log In.
Enter a registered username (e.g., testuser123).
Enter a random incorrect password (e.g., 1090).
Click the Log In button.
Expected Result:
🔹 The user cannot log in.
🔹 A warning pop-up appears or field validation prevents login.

Actual Result: To be filled after execution

Status: In Process

TC_010
Summary: Unsuccessful login attempt with boundary values

Preconditions:

The user must be on the homepage of the site https://www.demoblaze.com/index.html.
Test Steps:

Click on Log In.
Enter a very long username (e.g., 50+ characters).
Enter a one-character password (e.g., "A").
Click the Log In button.
Expected Result:
🔹 The system should validate the input fields.
🔹 A warning pop-up should appear if the username or password exceeds the allowed limit.

Actual Result: To be filled after execution

Status: In Process

TC_011
Summary: Checking the "Forgot Username" functionality

Preconditions:

The user must be on the homepage of the site https://www.demoblaze.com/index.html.
The system must have a Forgot Username option (if available).
Test Steps:

Click on Log In.
Look for the "Forgot Username" link (if present).
Click on the "Forgot Username" link.
Enter the registered email associated with the account.
Click Submit.
Expected Result:
🔹 The system should send an email with the registered username or display a message with further instructions.
🔹 If the feature is not available, it should be reported as a missing functionality.

Actual Result: To be filled after execution

Status: In Process

TC_012
Summary: Checking the "Forgot Password" functionality

Preconditions:

The user must be on the homepage of the site https://www.demoblaze.com/index.html.
The system must have a Forgot Password option.
Test Steps:

Click on Log In.
Look for the "Forgot Password" link.
Click on the "Forgot Password" link.
Enter the registered email associated with the account.
Click Submit.
Check the email for a password reset link.
Expected Result:
🔹 The system should send a password reset link to the registered email.
🔹 If the feature is not available, it should be reported as a missing functionality.

Actual Result: To be filled after execution

Status: In Process

TC_013
Summary: User account lockout after multiple failed login attempts

Preconditions:

The user has an account (valid username and password).
The user is on the homepage https://www.demoblaze.com/index.html
Test Steps:

Click "Log In".
Enter an existing username (e.g., testuser123).
Enter an incorrect password (e.g., 12345).
Click the "Log In" button.
Repeat steps 2-4 five times.
Try logging in again with the correct credentials.
Expected Result:
🔹 If the system has security measures, the user receives a warning about temporary account lockout.
🔹 If there is no lockout mechanism, the user should be able to log in after entering the correct credentials.

Actual Result: To be filled after execution

Status: In Process

TC_014
Summary: Checking if login session persists after page refresh

Preconditions:

The user has an account (valid username and password).
The user is on the homepage https://www.demoblaze.com/index.html
Test Steps:

Click "Log In".
Enter an existing username (e.g., testuser123).
Enter the correct password.
Click the "Log In" button.
Wait for successful login.
Refresh the page (press F5 or reload the browser tab).
Expected Result:
🔹 If the site supports session persistence, the user remains logged in.
🔹 If session persistence is not implemented, the user must log in again.

Actual Result: To be filled after execution

Status: In Process

TC_015

Summary: Navigation check for the "Phones" category

Preconditions: The user is on the homepage https://www.demoblaze.com/index.html
Test Steps:

Click on the "Phones" category in the left menu.

Verify that only products from the "Phones" category are displayed on the page.

Expected Result: The site correctly filters products from the "Phones" category.

Actual Result: To be filled after execution

Status: In Process

TC_016

Summary: Navigation check for the "Laptops" category

Preconditions: The user is on the homepage https://www.demoblaze.com/index.html
Test Steps:

Click on the "Laptops" category in the left menu.

Verify that only products from the "Laptops" category are displayed on the page.

Expected Result: The site correctly filters products from the "Laptops" category.

Actual Result: To be filled after execution

Status: In Process

TC_017

Summary: Navigation check for the "Monitors" category

Preconditions: The user is on the homepage https://www.demoblaze.com/index.html

Test Steps:

Click on the "Monitors" category in the left menu.

Verify that only products from the "Monitors" category are displayed on the page.

Expected Result: The site correctly filters products from the "Monitors" category.

Actual Result: To be filled after execution

Status: In Process

TC_018

Summary: Navigation check for "Home"

Preconditions: The user must be on the "Laptops" category page.

Test Steps:
1.	Click on the "Home" button.
2.	Verify that the homepage is displayed.
3.	
Expected Result: The website correctly navigates back to the homepage.

Actual Result: To be filled after execution

Status: In Process

TC_019

Summary: Navigation check for "Contact"

Preconditions: The user must be on the "Phones" category page.

Test Steps:
1.	Click on "Contact" in the top navigation menu.
2.	Verify that the appropriate pop-up window appears.
   
Expected Result: The "Contact" pop-up window opens.

Actual Result: To be filled after execution

Status: In Process

TC_020

Summary: Navigation check for "About us"

Preconditions: The user must be on the "Phones" category page.

Test Steps:
1.	Click on "About us" in the top navigation menu.
2.	Verify that the appropriate pop-up window appears.
   
Expected Result: The "About us" pop-up window opens.

Actual Result: To be filled after execution

Status: In Process

TC_021

Summary: Navigation check for "Cart"

Preconditions: The user must be on the homepage of  https://www.demoblaze.com/index.html

Test Steps:
1.	Click on "Cart" in the top navigation menu.
2.	Verify that the cart page is displayed.
   
Expected Result: The cart page opens.

Actual Result: To be filled after execution

Status: In Process

TC_022

Summary: Navigation check for "Log in"

Preconditions: The user must be on the homepage of  https://www.demoblaze.com/index.html

Test Steps:
1.	Click on "Log in" in the top navigation menu.
2.	Verify that the appropriate pop-up window appears.
   
Expected Result: The "Log in" pop-up window opens.

Actual Result: To be filled after execution

Status: In Process

TC_023

Summary: Navigation check for "Sign up"

Preconditions: The user must be on the homepage of  https://www.demoblaze.com/index.html

Test Steps:
1.	Click on "Sign up" in the top navigation menu.
2.	Verify that the appropriate pop-up window appears.
   
Expected Result: The "Sign up" pop-up window opens.

Actual Result: To be filled after execution

Status: In Process

TC_024

Summary: Add one product from "Phones" category to cart

Preconditions: The user must be on the homepage of the site https://www.demoblaze.com/index.html and navigate to the "Phones" category.

Test Steps:

Select the product "Samsung galaxy s6".

Click on the "Add to cart" button.

Confirm the pop-up message.

Go to the cart.

Expected Result: The selected product is successfully added to the cart and displayed in the cart list.

Actual Result: To be filled after execution

Status: In Process

TC_025

Summary: Add one product from "Laptops" category to cart

Preconditions: The user must be on the homepage of the site https://www.demoblaze.com/index.html and navigate to the "Laptops" category.

Test Steps:

Select the product "Sony vaio i5".

Click on the "Add to cart" button.

Confirm the pop-up message.

Go to the cart.

Expected Result: The selected product is successfully added to the cart and displayed in the cart list.

Actual Result: To be filled after execution

Status: In Process

TC_026

Summary: Add one product from "Monitors" category to cart

Preconditions: The user must be on the homepage of the site https://www.demoblaze.com/index.html and navigate to the "Monitors" category.

Test Steps:

Select the product "Apple monitor 24".

Click on the "Add to cart" button.

Confirm the pop-up message.

Go to the cart.

Expected Result: The selected product is successfully added to the cart and displayed in the cart list.

Actual Result: To be filled after execution

Status: In Process

TC_027

Summary: Add multiple products to the cart

Preconditions: The user must be on the homepage of the site https://www.demoblaze.com/index.html.

Test Steps:

Add "Samsung galaxy s6" from "Phones" category.

Add "Sony vaio i5" from "Laptops" category.

Add "Apple monitor 24" from "Monitors" category.

Go to the cart.

Expected Result: All selected products are successfully added to the cart and displayed in the cart list.

Actual Result: To be filled after execution

Status: In Process

TC_028

Summary: Remove one product from the cart

Preconditions: The user must have at least two products in the cart.

Test Steps:

Go to the cart.

Remove the product "Samsung galaxy s6" from the cart.

Expected Result: The selected product is removed from the cart, and the remaining products are still present.

Actual Result: To be filled after execution

Status: In Process

TC_029

Summary: Remove all products from the cart

Preconditions: The user must have at least two products in the cart.

Test Steps:

Go to the cart.

Remove all products from the cart one by one.

Expected Result: The cart becomes empty, and no products are displayed.

Actual Result: To be filled after execution

Status: In Process

TC_030

Summary: Check clicking the Place Order button when the cart is empty

Preconditions: The cart is empty.

Test Steps:

Go to the cart.
Click the Place Order button.

Expected Result: A message or pop-up should appear indicating that the cart is empty and the order cannot be placed.

Actual Result: To be filled after execution

Status: In Process

TC_031

Summary: Check if the products remain in the cart after page refresh

Preconditions: There is at least one product in the cart.

Test Steps:

Go to the cart, where there is at least one product.
Refresh the page.
Check if the product(s) remain in the cart after the page refresh.

Expected Result: Products should remain in the cart after refreshing the page.

Actual Result: To be filled after execution

Status: In Process

TC_032

Summary: Check if the products remain in the cart after logging out and logging back in

Preconditions: There is at least one product in the cart. The user is logged in.

Test Steps:

Go to the cart, where there is at least one product.
Log out (click Log out).
Log back into the account.
Check if the products are still in the cart after logging back in.

Expected Result: Products should remain in the cart even after logging out and logging back in.

Actual Result: To be filled after execution

Status: In Process

TC_033

Summary: Check order placement

Preconditions: There must be at least one product in the cart.

Test Steps:

Go to the cart.
Click the Place order button.
In the pop-up, fill in all the fields correctly: name, address, city, postal code, country, and phone number.
Click the Purchase button.

Expected Result: After clicking Purchase, a pop-up should appear confirming the successful order placement.

Actual Result: To be filled after execution

Status: In Process

TC_034

Summary: Check Purchase button behavior when fields are empty

Preconditions: The user must have at least one item in the cart and be on the order page.

Test Steps:

Go to the cart.
Click the Place order button.
In the pop-up, leave all fields empty.
Click the Purchase button.

Expected Result: The system should show an error or a message prompting the user to fill out all the fields correctly. The order should not be placed.

Actual Result: To be filled after execution

Status: In Process

TC_035

Summary: Check Purchase button behavior when incorrect data is entered

Preconditions: The user must have at least one item in the cart and be on the order page.

Test Steps:

Go to the cart.
Click the Place order button.
In the pop-up, fill in the fields with incorrect data (e.g., invalid address, postal code, etc.).
Click the Purchase button.

Expected Result: The system should show an error message indicating that the data is incorrect. The order should not be placed.

Actual Result: To be filled after execution

Status: In Process

TC_036

Summary: Check Purchase button behavior when negative values are entered in the fields

Preconditions: The user must have at least one item in the cart and be on the order page.

Test Steps:

Go to the cart.
Click the Place order button.
In the pop-up, enter negative values in one or more fields (e.g., negative postal code or phone number).
Click the Purchase button.

Expected Result: The system should show an error message indicating that negative values are not allowed. The order should not be placed.

Actual Result: To be filled after execution

Status: In Process

TC_037

Summary: Check Purchase button behavior when the fields exceed the maximum character limit (50+ characters)

Preconditions: The user must have at least one item in the cart and be on the order page.

Test Steps:

Go to the cart.
Click the Place order button.
In the pop-up, enter more than 50 characters in one of the fields (e.g., name, address, or city).
Click the Purchase button.

Expected Result: The system should either reject the input or show an error message indicating the character limit has been exceeded. The order should not be placed.

Actual Result: To be filled after execution

Status: In Process

TC_38

Summary: Verify that all main interface elements (menu, buttons, images, text, links) are displayed correctly on the page without distortion.

Preconditions: The user is on the homepage or any other page of the website.

Test Steps:
Verify that all main elements (menu, buttons, images, text, links) are displayed correctly.
Verify that all buttons have the correct labels and are clickable.
Expected Result: All interface elements are displayed correctly on the screen, without distortion or missing parts.
Actual Result: To be filled after test execution
Status: To be filled after test execution (Pass/Fail)

TC_39: Verification of Website Responsiveness for Different Screen Sizes (ComputerSummary: Verify that the website displays correctly on a computer screen, and the interface is user-friendly.

Preconditions: The user opens the website Demoblazer on a computer.

Test Steps:
Open the website Demoblazer on a computer.
Verify that the interface adjusts correctly to the computer screen.
Verify the availability of main interface elements: menu, buttons, links.
Verify that all images, text, and tables display correctly.

Expected Result: The website should display correctly on a computer screen, and the interface should be user-friendly.

Actual Result: To be filled after test execution

Status: To be filled after test execution (Pass/Fail)

TC_40

Summary: Verify that the website displays correctly on a tablet screen, and the menu and interface elements are accessible.

Preconditions: The user opens the website Demoblazer on a tablet.

Test Steps:
Open the website Demoblazer on a tablet.
Verify that the interface adjusts correctly to the tablet screen.
Verify the availability of main interface elements: menu, buttons, links.
Verify that all images, text, and tables display correctly.

Expected Result: The website should display correctly on a tablet screen, and the interface should be user-friendly.

Actual Result: To be filled after test execution

Status: To be filled after test execution (Pass/Fail)

TC_41

Summary: Verify that the website displays correctly on a smartphone screen, and the menu and interface elements are accessible.

Preconditions: The user opens the website Demoblazer on a smartphone.

Test Steps:
Open the website Demoblazer on a smartphone.
Verify that the interface adjusts correctly to the phone screen.
Verify the availability of main interface elements: menu, buttons, links.
Verify that all images, text, and tables display correctly.

Expected Result: The website should display correctly on a smartphone screen, and the menu and interface elements should be accessible.

Actual Result: To be filled after test execution

Status: To be filled after test execution (Pass/Fail)

TC_42

Summary: Verify that the website uses an appropriate color palette and that the contrast between text and background is sufficient for readability.

Preconditions: The user is on any page of the website.

Test Steps:
Verify that the color palette is used correctly (without overly bright or poorly combined colors).
Check the contrast between the text and the background to ensure good visibility for users with poor eyesight.

Expected Result: The colors and contrast should be pleasant to the eyes and provide comfortable reading.

Actual Result: To be filled after test execution

Status: To be filled after test execution (Pass/Fail)

TC_43

Summary: Verify that the ordering process is easy to follow, and the fields are easy to fill out with clear instructions.

Preconditions: The user has a product in the cart and is ready to place an order.

Test Steps:
Verify that there are no difficulties when filling in the fields on the order page.
Verify that the instructions for entering data (such as address or payment information) are clear.

Expected Result: The order placement process should be intuitive, clear, and fast.

Actual Result: To be filled after test execution

Status: To be filled after test execution (Pass/Fail)

TC_44

Summary: Verify that the visual elements (buttons, icons, textures) match the overall website design and that there is consistency in styles, fonts, and colors across all pages.

Preconditions: The user is on any product page.

Test Steps:
Verify that the design elements (buttons, icons, textures) match the overall design of the website.
Ensure consistency in styles, fonts, and colors across all pages.

Expected Result: The website design should match the established layout and be consistent across all pages.

Actual Result: To be filled after test execution

Status: To be filled after test execution (Pass/Fail)

TC_45

Summary: Verify the Cart functionality without user authorization.

Preconditions: User is not logged in.

Steps:

Go to the website.

Without logging in, click on the Cart button in the top menu.

Check if products can be added to the cart.

Verify if the Place Order button is accessible.

Expected Result:

The Place Order button should be unavailable without authorization.

Products can be added to the cart, but attempting to place an order should display the message "Please login first".

Actual Result:

Status: In Progress

TC_46

Summary: Verify URL access restriction for unauthorized users.

Preconditions: User is logged in with a regular account (not admin).

Steps:

Log in as a regular user.

Enter the URL https://www.demoblaze.com/admin.html or any non-menu URL in the browser address bar.

Expected Result:

The site should redirect to the homepage or display an "Access Denied" message.

Actual Result:

Status: In Progress

TC_47

Summary: Verify system protection against SQL Injection.

Preconditions: User is on the Sign-up page.

Steps:

Go to the Sign-up page.

Enter the following in the Username field: ' OR 1=1 --

Enter any text in the Password field.

Click Sign up.

Expected Result:

An error message or registration denial should appear.

The system should not create an account.

Actual Result:

Status: In Progress

TC_48

Summary: Verify session expiration after inactivity.

Preconditions: User is logged in.

Steps:

Log in to the site.

Leave the tab open without activity for 20-30 minutes.

Refresh the page or try any action.

Expected Result:

Automatic logout should occur.

The site should redirect to the login page.

Actual Result:

Status: In Progress

TC_49

Summary: Verify correct error handling for incorrect URLs.

Preconditions: User is on any page.

Steps:

Go to any page.

Enter an invalid URL, e.g., https://www.demoblaze.com/unknownpage123

Expected Result:

A "404 Page Not Found" message should appear.

No technical server or database information should be visible.

Actual Result:

Status: In Progress

TC_50

Summary: Verify site performance with a large number of products in the cart.

Preconditions: User is logged in or as a guest (if allowed).

Steps:

Go to the website.

Add 20-30 products from different categories to the cart.

Go to the Cart.

Click Place Order.

Expected Result:

The cart should display all added products.

The site should not freeze or load slowly.

The total price should be calculated correctly.

The order should be placed without errors.

Actual Result:

Status: In Progress

TC_51

Summary: Verify site stability under high user activity.

Preconditions: User is logged in.

Steps:

Go to the website.

Log in.

Refresh the Cart page continuously (15-20 times) within 1 minute.

Check if products remain in the cart after each refresh.

Verify if there are any errors like "500 Internal Server Error" or "Session Timeout".

Expected Result:

Products should remain in the cart after each refresh.

The site should work stably without freezing.

No error messages should appear.

Actual Result:

Status: In Progress


