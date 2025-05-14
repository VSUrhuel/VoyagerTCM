## **CONN-001:** Connectivity Testing - Offline Alert  

> **Summary:** Verify app shows an appropriate message when offline.  <br>

**Preconditions:** _Turn off data connection or disconnect your device from wifi_  

Scenario 1 : Login

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Open Eduvate app     | Verify that the application starts and is running.   | 
 |  2 | Click on Login     | Verify that login form field was displayed   | 
 |  3 | Fill-in and submit/login     | Verify that the submission process won't continue and an error snackbar pops up.  |  

Scenario 2 : Signup

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Open Eduvate app     | Verify that the application starts and is running.   | 
 |  2 | Click on Sign up     | Verify that sign up form field was displayed   | 
 |  3 | Fill-in and submit/login     | Verify that the submission process won't continue and an error snackbar pops up.  |  


**Post-conditions:**  

 -  An error snackbar pops up.
 -  Queries won't be processed.
 -  Data won't be added to the database.  
