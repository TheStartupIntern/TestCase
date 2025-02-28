# Check Password Reset Funtionality
Verify that the password reset functionality works as expected.

#### **Preconditions:**  
- A stable internet connection is available.
- The user has access to a supported web browser.
- The user has a registered email address.

#### **Test Steps:**  
1. Open a web browser.
2. Navigate to the application's password reset page (e.g., https://www.example.com/reset-password).
3. Enter the registered email address and click **Submit**.
4. Check the email inbox for a password reset link.
5. Click the reset link and follow the instructions to set a new password.
6. Attempt to log in with the new password and observe the behavior of the application.

#### **Expected Result:**  
- The user receives a password reset email with a valid link.
- The user can set a new password and log in successfully.
- The old password no longer works.

#### **Postconditions:**  
- The user is logged in with the new password.
- The application is in a usable state for further testing.

#### **Test Priority:**  
Medium

#### **Status:**  
Pass/Fail (to be determined after execution)
