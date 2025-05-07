## **MENTEE-004:** Mentee Functionality Testing - View Course Details  

> **Summary:** Verify mentees can view course details.  <br>

**Preconditions:**
- User should be registered in a Mentee account
- Mentee should select a course from course list given there are courses available
- Mentee should not be enrolled to the course of interest
- Mentee should not have an existing or pending enrollment request

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Launch Application    | Verify that the sign in form is shown.   | 
 |  2 |  Login using Mentee account    | Verify that the Mentee home screen is shown.   | 
 |  3 |  Select the course by pressing the course card    | Verify that the course details is shown   |  

**Post-conditions:**  

 - The selected course's detailed information is correctly displayed.
 - No enrollment action is triggered automatically — the system remains in a view-only state.
 - The mentee remains eligible to initiate enrollment for the viewed course unless their status changes. 
