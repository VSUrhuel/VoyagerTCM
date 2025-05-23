## **MENTOR-007:** Mentor Functionality Testing - Post Categorization  

> **Summary:** Verify mentors can set post categories.  <br>

**Preconditions:** 
- Metor must be logged in
- Mentee(s) already accepted

Scenario 1: Posting an announcment post 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 | 1  | Launch the application | Verify that the onboarding screen is shown for first time user, otherwise show sign in form. |  
 | 2  | Log in using a mentor account | Verify that the mentor successfully logs in and the home page is shown. |  
 | 3  | Select `Announcement` from the category options.	      | Verify that announcement was highlighted   | 
 | 4  | Click the `Post` button | Verify that the Post button becomes disabled and is replaced with a loading indicator. |  
 | 5  | Wait for post creation to complete | Verify that the new post appears in the mentor’s post list and the screen navigates to previous screen. |  
 | 6  | Click `post` icon in bottom nav bar | Verify that the new post appears in the mentor's post list with the UI for Announcement category. |  

Scenario 2: Posting a resources post 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 | 1  | Launch the application | Verify that the onboarding screen is shown for first time user, otherwise show sign in form. |  
 | 2  | Log in using a mentor account | Verify that the mentor successfully logs in and the home page is shown. |  
 | 3  | Select `Resources` from the category options.	      | Verify that announcement was highlighted   | 
 | 4  | Click the `Post` button | Verify that the Post button becomes disabled and is replaced with a loading indicator. |  
 | 5  | Wait for post creation to complete | Verify that the new post appears in the mentor’s post list and the screen navigates to previous screen. |  
 | 6  | Click `post` icon in bottom nav bar | Verify that the new post appears in the mentor's post list with the UI for Announcement category. |  


**Post-conditions:**  

 - A post was uploaded with its corresponding post category
