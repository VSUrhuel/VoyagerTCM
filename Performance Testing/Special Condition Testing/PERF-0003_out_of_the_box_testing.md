## **PERF-0003:** Out-of-the-Box testing  

> **Summary:** Verify that the app can perform installation and setup successfully.  <br>

**Preconditions:** 
- A compatible device (e.g., Android/iOS phone or target platform) is available.
- The device has a stable internet connection.
- The latest version of the app installation file (.apk/.ipa) or access to the app store is available.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Install the application from the official source (App Store/Play Store or .apk).   | The app installs without errors and an icon appears on the device.   | 
 |  2 |   Launch the app after installation.   | Verify that splash screen is displayed and then transitions to the onboarding or login page.   | 
 |  3 |   Complete initial setup (e.g., permissions, onboarding, login/registration).   |  All prompts (permissions, walkthrough, etc.) function correctly, and the user lands on the home screen.  |  

**Post-conditions:**  

 - The app is successfully installed on the device.
 - User has completed the setup process and reached the main screen/dashboard.
 - Necessary permissions (e.g., location, camera, notifications) have been granted or handled appropriately.
