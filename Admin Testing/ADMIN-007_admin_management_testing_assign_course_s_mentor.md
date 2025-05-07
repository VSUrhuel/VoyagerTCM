## **ADMIN-007:** Admin Management Testing - Assign Course's Mentor  

> **Summary:** Verify admins can assign mentors to courses.  <br>


**Preconditions:** 
- Admin credentials from the developer team
- Mentor must not be active or assigned in a course
- Mentor must not be suspended


Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Launch Application    | Verify that on-boarding screen  is shown for first time user or the welcome screen for existing user.   | 
 |  2 | Log-in as `admin` using developer generated admin credentials       | Verify that the admin home interface is displayed.   | 
 |  3 | Click on `Course Management` tab     | Verify that `Course List` was displayed.   |
 |  4 | Below search bar, choose courses according to status     | Verify that different courses are listed from each status.   |
 |  5 | Within any course status, choose one `Course` tab and click on the `triple dots`    | Verify that a dialogue will pop-up with choices to either `Add Mentor`, `Archived Course`, `Restore Course` or `Delete Course`.   |
 |  6 | Click on `Add Mentor`     | Verify that a pop-up mentor list appears.   |
 |  7 | Choose a mentor to assign     | Verify that a cofirmation dialogue appears.  |
 |  7 | Click `confirm`    | Verify that the chosen course contains the mentor chosen.  |
 
**Post-conditions:**  

 - A mentor will be assigned to a course
 - Mentor status will be set to `Active`
 - A course can now be used by mentees to enroll on
