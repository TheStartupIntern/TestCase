# Verify Login Attempt with Empty Credentials
Verify that the system handles empty credentials appropriately.

## **Preconditions:**  
- A stable internet connection is available.  
- The user has access to a supported web browser (Chrome, Firefox, Edge, Safari, etc.).

## **Test Steps:**  
1. Open a web browser.
2. Navigate to the application's login page (e.g., https://www.example.com/login).
3. Leave both the username and password fields empty.
4. Click the **Login** button.
5. Observe the behavior of the application. 

## **Expected Result:**  
- The system displays an error message (e.g., **"Username and password are required"**)
- The user is not logged in and remains on the login page.
- No session is established.

## **Postconditions:**  
- The application is in a usable state for further testing. 
- The login form fields (username and password) remain empty for the next attempt.
- The application remains on the login page, and the user can retry with valid credentials.

## **Test Priority:**  
Medium 

## **Status:**  
Pass/Fail (to be determined after execution)
