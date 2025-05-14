## **MENTOR-003:** Mentor Functionality Testing - Remove Mentee  

> **Summary:** Verify mentors can remove mentees.  <br>

**Preconditions:** 
- Login as mentor account
- Existing accepted mentee

Scenario 1: Removing Mentee in Home Page

 | # | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Launch Application    | Verify that the onboarding screen is shown for first time user, then if not then show the sign in form.   | 
 |  2 |  Login using a mentor acccount    | Verify that the mentor succesfully log in and the mentor home page is shown.   | 
 |  3 |  Click the `kebab menu` (three vertical dots) of the accepted mentee   | Verify that it shows `Remove` action   |  
 |  4 |  Click the `Remove` action of the accepted mentee    | Verify that it auotomatically refresh the mentee list and was removed from the list   |
 |  5 |  Click the `View all` button in mentee list   | Verify that it navigates to mentee list screen  |
 |  6 |  Search mentee's name  | Verify that it does not reflect any mentee |

 Scenario 2: Removing Mentee in View All Mentee List Page

 | # | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Launch Application    | Verify that the onboarding screen is shown for first time user, then if not then show the sign in form.   | 
 |  2 |  Login using a mentor acccount    | Verify that the mentor succesfully log in and the mentor home page is shown.   | 
 |  3 |  Click the `View all` button in pending requst   | Verify that it navigates to pending requests tab  |  
 |  6 |  Search mentee's name  | Verify that it does reflect the mentee's information |
 |  3 |  Click the `kebab menu` (three vertical dots) of the accepted mentee   | Verify that it shows `Remove` action   |  
 |  4 |  Click the `Remove` action of the accepted mentee    | Verify that it auotomatically refresh the mentee list and was removed from the list   |
 |  6 |  Search mentee's name  | Verify that it does not reflect any mentee |

**Post-conditions:**  

 - Mentee is removed in mentor's list
 - Mentee will no longer have access to post, announcemnts, and sessions of the mentor
 - Mentee can re-enroll in the same course and mentor
