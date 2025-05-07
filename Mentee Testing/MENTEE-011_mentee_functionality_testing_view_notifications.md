## **MENTEE-011:** Mentee Functionality Testing - View Notifications  

> **Summary:** Verify mentees can view notifications (posts/schedules).  <br>

**Preconditions:**  
- User should be logged in as a Mentee
- Mentee should be enrolled to the course
- Mentee should be approved by the Mentor
- Mentor should have an existing posts and session scheduled

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Launch Application    | Verify that the sign form is shown.   | 
 |  2 |  Register using a Mentee account   | Verify that the homescreen for Mentee is shown.  | 
 |  3 |  In the Mentee home screen press the `Bell` icon on the top right corner    | Verify that the notification screen is showing the list of notification received from mentor posts and schedules   |  
 |  4 |  in the notification screen click the notification card anywhere   | Verify that a pop up will appear with the full description of the notification.  | 

**Post-conditions:**  

 - The mentee successfully views all notifications related to their enrolled courses and mentors.
 - Tapping a notification opens a detailed pop-up with full content.
 - The system retains a history of received notifications for future reference.
