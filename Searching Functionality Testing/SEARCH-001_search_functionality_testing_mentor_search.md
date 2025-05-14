## **SEARCH-001:** Search Functionality Testing - Mentor Search  

> **Summary:** Verify mentees/admins can search for mentors.  <br>

**Preconditions:**
- Login as Mentee/Admin
- Mentor are avaialble

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Launch Application    | Verify that the onboarding screen is shown for first time user, then if not then show the sign in form.   | 
 |  2 |  Regiseter using a mentee acccount    | Verify that the home screen for mentee is shown.   | 
 |  3 |  In the home screen, wait for resources to load    | Verify that the course list is showing the list of coures and avaialble Mentors.   | 
 |  4 |  Change the search filter to 'Mentor'    | Verify that when a name is entered the Mentor section will display the matched mentor.   |

**Post-conditions:**  

 - Displayed mentor list reflects the search accurately
 - The system maintains correct user session and UI state
