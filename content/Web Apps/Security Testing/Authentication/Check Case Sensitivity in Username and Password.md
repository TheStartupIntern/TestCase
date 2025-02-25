# Check Case Sensitivity in Username and Password
Verify that the system handles case sensitivity correctly for usernames and passwords.

#### **Preconditions:**  
- A stable internet connection is available
- The user has access to a supported web browser like Edge, Safari, Chrome or Firefox.
- The user has a valid username (**User123**) and password (**Pass123**)

#### **Test Steps:**  
1. Open a web browser.
2. Navigate to the application's login page.
3. Enter the username and password with different cases (e.g., **user123** and **pass123**).
4. Click the **Login** button and observe the application's behaviour.

#### **Expected Result:**  
- The system denies access and displays an error message (e.g., "**Invalid username or password**").
- The user is not logged in.

#### **Postconditions:**  
- The application is in a usable state for further testing.
- The application remains on the login page, allowing the user to retry with the correct credentials.
- No session is created, and the user is not granted access to protected resources.
- The system logs the failed login attempt (if applicable).

#### **Test Priority:**  
Medium

#### **Status:**  
Pass/Fail (to be determined after execution)
