## **MENTEE-009:** Mentee Functionality Testing - View Calendar Events  

> **Summary:** Verify mentees can view calendar events (sessions).  <br>

**Preconditions:**   
- User should be logged in as a Mentee
- Mentee should be enrolled to the course
- Mentee should be approved by the Mentor
- Mentor should have an existing session scheduled or posted

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Launch Application    | Verify that the sign form is shown.   | 
 |  2 |  Register using a Mentee account   | Verify that the homescreen for Mentee is shown.  | 
 |  3 |  In the nav bar press the `Session` section    | Verify that the session screen is showing the list of sessioni from the Mentor   |  
 |  4 |  At the top right corner press `Calendar` icon   | Verify that the calendar with the list of upcoming session is displayed.   | 

 
**Post-conditions:**  

 - The calendar view displays all upcoming sessions relevant to the mentee’s enrolled courses and approved mentors.
 -  The mentee can visually identify session dates, times, and related details in the calendar interface.
 -  The calendar remains read-only.
