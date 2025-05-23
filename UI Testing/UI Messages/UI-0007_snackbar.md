## **UI-0007:** Snackbar  

> **Summary:** Verify that snackbars are working successfully.  <br>

**Preconditions:**  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Launch Application   | Verify that the onboarding screen appears for first time user, and it not then directly show the login page.   | 
 |  2 |   Navigate to the login form   | Verify that the login form is visible to the user.   | 
 |  3 |   Click the `Register Button`   | Verify that the user is redirected to the register page .   |  
 |  4 |   Click the `Sign up` button without filling the fields   | Verify that a snackbar sill appear saying "Missing Fields".   |

**Post-conditions:**  

 - Snackbar appears immediately after the trigger event.
 - Snackbar content is relevant and readable.
 - Snackbar disappears after a set duration or when dismissed, without leaving UI artifacts.
