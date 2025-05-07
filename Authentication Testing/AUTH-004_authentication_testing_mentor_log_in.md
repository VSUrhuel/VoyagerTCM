## **AUTH-004:** Authentication Testing - Mentor Log-in  

> **Summary:** Verify mentors can log in via credentials or Google.  <br>

**Preconditions:**
- Mentor account exists in system  
- Valid mentor credentials available 

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Launch application     | Verify onboarding screen appears for new users OR welcome screen appears for returning users  | 
 | 2 | Enter mentor email (e.g., mentor@org.com) | Field accepts input without errors | 
 | 3 | Tap password eye icon | Password text becomes visible while pressed | 
 | 4 | Release eye icon | Password text returns to hidden state | 
 | 5 | Enter invalid email format (e.g., `mentor@`) | Display `Invalid email` error immediately | 
 | 6 | Submit with blank fields | Display `Missing Field` error | 
 | 7 | Enter invalid credentials and submit | Display `Invalid credentials` error after submission | 
 | 8 | Enter valid admin credentials and submit | Verify that it proceeds to Mentor home screen | 
 | 9 | Click `Forgot Password?` | Navigate to password reset screen |  

**Post-conditions:**  

 - - Successful authentication, proceed to mentor home screen  
