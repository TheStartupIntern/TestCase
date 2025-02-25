# Check that CAPTCHA Appears After Multiple Failed Login Attempts
Verify that CAPTCHA is triggered after multiple failed login attempts to prevent brute-force attacks.

#### **Preconditions:**  
- The system has CAPTCHA enabled for authentication.
- A stable internet connection is available.
- The user has access to a supported web browser.

#### **Test Steps:**  
1. Open a web browser.
2. Navigate to the login page (https://www.example.com/login).
3. Enter incorrect credentials multiple times (e.g., 3-5 failed attempts).
4. Observe if the CAPTCHA challenge appears.

#### **Expected Result:**  
- CAPTCHA appears after repeated failed login attempts.
- The system does not allow automated login attempts.
- The user must complete the CAPTCHA before attempting further logins.

#### **Postconditions:**  
- The system remains protected against brute-force attacks.

#### **Test Priority:**  
High

#### **Status:**  
Pass/Fail (to be determined after execution)
