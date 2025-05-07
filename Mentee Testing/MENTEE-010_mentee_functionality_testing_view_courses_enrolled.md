## **MENTEE-010:** Mentee Functionality Testing - View Courses Enrolled  

> **Summary:** Verify mentees can view their enrolled courses.  <br>

**Preconditions:**  
- User should be logged in as a Mentee
- Mentee should be enrolled to the course
- Mentee should be approved by the Mentor

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Launch Application    | Verify that the sign form is shown.   | 
 |  2 |  Register using a Mentee account   | Verify that the homescreen for Mentee is shown.  | 
 |  3 |  In the nav bar press the `Profile` icon section    | Verify that the session screen is showing the account information of the Mentee   |  
 |  4 |  In the nav bar press the `Personal Information` button    | Verify that the screen is showing the personal information of the Mentee along with the list of `Enrolled Courses`   | 

**Post-conditions:**  

 - The mentee’s enrolled courses are correctly displayed in the Personal Information section. 
 - The data shown reflects the most recent and accurate enrollment status from the system.
 - The list does not include pending, rejected, or dropped courses — only approved enrollments are shown.
