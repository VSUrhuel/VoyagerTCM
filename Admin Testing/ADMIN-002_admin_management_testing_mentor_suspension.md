## **ADMIN-002:** Admin Management Testing - Mentor Suspension  

> **Summary:** Verify admins can suspend mentors.  <br>

**Preconditions:** 
- Admin credentials from the developer team
- Mentor must be `Active` or `Archived`
- Under `Archived` mentors, suspension is applicable only to mentor that completed the registration process or basically has schedule chosen



Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Launch Application    | Verify that on-boarding screen  is screen is shown for first time user or the welcome screen for existing user.   | 
 |  2 | Log-in as `admin` using developer generated admin credentials       | Verify that the admin home interface is displayed.   | 
 |  3 | Click on `Mentor Management` tab     | Verify that `Mentor List` was displayed.   |
 |  4 | Below search bar, choose mentors according to status     | Verify that different mentors are listed from each status.   |
 |  5 | Within `Active` or `Archived` status, choose one `Mentor` tab and click on the `triple dots`    | Verify that a dialogue will pop-up with choices to either `suspend` or `delete` a mentor.   |
 |  6 | Click on `Suspend Mentor`     | Verify that a pop-up confirmation dialogue appears.   |
 |  7 | Click on `Confirm`     | Verify that a snackbar appears showing successful action.  |
 
**Post-conditions:**  

 - Mentor status will be set to suspended
 - Mentor can't be able to access their accounts
 - Mentor will be removed from the list of mentors that are available to be assigned for a course

 
