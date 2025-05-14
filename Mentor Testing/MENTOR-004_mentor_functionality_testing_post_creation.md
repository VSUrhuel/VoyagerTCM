## **MENTOR-004:** Mentor Functionality Testing - Post Creation  

> **Summary:** Verify mentors can create posts.  <br>

**Preconditions:** 
- Metor must be logged in
- Mentee(s) already accepted

Scenario 1: Creating a Valid Post with Title and Description

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 | 1 | Launch the application | Verify that the onboarding screen is shown for first time user, otherwise show sign in form. |  
 | 2 | Log in using a mentor account | Verify that the mentor successfully logs in and the home page is shown. |  
 | 3 | Click the post action button at the nav bar button | Verify that the Create Post screen is displayed with fields for title and description. |  
 | 4 | Enter a valid title and description within character limits | Verify that input is accepted without warnings. |  
 | 5 | Click the `Post` button | Verify that the Post button becomes disabled and is replaced with a loading indicator. |  
 | 6 | Wait for post creation to complete | Verify that the new post appears in the mentor’s post list and the screen navigates to previous screen. |  

 Scenario 2: Attempting to Post with Empty Title
 
 | \# | Step | Expected Behavior |  
 |----|------|-------------------|  
 | 1 | Launch the application | Verify that the onboarding screen is shown for first time user, otherwise show sign in form. |  
 | 2 | Log in using a mentor account | Verify that the mentor successfully logs in and the home page is shown. |  
 | 3 | Click the post action button at the nav bar button | Verify that the Create Post screen is displayed with fields for title and description. |  
 | 4 | Leave the title empty and enter a valid description | Verify that nothing was changed in the screen. |  
 | 5 | Click the `Post` button | Verify that post is not submitted and a snackbar message is shown for the missing field error. |

  Scenario 3: Attempting to Post with Empty Description
  
 | \# | Step | Expected Behavior |  
 |----|------|-------------------|  
 | 1 | Launch the application | Verify that the onboarding screen is shown for first time user, otherwise show sign in form. |  
 | 2 | Log in using a mentor account | Verify that the mentor successfully logs in and the home page is shown. |  
 | 3 | Click the post action button at the nav bar button | Verify that the Create Post screen is displayed with fields for title and description. |  
 | 4 | Leave the description empty and enter a valid title | Verify that nothing was changed in the screen. |  
 | 5 | Click the `Post` button | Verify that post is not submitted and a snackbar message is shown for the missing field error. |

 Scenario 4: Exceeding Title or Description Character Limits
 
 | \# | Step | Expected Behavior |  
 |----|------|-------------------|  
 | 1 | Launch the application | Verify that the onboarding screen is shown for first time user, otherwise show sign in form. |  
 | 2 | Log in using a mentor account | Verify that the mentor successfully logs in and the home page is shown. |  
 | 3 | Click the post action button at the nav bar button | Verify that the Create Post screen is displayed with fields for title and description. |  
 | 2 | Enter a title or description that exceeds the allowed character limit | Verify that nothing was changed in the screen. |  
 | 3 | Attempt to click the `Post` button | Verify that the post is not submitted and a snackbar message for maximum character limit error was shown. |
 
Scenario 5: Rapidly Clicking Post Button

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 | 1 | Launch the application | Verify that the onboarding screen is shown for first time user, otherwise show sign in form. |  
 | 2 | Log in using a mentor account | Verify that the mentor successfully logs in and the home page is shown. |  
 | 3 | Click the post action button at the nav bar button | Verify that the Create Post screen is displayed with fields for title and description. |  
 | 4 | Enter a valid title and description within character limits | Verify that input is accepted without warnings. |  
 | 5 | Click the `Post` button repeatedly | Verify that only one post is submitted and button is disabled on first click with a loading indicator. |  


**Post-conditions:**  

- A new post is created and displayed in the mentor’s feed.  
- Posts with invalid input (empty or excessive length) are not submitted.  
- Duplicate posts are prevented through loading and button disabling mechanism.  
