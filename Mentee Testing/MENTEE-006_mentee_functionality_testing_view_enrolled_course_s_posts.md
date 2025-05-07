## **MENTEE-006:** Mentee Functionality Testing - View Enrolled Course's Posts  

> **Summary:** Verify mentees can view posts from enrolled courses.  <br>

**Preconditions:** 
- User should be logged in as a Mentee
- Mentee should be enrolled to the course
- Mentee should be approved by the Mentor
- Mentor should have an existing post

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Launch Application    | Verify that the sign form is shown.   | 
 |  2 |  Register using a Mentee account    | Verify that the homescreen for Mentee is shown.  | 
 |  3 |  In the nav bar press the `Post` section    | Verify that the post screen is showing the list of Post from the Mentor   |  
 |  4 |  In the post card, press `Attachment`   | Verify that a drop down for all the media display will appear.   | 
 |  5 |  Under the `Attachment` dropdown press the `Download` button    | Verify that the resources will be downloaded to the device.   | 


**Post-conditions:**  

 - The list of mentor posts is successfully displayed and accessible to the enrolled and approved mentee.
 - The mentee can view attachments associated with each post.
 - Downloaded media files are saved to the device’s local storage or appropriate download directory.
 - No access is granted to posts from mentors the mentee is not enrolled with.
