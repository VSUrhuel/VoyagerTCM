## **SEARCH-001:** Search Functionality Testing - Mentor Search  

> **Summary:** Verify mentees/admins can search for mentors.  <br>

**Preconditions:**
- Login as Mentee/Admin
- Mentor are avaialble

Scenario 1 Searching Mentors in Mentee Interface

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Launch Application    | Verify that the onboarding screen is shown for first time user, then if not then show the sign in form.   | 
 |  2 |  Regiseter using a mentee acccount    | Verify that the home screen for mentee is shown.   | 
 |  3 |  In the home screen, wait for resources to load    | Verify that the Mentor list is showing the list of avaialble Mentors.   | 
 |  4 |  Change the search filter to 'Mentor'    | Verify that when a name is entered the Mentor section will display the matched mentor.   |

 Scenario 2 Searching Mentors in Mentee View All Interface

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Launch Application    | Verify that the onboarding screen is shown for first time user, then if not then show the sign in form.   | 
 |  2 |  Regiseter using a mentee acccount    | Verify that the home screen for mentee is shown.   | 
 |  3 |  In the home screen, wait for resources to load    | Verify that the Mentor list is showing the list of avaialble Mentors.   | 
 |  4 |  Above the default Mentor list click on view all    | Verify that when the view all is clicked you are redirected to the view all Mentor interface  |
 |  5 |  Enter the Mentor's details of who you wnat to search for    | Verify that when a name is entered the Mentor section will display the matched mentor.   |

 Scenario 3 Searching Mentors in Admin Interface

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Launch Application    | Verify that the onboarding screen is shown for first time user, then if not then show the sign in form.   | 
 |  2 |  Regiseter using an admin acccount    | Verify that the home screen for admin is shown.   | 
 |  3 |  In the home screen, wait for resources to load    | Verify that the Mentor list is showing the list of avaialble Mentors.   | 
 |  4 |  Enter the mentor's details you want to search for    | Verify that when a name is entered the Mentor section will display the matched mentor.   |

**Post-conditions:**  

 - Displayed mentor list reflects the search accurately
 - The system maintains correct user session and UI state
