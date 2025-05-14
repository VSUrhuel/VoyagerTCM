## **CONN-004:** Connectivity Testing - Persistent Authentication Status  

> **Summary:** Verify user remains authenticated after brief network interruption.  <br>


**Preconditions:** _Turned on data connection or connected device from wifi with internet_  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Open Eduvate app     | Verify that the application starts and is running.   | 
 |  2 | Login or Signup      | Verify that the application can login or signup. |
 |  3 | Turn off your internet | Verify that the internet connection is completely off. |
 |  4 | Close the app  | Verify that the application was completely closed.  |  
 |  5 | Turn the internet on and open Eduvate    | Verify that the application starts and runs. |
 |  6 | Navigate to screens or pages  | Verify that the the screen doesn't take you back to login page and that the role is still the same as the previous logged in.


**Post-conditions:**  

 -  No changes, must still be the same as usual
 -  Doesn't take the user back to login-page
 -  User can still be able to perform actions according to its authenticated role.
