# Login Failure with Invalid Credentials
Verify that the system denies access when invalid credentials are entered.

#### **Preconditions:**  
- Stable internet connection is available.
- The user has access to the supported web browser (Edge, Chrome, Firefox or Safari)
- The user has invalid credentials (incorrect username or email or password)

#### **Test Steps:**  
1. Open web browser
2. Navigate to the application's login page (e.g., https://www.example.com/login)
3. Enter invalid credentials (username, email and/or password).
4. Click the "Login" button.
5. Observe the behaviour of the application

#### **Expected Result:**  
- The system displays an error message such as **"Invalid username or password"**
- The user is not logged in and remains on the login page.
- No session is established. 

#### **Postconditions:**  
- The application is in a usable state for further testing.

#### **Test Priority:**  
High

#### **Status:**  
Pass/Fail (to be determined after execution)  
