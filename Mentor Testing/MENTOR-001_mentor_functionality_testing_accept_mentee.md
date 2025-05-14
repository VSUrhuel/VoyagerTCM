## **MENTOR-001:** Mentor Functionality Testing - Accept Mentee  

> **Summary:** Verify mentors can accept mentee requests.  <br>

**Preconditions:** 
- Login as mentor account
- Existing pending mentee requets

Scenario 1: Accepting Mentee in Home Page

 | # | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Launch Application    | Verify that the onboarding screen is shown for first time user, then if not then show the sign in form.   | 
 |  2 |  Login using a mentor acccount    | Verify that the mentor succesfully log in and the mentor home page is shown.   | 
 |  3 |  Click the `kebab menu` (three vertical dots) of the pending mentee   | Verify that it shows actions `Accept` and `Reject`   |  
 |  4 |  Click the `Accept` action of the pending mentee    | Verify that it auotomatically refresh the pending request and was removed from pending list   |
 |  5 |  Pull screen down to refersh home page    | Verify that both pending and accepted list are refresh, and the accepted mentee earlier is displayed  |

 Scenario 2: Accepting Mentee in View All Pending Request Page

 | # | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Launch Application    | Verify that the onboarding screen is shown for first time user, then if not then show the sign in form.   | 
 |  2 |  Login using a mentor acccount    | Verify that the mentor succesfully log in and the mentor home page is shown.   | 
 |  3 |  Click the `View all` button in pending requst   | Verify that it navigates to pending requests tab  |  
 |  4 |  Click the `kebab menu` (three vertical dots) of the pending mentee   | Verify that it shows actions `Accept` and `Reject`   |  
 |  5 |  Click the `Accept` action    | Verify that it auotomatically refresh the pending request and was removed from pending list   |
 |  6 |  Click the back arrow button    | Verify that both pending and accepted list are refresh, and the accepted mentee earlier is displayed  |

**Post-conditions:**  

 - A mentee is accepted in mentor's list
 - Mentee can now view post, announcements, and schedules of the mentor
