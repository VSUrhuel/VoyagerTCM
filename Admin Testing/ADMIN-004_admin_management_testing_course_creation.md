## **ADMIN-004:** Admin Management Testing - Course Creation  

> **Summary:** Verify admins can create new courses.  <br>


**Preconditions:** 
- Admin credentials from the developer team



Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Launch Application    | Verify that on-boarding screen  is screen is shown for first time user or the welcome screen for existing user.   | 
 |  2 | Log-in as `admin` using developer generated admin credentials       | Verify that the admin home interface is displayed.   | 
 |  3 | Click on `Course Management` tab     | Verify that `Course List` was displayed.   |
 |  4 | On the upper right of the screen, below search bar, click on `+` button     | Verify that `Add Course` interface is displayed with five boxes to fill-up.   |
 |  5 | Fill-in the textboxes      | Verify that text boxes can be filled and inputs persists when clicking other parts of the screen.   |
 |  6 | Under `Course Deliverables` after text input, click enter or `+` button to append each deliverables      | Verify that text deliverables are separated and listed.   |
 |  7 | After adding a deliverable, click on the trash button on one deliverable     | Verify that a deliverable chosen will be deleted from the list.   |
 |  8 | Click on `upload cover photo` input box      | Verify that gallery or your album will be displayed to choose pictures from.   |
 |  9 | Click on any image from your gallery     | Verify that your chosen image will be displayed in the picture input box.   |
 |  10 | Click on the `proceed` button      | Verify that `Add Mentor` screen will be closed and proceeding with an empty or lacking necessary inputs are not allowed.   |
 
**Post-conditions:**  

   - Add Course page will be closed
   - Snackbar for a successful creation will be shown
   - Course will be added to the list without a mentor

 

 

