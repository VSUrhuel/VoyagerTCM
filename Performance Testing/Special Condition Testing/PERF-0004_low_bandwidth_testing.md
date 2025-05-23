## **PERF-0004:** Low-bandwidth testing  

> **Summary:** Verify that the app can handle requests in a congested network.  <br>

**Preconditions:** _None_  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Simulate a low-bandwidth network (e.g., using a network throttling tool or by switching to 2G/3G).   | The app detects slower network speeds and adapts accordingly (e.g., shows loading indicators).   | 
 |  2 |    Attempt to perform a network request (e.g., login, fetch data, or load a page).  | The request completes successfully or gracefully times out with a user-friendly message.   | 
 |  3 |   Navigate through the app while network speed remains low.   | The app remains responsive, avoids crashes, and handles delays gracefully (e.g., caching, retry mechanisms).   |  

**Post-conditions:**  

- The app remains functional and does not crash under low-bandwidth.
- All requests either succeed eventually or fail gracefully with appropriate error messaging.
- User can still navigate or retry operations without needing to restart the app.

 
