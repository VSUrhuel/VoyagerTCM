## **UI-0008:** Toast notifications  

> **Summary:** Verify that toast notifications are working successfully, providing brief and non-intrusive feedback to the user.  <br>

**Preconditions:** 

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Launch Application   | Verify that the onboarding screen appears for first time user, and it not then directly show the login page.   | 
 |  2 |   Navigate to the login form   | Verify that the login form fields is visible.   | 
 |  3 |   Sign in as a mentee   | Verify that the mentee dashboard is displayed upon login   |  
 |  4 |   Enroll to a course   | Verify that once when enrolled there is a toast notificatin that appears where it says `Enrollment Successful`   |  
 

**Post-conditions:**  

 - Toast notifications appear automatically after appropriate actions. 
 - Toast messages are brief, non-blocking, and do not require user input.
 - Toasts auto-dismiss within the expected time frame without affecting the UI flow.
