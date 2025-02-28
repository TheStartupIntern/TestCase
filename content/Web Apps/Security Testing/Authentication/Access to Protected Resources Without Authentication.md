# Access to Protected Resources Without Authentication
Verify that unauthorized users cannot access protected resources.

#### **Preconditions:**  
- A stable internet connection is available
- The user has access to a supported web browser.
- The user is not logged in.

#### **Test Steps:**  
1. Open a web browser.
2. Navigate directly to a protected resource URL (e.g., https://www.example.com/dashboard).
3. Observe the behavior of the application.

#### **Expected Result:**  
- The user is redirected to the login page or shown an access denied message.
- The protected resource is not accessible without authentication.

#### **Postconditions:**  
- The application is in a usable state for further testing.
- The user remains on the login page or access denied page.
- No session is created for the unauthorized user.
- Protected resources remain secure and inaccessible to unauthorized users.

#### **Test Priority:**  
High

#### **Status:**  
Pass/Fail (to be determined after execution)

