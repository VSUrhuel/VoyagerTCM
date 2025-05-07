## **ADMIN-006:** Admin Management Testing - Course Deletion  

> **Summary:** Verify admins can permanently delete courses.  <br>

**Preconditions:** 
- Admin credentials from the developer team


Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Launch Application    | Verify that on-boarding screen  is screen is shown for first time user or the welcome screen for existing user.   | 
 |  2 | Log-in as `admin` using developer generated admin credentials       | Verify that the admin home interface is displayed.   | 
 |  3 | Click on `Course Management` tab     | Verify that `Course List` was displayed.   |
 |  4 | Below search bar, choose courses according to status     | Verify that different courses are listed from each status.   |
 |  5 | Within any course status, choose one `Course` tab and click on the `triple dots`    | Verify that a dialogue will pop-up with choices to either `Add Mentor`, `Archived Course`, `Restore Course` or `Delete Course`.   |
 |  6 | Click on `Delete Course`     | Verify that a pop-up confirmation dialogue appears.   |
 |  7 | Click on `Delete`     | Verify that a snackbar appears showing successful action.  |
 
**Post-conditions:**  

 - Course will be `softdeleted`
 - A course will be removed from the entire system queries
