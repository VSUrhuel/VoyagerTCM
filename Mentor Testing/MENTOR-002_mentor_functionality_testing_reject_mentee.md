## **MENTOR-002:** Mentor Functionality Testing - Reject Mentee  

> **Summary:** Verify mentors can reject mentee requests.  <br>

**Preconditions:** 
- Login as mentor account
- Existing pending mentee requets

Scenario 1: Rejecting Mentee in Home Page

 | # | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Launch Application    | Verify that the onboarding screen is shown for first time user, then if not then show the sign in form.   | 
 |  2 |  Login using a mentor acccount    | Verify that the mentor succesfully log in and the mentor home page is shown.   | 
 |  3 |  Click the `kebab menu` (three vertical dots) of the pending mentee   | Verify that it shows actions `Accept` and `Reject`   |  
 |  4 |  Click the `Reject` action of the pending mentee    | Verify that it auotomatically refresh the pending request and was removed from pending list   |
 |  5 |  Click the `View All` in mentee list   | Verify that screen navigates to pending list  |
 |  6 |  Click the `Rjected` tab | Verify that content changes, and shows the recently rejected mentee |

 Scenario 2: Rejecting Mentee in View All Pending Request Page

 | # | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Launch Application    | Verify that the onboarding screen is shown for first time user, then if not then show the sign in form.   | 
 |  2 |  Login using a mentor acccount    | Verify that the mentor succesfully log in and the mentor home page is shown.   | 
 |  3 |  Click the `View all` button in pending requst   | Verify that it navigates to pending requests tab  |  
 |  4 |  Click the `kebab menu` (three vertical dots) of the pending mentee   | Verify that it shows actions `Accept` and `Reject`   |  
 |  5 |  Click the `Reject` action    | Verify that it auotomatically refresh the pending request and was removed from pending list   |
 |  6 |  Click the back arrow button    | Verify that both pending and accepted list are refresh  |
 |  7 |  Click the `View All` in mentee list   | Verify that screen navigates to pending list  |
 |  8 |  Click the `Rjected` tab | Verify that content changes, and shows the recently rejected mentee |

**Post-conditions:**  

 - Mentee's enrolling pending request is rejected
 - Mentee can re-enroll in the same course and the same mentor
 - Mentor cannot make any actions towards rejected mentee

