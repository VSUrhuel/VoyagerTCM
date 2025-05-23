## **UI-0006:** Helper texts  

> **Summary:** Verify that UI helper texts are displayed properly to guide the user in filling out form fields or using UI components..  <br>

**Preconditions:**  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Launch Application   | Verify that the onboarding screen appears for first time user, and it not then directly show the login page.   | 
 |  2 |   Navigate to the login form   | Verify that the login form fields is visible.   | 
 |  3 |   Click the login without any text on the field   | Verify that there is a placeholder text that tells what to input to the field.   |  

**Post-conditions:**  

 - Helper texts are clearly visible and contextually appropriate for each input field.
 - No overlap or confusion between helper texts and validation/error messages.
 -  User is properly guided by helper texts throughout the form interaction process.
