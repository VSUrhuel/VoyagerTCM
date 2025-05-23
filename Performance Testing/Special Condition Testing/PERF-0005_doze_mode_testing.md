## **PERF-0005:** Doze-mode testing  

> **Summary:** Verify that the app can handle requests after timeouts.  <br>

**Preconditions:** _None_  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Leave the device idle long enough to trigger Doze mode.   | Verify that the device enters Doze mode; background activities are restricted.   | 
 |  2 |   Schedule or expect a background task   | Verify that task is deferred during Doze, as per system behavior.   | 
 |  3 |   Wake the device and open the app.   | Verify that app resumes normally and pending tasks are processed.   |  

**Post-conditions:**  

- App remains stable after Doze mode.

- Pending tasks are handled upon device wake.

- No crashes or lost data due to Doze restrictions.
