## **ADMIN-001:** Admin Management Testing - Create Mentor Initial Account  

> **Summary:** Verify admins can create unverified mentor accounts with default password.  <br>

**Preconditions:** 
- Admin credentials from the developer team
- Mentor email must not yet registered to the system previously
- Default password must be `mentor2025`


Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 | Launch Application    | Verify that on-boarding screen  is screen is shown for first time user or the welcome screen for existing user.   | 
 |  2 | Log-in as `admin` using developer generated admin credentials       | Verify that the admin home interface is displayed.   | 
 |  3 | Click on Mentor `Management` tab     | Verify that `Mentor List` was displayed.   |
 |  4 | On the upper right of the screen, below search bar, click on `+` button     | Verify that `Add Mentor` interface is displayed with six boxes to fill-up.   |
 |  5 | Click on the `Course to Mentor` box     | Verify that existing courses will only be displayed to choose on when there are courses available.   |
 |  6 | Fill-in the textboxes and use `mentor2025` as default password for mentor      | Verify that text boxes can be filled and inputs persists when clicking other parts of the screen.   |
 |  7 | Click on `upload profile picture` box      | Verify that gallery or your album will be displayed to choose pictures from.   |
 |  8 | Click on any image from your gallery     | Verify that your chosen image will be displayed in the picture input box.   |
 |  9 | Click on the `proceed` button      | Verify that `Add Mentor` screen will be closed and proceeding with an empty or lacking inputs are not allowed.   |
 
**Post-conditions:**  

 - Mentor account successfully created
   - Add Mentor page will be closed
   - Snackbar for a successful creation will be shown
   - Initial mentor account created will be added in `Mentor List` within the `Archived`
 - Unsuccessful mentor account creation  
   - If account already exists, firebase related error snack bar displays
   - If lack inputs, graceful warning or reminder snackbar displays
 
