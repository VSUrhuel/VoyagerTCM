## **MENTOR-005:** Mentor Functionality Testing - Post's Media Attachment  

> **Summary:** Verify mentors can attach media to posts.  <br>

**Preconditions:** 
- Metor must be logged in
- Mentee(s) already accepted

Scenario 1: Attaching Image to Post

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 | 1 | Launch the application | Verify that the onboarding screen is shown for first time user, otherwise show sign in form. |  
 | 2 | Log in using a mentor account | Verify that the mentor successfully logs in and the home page is shown. |  
 | 3 | Click the post action button at the nav bar button | Verify that the Create Post screen is displayed with fields for title and description. |  
 | 4 | Enter a valid title and description within character limits | Verify that input is accepted without warnings. |  
 | 5 | Click "Image" icon | Verify that an imag file picker appears. |  
 | 6 | Select an image (≤5MB). | Verify that image was previewed. | 
 | 6 | Click the `Post` button | Verify that the Post button becomes disabled and is replaced with a loading indicator. |  
 | 7 | Wait for post creation to complete | Verify that the new post appears in the mentor’s post list and the screen navigates to previous screen. |  

Scenario 2: Attaching PDF/document to Post

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 | 1 | Launch the application | Verify that the onboarding screen is shown for first time user, otherwise show sign in form. |  
 | 2 | Log in using a mentor account | Verify that the mentor successfully logs in and the home page is shown. |  
 | 3 | Click the post action button at the nav bar button | Verify that the Create Post screen is displayed with fields for title and description. |  
 | 4 | Enter a valid title and description within character limits | Verify that input is accepted without warnings. |  
 | 5 | Click "File" icon | Verify that an document file picker appears. |  
 | 6 | Select a file (≤5MB). | Verify that file name was shown and previewed. | 
 | 6 | Click the `Post` button | Verify that the Post button becomes disabled and is replaced with a loading indicator. |  
 | 7 | Wait for post creation to complete | Verify that the new post appears in the mentor’s post list and the screen navigates to previous screen. |  

 Scenario 3: Attaching Link to Post

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 | 1 | Launch the application | Verify that the onboarding screen is shown for first time user, otherwise show sign in form. |  
 | 2 | Log in using a mentor account | Verify that the mentor successfully logs in and the home page is shown. |  
 | 3 | Click the post action button at the nav bar button | Verify that the Create Post screen is displayed with fields for title and description. |  
 | 4 | Enter a valid title and description within character limits | Verify that input is accepted without warnings. |  
 | 5 | Click "Link" icon | Verify that a dialog appears with link title and url. |  
 | 6 | Input a valid link | Verify that the link was inputted. | 
 | 6 | Clikc the `Save` button | Verify that the link was attached with the title as the previewed and the dialog is closed| 
 | 6 | Click the `Post` button | Verify that the Post button becomes disabled and is replaced with a loading indicator. |  
 | 7 | Wait for post creation to complete | Verify that the new post appears in the mentor’s post list and the screen navigates to previous screen. |  

 Scenario 4: Attaching Videos to Post

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 | 1 | Launch the application | Verify that the onboarding screen is shown for first time user, otherwise show sign in form. |  
 | 2 | Log in using a mentor account | Verify that the mentor successfully logs in and the home page is shown. |  
 | 3 | Click the post action button at the nav bar button | Verify that the Create Post screen is displayed with fields for title and description. |  
 | 4 | Enter a valid title and description within character limits | Verify that input is accepted without warnings. |  
 | 5 | Click "Video" icon | Verify that an video picker appears. |  
 | 6 | Select a vide (≤5MB). | Verify that video name was shown and previewed. | 
 | 6 | Click the `Post` button | Verify that the Post button becomes disabled and is replaced with a loading indicator. |  
 | 7 | Wait for post creation to complete | Verify that the new post appears in the mentor’s post list and the screen navigates to previous screen. |  

**Post-conditions:**  

 - All media types attach successfully and display correctly.
