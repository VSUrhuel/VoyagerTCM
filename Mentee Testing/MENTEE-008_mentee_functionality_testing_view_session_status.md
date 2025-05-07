## **MENTEE-008:** Mentee Functionality Testing - View Session Status  

> **Summary:** Verify mentees can view upcoming/completed sessions.  <br>

**Preconditions:**  
- User should be logged in as a Mentee
- Mentee should be enrolled to the course
- Mentee should be approved by the Mentor
- Mentor should have an existing session scheduled

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Launch Application    | Verify that the sign form is shown.   | 
 |  2 |  Register using a Mentee account   | Verify that the homescreen for Mentee is shown.  | 
 |  3 |  In the nav bar press the `Session` section    | Verify that the session screen is showing the list of sessioni from the Mentor   |  
 |  4 |  In the session screen select `Completed` to view completed session   | Verify that the list of cards being shown are completed sessions posted by the Mentor.   | 
 |  5 |  In the session screen select `Upcoming` to view upcoming session   | Verify that the list of cards being shown are upcoming sessions posted by the Mentor.   | 

**Post-conditions:**  

 - The list of mentor session schedule is successfully displayed and accessible to the enrolled and approved mentee.
 - The mentee can view completed and upcoming session posted by the Mentor.
 - No access is granted to posts from mentors the mentee is not enrolled with.
