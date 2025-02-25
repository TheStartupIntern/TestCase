# Check CAPTCHA Verification on Login
Ensure that CAPTCHA is required and functional for login attempts.

#### **Preconditions:**  
- The system has CAPTCHA enabled for authentication.
- A stable internet connection is available.
- The user has access to a supported web browser.

#### **Test Steps:**  
1. Open a web browser.
2. Navigate to the application's login page.
3. Enter valid credentials 
4. Complete the CAPTCHA challenge (e.g., selecting images, entering distorted text).
5. Click **Login**

#### **Expected Result:**  
- The CAPTCHA challenge is required before login submission.
- The user is successfully authenticated upon completing the CAPTCHA correctly.
- The CAPTCHA prevents automated bot login attempts.

#### **Postconditions:**  
- The user is successfully logged in and can access protected resources.
- The system remains protected against automated login attempts.


#### **Test Priority:**  
Medium

#### **Status:**  
Pass/Fail (to be determined after execution)
