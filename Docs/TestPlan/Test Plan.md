**Test Plan – VLC Android App**

|**S. N**|**Name**|**Description**||||
| :- | :- | :- | :- | :- | :- |
|**1.**|**Introduction**|Overview of the test plan, objectives, and scope.||||
|**2.**|**Test Strategy**|Testing approach, types of testing, and levels covered.||||
|**3.**|**Test Scope**|Features included and excluded in testing.||||
|**4.**|**Test Environment**|Details of devices, OS versions, and network setups used for testing.||||
|**5.**|**Test Deliverables**|List of documents and reports generated during testing.||||
|**6.**|**Test Execution Plan**|Steps to execute test cases, bug reporting, and tracking.||||
|**7.**|**Roles and Responsibilities**|Team members responsible for testing activities.||||
|**8.**|**Risks and Mitigation**|Possible risks in testing and how to handle them.||||
|**9.**|**Exit Criteria & Suspension**|Conditions to stop testing or pause it if needed.||||
|**10.**|**Test Schedule**|Timeline for test execution.||||



**1. Introduction**

**1.1 Purpose**

The purpose of this test plan is to define the strategy and approach for testing the VLC Android App. The goal is to ensure that all features work as expected, the app is stable, and there are no major issues before release.

**1.2 Scope**

This test plan covers the functional and non-functional aspects of the VLC Android App. The testing will focus on media playback, file management, subtitles, network streaming, UI/UX, performance, and compatibility on different Android devices.

**1.3 Objectives**

- Verify that VLC supports various media formats (video/audio).
- Ensure media playback features (play, pause, seek, speed adjustment) work correctly.
- Test subtitles, multi-audio tracks, and network streaming functionalities.
- Evaluate UI usability, performance, and app stability.
- Check compatibility across different Android versions and screen sizes.
-----
**2. Test Strategy**

**2.1 Testing Approach**

- **Manual Testing:** Will be used to check the basic functionalities and UI.
- **Exploratory Testing:** To find unexpected bugs by freely using the app.
- **Regression Testing:** To ensure new updates don’t break existing features.

**2.2 Testing Levels**

- **Unit Testing:** Ensuring individual functions work properly.
- **Integration Testing:** Checking how different parts of the app interact.
- **System Testing:** Testing the whole app to ensure all features work together.
- **User Acceptance Testing (UAT):** Checking if the app meets user expectations.

**2.3 Testing Types Covered**

- **Functional Testing** – To verify app features like playback, subtitles, streaming.
- **UI/UX Testing** – To check app design, layout, and user-friendliness.
- **Performance Testing** – To check speed, lag, and app stability.
- **Compatibility Testing** – To check app behaviour on different Android devices.
- **Security Testing** – To ensure user data privacy and app security.
-----


**3. Test Scope**

**3.1 Features to be Tested**

- Media Playback (Play, Pause, Stop, Seek, Speed control)
- File Management (Scan, Browse, Sort, Rename, Delete)
- Subtitles & Audio Tracks (Enable, Sync, Load External)
- Network Streaming (URL streaming, Local Network, Casting)
- UI & Gestures (Dark Mode, Brightness/Volume Gestures)

**3.2 Features Not in Scope**

- ` `VLC Desktop or iOS versions
- Advanced developer settings
-----
**4. Test Environment**

**4.1 Devices & OS**

- **Android Versions:** 8.0 (Oreo) to 15
- **Devices:** 
  - Samsung Galaxy Tab A9
  - Realme 
  - Redmi k50i
  - iPhone

**4.2 Network Setup**

- Wi-Fi & Mobile Data for streaming tests
-----
**5. Test Deliverables**

- **Test Scenarios** – High-level scenarios covering major features.
- **Test Cases** – Step-by-step test cases with expected results.
- **Bug Reports** – Issues found, logged with screenshots.
- **Test Summary Report** – Final test results and recommendations.


**6. Test Execution Plan**

**6.1 Test Case Execution**

- Run test cases on different devices and OS versions.
- Note pass/fail status for each test case.
- Log bugs in **Jira** with severity levels.

**6.2 Defect Reporting & Tracking**

- **Severity Levels:**
  - **Critical:** App crashes, data loss.
  - **High:** Major features not working.
  - **Medium:** Minor glitches, UI issues.
  - **Low:** Cosmetic issues.
- **Bug Tracking Tool:** Jira
-----
**7. Roles & Responsibilities**

|**Role**|**Responsibility**|
| :- | :- |
|**QA Engineer**|Writing & executing test cases, reporting bugs|
|**Test Lead**|Reviewing test strategy, tracking progress|
|**Developer**|Fixing reported bugs|
|**Project Manager**|Managing timelines & ensuring quality|

-----
**8. Risks & Mitigation**

|**Risk**|**Mitigation Strategy**|
| :- | :- |
|**App crashes on specific devices**|Test on multiple devices, report issues|
|**Network streaming not working**|Check different networks, report findings|
|**UI layout breaks on different screens**|Test on various screen sizes|

-----
**9. Exit Criteria & Suspension**

**9.1 Exit Criteria**

Testing will stop when:

- All high and critical bugs are fixed.
- Test cases achieve 95% pass rate.
- App meets business and user expectations. 
 

**9.2 Suspension Criteria**

Testing may be paused if:

- Major technical issues block further testing.
- Test environment is unavailable.

  -----

**10. Test Schedule**

|Task |Start Date |End Date |
| :- | :- | :- |
|**Test Planning** |March 7, 2025|March 8, 2025|
|**Test Scenarios**|March 8, 2025|March 8,2025|
|**Test Case Writing**|March 8, 2025|March 10, 2025|
|**Test Execution**|March 10,2025|March 11,2025|
|**Bug Reporting & Fixing** |March 11,2025|March 12, 2025|
|**Final Report** |March 12, 2025|End|

