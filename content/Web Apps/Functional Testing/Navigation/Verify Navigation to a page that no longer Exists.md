# Verify Navigation to a page that no longer Exists

#### **Preconditions:**  
- The website has an invalid or removed page.  

#### **Test Steps:** 
1. Open a web browser.   
2. Manually enter a non-existent URL. (www.nonexist.ng) 
3. Press **Enter**.
4. Observe the behavior of the application. 

#### **Expected Result:**  
- A 404 error page or a user friendly messsage should appear.
- Page load time should be within an acceptable limit (e.g., <3 seconds).  
- No error messages such as **"404 Not Found"**, **"500 Internal Server Error"**, or connection issues should appear.

#### **Postconditions:**  
- The user is informed that the page does not exist.  

#### **Test Priority:**  
High 

#### **Status:**  
Pass/Fail (to be determined after execution)  
