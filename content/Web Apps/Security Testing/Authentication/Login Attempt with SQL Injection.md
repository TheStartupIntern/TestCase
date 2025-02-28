# Login Attempt with SQL Injection
Verify that the login form is protected against SQL injection attacks.

## **Preconditions:**  
- A stable internet connection is available.  
- The user has access to a supported web browser (Chrome, Firefox, Edge, Safari, etc.).

## **Test Steps:**  
1. Open a web browser.  
2. Navigate to the application's URL (e.g., `https://www.example.com/login`).  
3. Enter the following SQL injection payload in the username field: admin' OR '1'='1
4. Enter any password in the password field.
5. Click the **Login** button.
6. Observe the application's response.

## **Expected Result:**  
- The system rejects the login attempt and does not authenticate the user.
- The error message does not reveal SQL syntax or database errors.
- The system implements input validation and sanitization.

## **Postconditions:**  
- The login page remains secure and functional. 

## **Test Priority:**  
High 

## **Status:**  
Pass/Fail (to be determined after execution)  
