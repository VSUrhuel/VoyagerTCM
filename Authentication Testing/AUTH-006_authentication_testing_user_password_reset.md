## **AUTH-006:** Authentication Testing - User Password Reset  

> **Summary:** Verify users can reset their passwords successfully.  <br>

**Preconditions:** 
- User has an existing account

Scenario 1 

 | # | Step | Expected Behavior | 
 |----|------|-------------------| 
 | 1 | Launch application | Verify the onboarding screen appears for new users OR the welcome screen appears for returning users | 
 | 2 | Click the `Forgot Password?` text button | Verify that it navigates to the forgot password page | 
 | 3 | Enter user email (e.g., user@org.com) | Verify the field accepts input without errors |
 | 4 | Enter invalid email format (e.g., `user@`) | Verify the system displays an `Error sending email` message immediately | 
 | 5 | Submit with blank fields | Verify the system displays an `Error sending email` message | 
 | 6 | Enter valid admin email | Verify the system shows a `Check your email` prompt and navigates to the login screen | 

**Post-conditions:**  

- System sends a password reset email  
- User's email password will be reset  
