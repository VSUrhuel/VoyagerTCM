## **MENTEE-001:** Mentee Functionality Testing - Course Enrollment  

> **Summary:** Verify mentees can enroll in courses.  <br>

**Preconditions:** 
- Logged in as a mentee
- Course is avaialble for enrollment
- Course has available mentor
- Mentee has no current pending enrollment request for the same subject

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Launch Application    | Verify that the onboarding screen is shown for first time user, then if not then show the sign in form.   | 
 |  2 |  Regiseter using a mentee acccount    | Verify that the home screen for mentee is shown.   | 
 |  3 |  In the home screen, wait for resources to load    | Verify that the course list is showing the list of coures.   |  
 |  4 |  In the course card, click anywhere within the card    | Verify that the course detail are shown in the screen.   | 
 |  5 |  Once course is confirmed, select an available mentor    | Verify that the selected mentor has an outline border color of blue   |
 |  6 |  Wait until loading is completed    | Verify that a dialouge pop up appears with a text `Course enrollment processed successfully`   |
 |  7 |  In the mentee home screen look for the same course you enrolled    | Verify that the course is no longer present.   |

**Post-conditions:**  

 - The course is addded to the mentee's `Enrolled Courses` list.
 - The mentee cannot re-enroll in the same course unless the current request is cancelled or completed.
 - A pending enrollment request is recorded in the database associated with the selected mentor.
 - The course is no longer listed in the available courses list for the mentee.
 - The mentee should be able to view posts from Mentor.
 - The mentee should be able to to view session posted by the mentors.
