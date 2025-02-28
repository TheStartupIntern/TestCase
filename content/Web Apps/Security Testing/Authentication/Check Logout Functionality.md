# Verify logout functionality
Verify that the user is properly logged out and the session is terminated.

#### **Preconditions:**  
- A stable internet connection is available.
- The user is logged into the application.

#### **Test Steps:**  
1. Open a web browser.
2. Navigate to the application and log in.
3. Click the **Logout** button.
4. Attempt to access a protected resource (e.g., dashboard).
5. Observe the behavior of the application.

#### **Expected Result:**  
- The user is logged out and redirected to the login page.
- The session is terminated, and protected resources are inaccessible.

#### **Postconditions:**  
- The session token or cookie is deleted or invalidated.
- The user is no longer authenticated and cannot access protected resources without logging in again.
- The application is in a usable state for further testing (e.g., the login page is displayed and functional).
- Any cached data or sensitive information from the previous session is cleared from the browser.
- If the application supports multiple tabs or windows, all sessions are terminated across all tabs/windows.

#### **Test Priority:**  
High

#### **Status:**  
Pass/Fail (to be determined after execution)  

