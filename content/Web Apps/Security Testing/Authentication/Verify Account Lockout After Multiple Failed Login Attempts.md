# Verify Account Lockout After Multiple Failed Login Attempts
Verify that the system locks the account after a specified number of failed login attempts.

#### **Preconditions:**  
- A stable internet connection is available.
- The user has access to a supported web browser.
- The application has a lockout policy (e.g., 3 failed attempts).

#### **Test Steps:**  
1. Open web browser
2. Navigate to the application's login page (e.g., https://www.example.com/login)
3. Enter invalid credentials and click **Login** repeatedly until the lockout threshold is reached.
4. Observe the behaviour of the application

#### **Expected Result:**  
- After the specified number of failed attempts, the system locks the account and displays a message (e.g., **"Account locked. Please try again later or contact support"**)
- The user cannot log in even with valid credentials until the lockout period expires or the account is unlocked by an admin.

#### **Postconditions:**  
- The account remains locked for the specified duration.
- The application is in a usable state for further testing.

#### **Test Priority:**  
High

#### **Status:**  
Pass/Fail (to be determined after execution)  

