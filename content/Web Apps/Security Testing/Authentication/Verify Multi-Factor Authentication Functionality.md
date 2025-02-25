# Verify Multi-Factor Authentication Functionality
Verify that the system enforces MFA if enabled.

#### **Preconditions:**  
- A stable internet connection is available.
- The user has MFA enabled on their account.

#### **Test Steps:**  
1. Open a web browser.
2. Navigate to the application's login page.
3. Enter valid credentials and click **Login**
4. Enter the MFA code sent to the user's device and observe the behavior of the application.

#### **Expected Result:**  
- The user is logged in only after entering the correct MFA code.
- Access is denied if the MFA code is incorrect or missing.

#### **Postconditions:**  
- The user is successfully logged in and can access protected resources.
- The session is established with MFA verification.
- The application is in a usable state for further testing.
- The MFA code is invalidated after use (if it is a one-time code).

#### **Test Priority:**  
High

#### **Status:**  
Pass/Fail (to be determined after execution)
