## **SET-002:** Settings Testing - Change Password  

> **Summary:** Verify users can change their password.  <br>

**Preconditions:**
- Make sure you have any existing account for Mentee/Mentor

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Launch Application   | Verify that the onboarding screen is shown for first time user, then if not then show the sign in form.   | 
 |  2 |   Login using a mentor acccount   |  Verify that the mentor succesfully log in and the mentor home page is shown.  | 
 |  3 |   Using the Nav bar click on the Profile section   |  Verify that the My Profile view page is being displayed  |
 |  4 |   Click on the `Security and Password`    |  Verify that the Security page is displayed with the change password fields  |
 |  5 |   Input required field for password change and lick `update password`    |  Verify that a snackbar saying that the credential is changed pops up  |
 

**Post-conditions:**  

 - When login in back to the application the user can log in with the new credential 
 - User should not be able to log in using the old credentials
