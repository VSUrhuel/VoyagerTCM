## **SET-001:** Settings Testing - Update Profile  

> **Summary:** Verify users can update their profile information.  <br>

**Preconditions:**
- Make sure that the user has a mentor account

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Launch Application    | Verify that the onboarding screen is shown for first time user, then if not then show the sign in form.   | 
 |  2 |  Login using a mentor acccount   | Verify that the mentor succesfully log in and the mentor home page is shown.   | 
 |  3 |  Using the Nav bar click on the `Profile` section    | Verify that the `My Profile` view page is being displayed  |  
 |  4 |  Click the `Personal Information` bar    | Verify that you are redirected to your personal information page  |  
 |  5 |  At the lower right of the profile picture click on the `Pencil` icon    | Verify that you are redirected to the input information page and user can change information  |  
 |  6 |  After editing fields, click `Proceed`     | Verify that the personal information is updated with the new information |

**Post-conditions:**  

 - User Profile Information should now contain the updated information
 - The old information should not appear in any of the interfaces 
