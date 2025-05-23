## **PERF-0006:** Low-power testing  

> **Summary:** Verify that the app can handle requests in low battery mode.  <br>

**Preconditions:** 
- Make sure that the device has a low power or battery saving feature

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Enable low power/battery saver mode on the device.   | Verify that device enters low power mode; system may restrict background activity.   | 
 |  2 |   Launch the app and perform common tasks (e.g., login, navigation, data fetch).   | Verify that app functions normally, possibly with adjusted performance.   | 
 |  3 |   Trigger a background action.   | Verify that app respects system constraints; background tasks are deferred or handled gracefully   |  

**Post-conditions:**  

- App remains usable and stable in low power mode.

- No crashes or performance issues occur.

- Background tasks are managed appropriately under system constraints.
