# Verify Error handling on Restricted Pages

#### **Preconditions:**  
- The user is not logged in.  

#### **Test Steps:**  
1. Open a web browser.  
2. Navigate to the application's URL (e.g., `https://www.example.com`). 
3. Access a restricted page via manipulating the direct URL. 
4. Observe the behavior of the application.  

#### **Expected Result:**  
- The user is prompted to log in or sees an appropriate error message. 
- Page load time should be within an acceptable limit (e.g., <3 seconds).  
- No error messages such as **"404 Not Found"**, **"500 Internal Server Error"**, or connection issues should appear. 

#### **Postconditions:**  
- The user is guided appropriately to the required page.  

#### **Test Priority:**  
High  

#### **Status:**  
Pass/Fail (to be determined after execution)  
