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
Preconditions: The user must be on the homepage of  https://www.demoblaze.com/index.html..
Test Steps:
1.	Click on "Cart" in the top navigation menu.
2.	Verify that the cart page is displayed.
Expected Result: The cart page opens.
Actual Result: To be filled after execution
Status: In Process
TC_022
Summary: Navigation check for "Log in"
Preconditions: The user must be on the homepage of  https://www.demoblaze.com/index.html..
Test Steps:
1.	Click on "Log in" in the top navigation menu.
2.	Verify that the appropriate pop-up window appears.
Expected Result: The "Log in" pop-up window opens.
Actual Result: To be filled after execution
Status: In Process
TC_023
Summary: Navigation check for "Sign up"
Preconditions: The user must be on the homepage of  https://www.demoblaze.com/index.html..
Test Steps:
1.	Click on "Sign up" in the top navigation menu.
2.	Verify that the appropriate pop-up window appears.
Expected Result: The "Sign up" pop-up window opens.
Actual Result: To be filled after execution
Status: In Process
