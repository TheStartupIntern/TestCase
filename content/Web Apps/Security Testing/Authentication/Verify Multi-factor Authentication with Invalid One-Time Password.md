# Verify MFA with Invalid One-Time Password (OTP)
Verify that the system does not authenticate a user using an incorrect OTP.

#### **Preconditions:**  
- The user has a registered account with MFA enabled.
- A stable internet connection is available.
- The user has access to a supported web browser (Edge, Chrome, FireFox or Safari).

#### **Test Steps:**  
1. Open a web browser.
2. Navigate to the login page (https://www.example.com/login).
3. Enter valid credentials and click **Login**.
4. The system prompts for an MFA code.
5. Enter an incorrect OTP.
6. Click **Verify** and observe the application's response.

#### **Expected Result:**  
- The system displays an error message (e.g., "**Invalid OTP, please try again.**").
- The user is not authenticated.
- Repeated incorrect OTP attempts may trigger account lockout or additional security measures.

#### **Postconditions:**  
- The user must enter a valid OTP to gain access.

#### **Test Priority:**  
High

#### **Status:**  
Pass/Fail (to be determined after execution)  

