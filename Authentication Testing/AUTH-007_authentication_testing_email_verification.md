## **AUTH-007:** Authentication Testing - Email Verification  

> **Summary:** Verify users can verify their email successfully.  <br>

**Preconditions:** 
- Unverified user account

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Launch application | Display verify email screen for unveried user email |  
 |  2 | Click the `Resend E-mail Link` text button  | Verify that user received another email verification link   | 
 |  3 | Click the `Continue` button    | Verify that the user can redirect to home screen if already verified, else, will prompt an `Email not verified` error   |
 |  4 | Click the `back to log in` text button | Verify that the screen navigates back to log-in screen |
 |  5 | Wait for 3 seconds after verification | Verify that screen automatically navigates after 3 seconds from verification | 

**Post-conditions:**  

 - Email will be verified
 - Proceeds to the user home screen
