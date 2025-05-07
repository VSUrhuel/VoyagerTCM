## **AUTH-002:** Authentication Testing - Google Sign-up  

> **Summary:** Verify mentees can successfully create accounts using Google authentication.  <br>

**Preconditions:**  
- Google account is available   

### Scenario 1  

 | # | Step | Expected Behavior | 
 |----|------|-------------------| 
 | 1 | Launch application | Verify onboarding screen appears for new users OR welcome screen appears for returning users | 
 | 2 | Tap `Sign up with Google` button | Verify Google account selection popup appears with available accounts | 
 | 3 | Select Google account | Verify system requests necessary permissions | 
 | 4 | Finalize sign-up | Verify navigation to mentee home screen |  

**Post-conditions:**  

- New mentee account created in database with new user account  
