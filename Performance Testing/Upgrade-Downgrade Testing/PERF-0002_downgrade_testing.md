## **PERF-0002:** Downgrade testing  

> **Summary:** Verify that the application can downgrade successfully.  <br>

**Preconditions:** 
- Make sure you have the latest version of the application 

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Install the latest version of the app and use it normally.   | Verify that app behaves as expected; data and preferences are saved.   | 
 |  2 |   Uninstall the current version and install an older version of the app.   | Verify that cowngrade installs successfully without system errors.   | 
 |  3 |   Launch the downgraded app and access previous data or features.   | Verify that app launches properly, and either accesses old data or handles incompatibilities gracefully.   |  

**Post-conditions:**  

 - The downgraded app launches and functions without critical errors.
 - User data is either retained, gracefully reset, or user is prompted to reconfigure.
 - No crashes or major functionality loss occurs due to version conflict.  
