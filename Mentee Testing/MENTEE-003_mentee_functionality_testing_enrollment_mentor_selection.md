## **MENTEE-003:** Mentee Functionality Testing - Enrollment Mentor Selection  

> **Summary:** Verify mentees can select mentors during enrollment.  <br>

**Preconditions:** 
- User should be enrolled in a Mentee account
- Mentee should select a course from course list given there are courses available
- The course selected should have an available assigned Mentor.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Launch Application    | Verify that the sign in form is shown.   | 
 |  2 |  Login using Mentee account    | Verify that the Mentee home screen is shown.   | 
 |  3 |  Select the course by pressing the course card    | Verify that the course details is shown   |  
 |  4 |  Select preffered available Mentor in the mentor list under the selected course    | Verify that the border outline of the selected Mentor is in color blue.   |   
 

**Post-conditions:**  

 - The selected mentor is visually indicated with a blue border outline.
 - The selected mentor's ID is temporarily stored in the enrollment session data.
 - The system ensures that only one mentor is selected at a time for the course.
 - The mentee is prevented from selecting unavailable or inactive mentors.
 - If the mentee proceeds with enrollment, the selected mentor is linked to the course enrollment request.
