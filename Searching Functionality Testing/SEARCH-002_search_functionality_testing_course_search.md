## **SEARCH-002:** Search Functionality Testing - Course Search  

> **Summary:** Verify mentees/admins can search for courses.  <br>

**Preconditions:**
- Login as Mentee/Admin
- Courses are avaialble

Scenario 1 Searching Courses in Mentee Interface

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Launch Application    | Verify that the onboarding screen is shown for first time user, then if not then show the sign in form.   | 
 |  2 |  Regiseter using a mentee or admin acccount    | Verify that the home screen for mentee is shown.   | 
 |  3 |  In the home screen, wait for resources to load    | Verify that the course list is showing the list of coures.   | 
 |  4 |  Change the search filter to ' Course'    | Verify that when a course name is entered the Mentor section will display the matched Courses.   |

 Scenario 2 Searching Mentee in Mentee view all Courses Interface

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Launch Application    | Verify that the onboarding screen is shown for first time user, then if not then show the sign in form.   | 
 |  2 |  Regiseter using a mentee    | Verify that the home screen for mentee is shown.   | 
 |  3 |  In the home screen, wait for resources to load    | Verify that the course list is showing the list of coures.   | 
 |  4 |  Click the "View All" above the course display    | Verify that when it is clicked the user is redirected to the View All Courses interface  |
 |  5 |  Enter the Course details you wnat to search    | Verify that the Courses return matched with the information of the course you are searching for  |

 **Scenario 2 Searching Mentee in Admin Interface

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Launch Application    | Verify that the onboarding screen is shown for first time user, then if not then show the sign in form.   | 
 |  2 |  Regiseter using a admin acccount    | Verify that the home screen for Admin is shown.   | 
 |  3 |  In the home screen, wait for resources to load    | Verify that the course list is showing the list of coures.   | 
 |  4 |  Click the course management in the interface    | Verify that when it is clicked the list of Courese are properly reflected  |
 |  5 |  Enter the Course details you wnat to search    | Verify that the Courses return matched with the information of the course you are searching for  |**
 

**Post-conditions:**  

 - Displayed Course list reflects the search accurately
 - The system maintains correct user session and UI state

