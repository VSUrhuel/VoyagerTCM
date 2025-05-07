## **AUTH-001:** Authentication Testing - Email Sign-up  

> **Summary:** Verify mentees can sign up via email successfully.  <br>

**Preconditions:**  
- No user is currently logged in  

### Scenario 1  

 | # | Step | Expected Behavior | 
 |----|------|-------------------| 
 | 1 | Launch application | Verify onboarding screen appears for new users OR welcome screen appears for returning users | 
 | 2 | Tap password eye icon | Verify password text becomes visible when eye icon is pressed | 
 | 3 | Release eye icon | Verify password text is hidden again | 
 | 4 | Enter invalid email format (e.g., `user@`) | Verify system shows error message and blocks submission | 
 | 5 | Leave required fields blank and submit | Verify system prevents submission and highlights missing fields | 
 | 6 | Complete valid sign-up form and submit | Verify system shows email verification screen after successful submission | 
 | 7 | Tap `Log in` button | Verify navigation to login screen |  

**Post-conditions:**  

- New mentee account created in database with mentee role 
- Verification email sent to provided address  
