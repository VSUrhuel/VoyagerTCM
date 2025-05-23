## **PERF-0001:** Upgrade testing  

> **Summary:** Verify that the application can upgrade successfully.  <br>

**Preconditions:** 
- Make sure that you have an existing version of the application already installed in the device
- It should be an older model

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Install an older, stable version of the app.   | Verify that app installs successfully and functions normally.   | 
 |  2 |   Upgrade the app to the latest version via app store or manual update.   | Verify that upgrade completes without errors; user data and settings are retained.   | 
 |  3 |   Launch the upgraded app and navigate through key features.   | Verify that app opens normally, new features are available, and no crashes or regressions occur.
   |  

**Post-conditions:**  

 - App is running the latest version.
 - No user data is lost during the upgrade.
 - App functionality is fully retained and stable.
