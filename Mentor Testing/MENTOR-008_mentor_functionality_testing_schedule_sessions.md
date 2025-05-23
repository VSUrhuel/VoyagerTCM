## **MENTOR-008:** Mentor Functionality Testing - Schedule Sessions  

> **Summary:** Verify mentors can create schedules for courses.  <br>

**Preconditions:** 
- Metor must be logged in
- Mentee(s) already accepted

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 | 1 | Launch the application | Verify that the onboarding screen is shown for first time user, otherwise show sign in form. |  
 | 2 | Log in using a mentor account | Verify that the mentor successfully logs in and the home page is shown. |  
 | 3 | Click the `calendar` icon | Verify that it navigates to My Session interface, there is an upcoming and completed session. |
 | 4 | Click the `calendar` icon in the app bar | Verify that it navigates to new screen and shows a calendar interface |
 | 5 | Click a specific date in the future | Verify that the selected date will be colored blue |
 | 6 | Click the `plus` icon | Verify that a dialog will pop up for new schedule |
 | 7 | Input the necessary valid details for new schedule | Verify the the input will be accepted |
 | 8 | Click `save` button | Verify that the new schedule will be accepted and the dialog will be close |
 | 9 | Click the date that was scheduled earlier | Verify that the scheduled date will be displayed |

**Post-conditions:**  

 - A new schedule date session will be saved
