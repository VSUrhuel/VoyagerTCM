## **AUTH-005:** Authentication Testing - Mentee Log-in  

> **Summary:** Verify mentees can log in via credentials or Google.  <br>

**Preconditions:**
- Mentee account exists in system  
- Valid mentee credentials available  

Scenario 1 

  | # | Step | Expected Behavior | 
 |----|------|-------------------| 
 | 1 | Launch application | Display login screen with email and password fields. | 
 | 2 | Enter mentee email (e.g., mentee@org.com) | Field accepts input without errors. | 
 | 3 | Tap password eye icon | Password text becomes visible while pressed. | 
 | 4 | Release eye icon | Password text returns to hidden state. | 
 | 5 | Enter invalid email format (e.g., `mentee@`) | Display `Invalid email` error immediately. | 
 | 6 | Submit with blank fields | Display `Missing Field` error. | 
 | 7 | Enter invalid credentials and submit | Display `Invalid credentials` error after submission. | 
 | 8 | Enter valid admin credentials and submit | Verify that it proceeds to Admin home screen. | 
 | 9 | Click `Forgot Password?` | Navigate to password reset screen. |  
 | 10 | Tap `Log In with Google` button | Verify Google account selection popup appears with available accounts. |
 | 11 | Finalize log-in | Verify navigation to mentee home screen. |  

**Post-conditions:**  

 - Successful authentication, proceed to mentee home screen  
