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
