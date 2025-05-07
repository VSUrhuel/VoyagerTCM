## **ADMIN-008:** Admin Management Testing - Remove Course's Mentor  

> **Summary:** Verify admins can revoke mentor access from courses.  <br>

**Preconditions:** 
- Admin credentials from the developer team
- Mentor must be active or actively mentoring for a course



Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Launch Application    | Verify that on-boarding screen  is shown for first time user or the welcome screen for existing user.   | 
 |  2 | Log-in as `admin` using developer generated admin credentials       | Verify that the admin home interface is displayed.   | 
 |  3 | Click on `Course Management` tab     | Verify that `Course List` was displayed.   |
 |  4 | Below search bar, choose courses according to status     | Verify that different courses are listed from each status.   |
 |  5 | Within `Active` course status, choose one `Course` tab and click on it    | Verify that a course details page was displayed.   |
 |  6 | Scroll down and until the assigned mentors page    | Verify that if there exists an approved mentor, mentor cards are listed in this section otherwise none.  |
 |  7 | Click on a mentor card of your choice     | Verify that a pop-up mentor options dialogue appears.   |
 |  8 | Click on `Remove Mentor`     | Verify that a confirmation modal/dialogue will be displayed.  |
 |  9 | Click on `Confirm`     | Verify that a course's mentors was decremented.  |
 
**Post-conditions:**  

 - Course mentors number will be decremented
 - Mentor can't totally be able to `Post` or interact with the course
 - Mentor will lose connection with the previous mentees
 - Mentor status will be `archived`
