## **CONN-005:** Connectivity Testing - Handle UI/UX in Slow Connectivity  

> **Summary:** Verify app handles slow network gracefully (loading indicators appear).  <br>

**Preconditions:** _Must be in a place with a slower internet connection_  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Open Eduvate app     | Verify that the application starts and is running.   | 
 |  2 | Login or Signup      | Verify that the application displays loading indicator upon waiting to be logged in or signed up. |
 |  3 | Navigate to any page where items are listed such as posts   | Verify that page displays loading indicators upon waiting on the items to be displayed and that the page still displays the correct and expected items.  |  


**Post-conditions:**  

 -  No changes, must all be the same as to how the app started.
 -  The app don't crash.
 -  Still be able to use the displayed functionalities even in slow manner.
