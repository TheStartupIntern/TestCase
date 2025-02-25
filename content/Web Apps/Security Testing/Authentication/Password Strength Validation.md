# Check Password Strength Validation
Verify that the system enforces password strength requirements during registration or password reset.

#### **Preconditions:**  
- A stable internet connection is available.
- The user has access to a supported web browser.

#### **Test Steps:**  
1. Open a web browser.
2. Navigate to the application's registration or password reset page.
3. Enter a weak password (e.g., 123456).
4. Click the **Submit** button.

#### **Expected Result:**  
- The system rejects the weak password and displays an error message (e.g., "**Password must contain at least 8 characters, including uppercase, lowercase, and special characters**").
- The user cannot proceed until a strong password is entered.


#### **Postconditions:**  
- The application remains on the registration or password reset page.
- The user is prompted to enter a stronger password that meets the requirements.
- No account is created or password is reset until a valid password is provided.
- The application is in a usable state for further testing.
- If the user enters a valid password, the process continues as expected (e.g., account creation or password reset).

#### **Test Priority:**  
Medium

#### **Status:**  
Pass/Fail (to be determined after execution)  

