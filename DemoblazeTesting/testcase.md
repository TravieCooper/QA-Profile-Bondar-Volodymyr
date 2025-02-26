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
