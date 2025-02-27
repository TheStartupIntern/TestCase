Test Case Title: Password Length and Strength Validation

Precondition: User is on the form page with a password field and password confirmation field.

Post Condition: The form should only accept passwords that meet the specified criteria (e.g., minimum length, alphanumeric, special character).

Test Steps:

Enter a password shorter than the minimum length (e.g., 4 characters if the minimum is 8).
Attempt to submit the form.
Observe the error message for password length.
Enter a valid password (e.g., 8 characters with a mix of letters and numbers).
Verify that the form accepts the password.
Expected Result:

The form should reject passwords that are too short and display an appropriate error message.
The form should accept passwords that meet the required length and strength.
Test Priority: High

Status: Not Tested / Passed / Failed

