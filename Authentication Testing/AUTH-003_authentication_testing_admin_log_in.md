## **AUTH-003:** Authentication Testing - Admin Log-in  

> **Summary:** Verify administrators can successfully authenticate using credentials.  <br>

**Preconditions:**  
- Admin account exists in system  
- Valid admin credentials available  

Scenario 1  

 | # | Step | Expected Behavior | 
 |----|------|-------------------| 
 | 1 | Launch application | Display login screen with email and password fields | 
 | 2 | Enter admin email (e.g., admin@org.com) | Field accepts input without errors | 
 | 3 | Tap password eye icon | Password text becomes visible while pressed | 
 | 4 | Release eye icon | Password text returns to hidden state | 
 | 5 | Enter invalid email format (e.g., `admin@`) | Display `Invalid email` error immediately | 
 | 6 | Submit with blank fields | Display `Missing Field` error | 
 | 7 | Enter invalid credentials and submit | Display `Invalid credentials` error after submission | 
 | 8 | Enter valid admin credentials and submit | Verify that it proceeds to Admin home screen | 
 | 9 | Click `Forgot Password?` | Navigate to password reset screen |  

**Post-conditions:**  

- Successful authentication, proceed to admin home screen  
