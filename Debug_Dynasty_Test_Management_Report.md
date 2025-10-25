# **Debug Dynasty Test Management Report: Word Puzzle Game Plus**

1. **Team & Roles**
   | Name             | Roles         |
   | ---------------- | ------------- |
   | Juliet Nakawesi  | Test Manager  |
   | Maureen Muriithi | Test Executor |
   | Donie Golanda    | Risk Analyst  |
2. ## **Test Plan**

   Objectives

- To verify the functionality of the features: Reset Game, Leaderboard, and Bonus Round.
- To identify and log at least 3 defects related to the features or game logic.
- To manage the testing process using risk-based prioritization.
- To document and report on test execution status, metrics, and team findings.

### Scope (In & Out)

In Scope:

- Functional testing of all game features.
- Data integrity testing for localStorage (Leaderboard).
- State management testing (Reset, Bonus tracking).
- Usability testing of the main game interface.
- Defect reporting and re-testing of fixes.

# Out of Scope:

- Cross-browser testing (testing is restricted to the specified environment).
- Performance, load, or stress testing.
- Code-level unit testing or white-box testing.
- Security testing.
- Mobile device responsiveness testing.

## Resources (Roles & Tools)

- Team: 1 Test Manager, 1 Risk Analyst, 1 Test Executor.
- System Under Test (SUT): index.html (local file).
  Tools:
- GitHub Repository: For version control of the report.
- GitHub Issues: For defect tracking (mandatory).
- Jira: For task management (Kanban board).
- Whatsapp for communication
- Markdown Editor: (e.g., VS Code) for report writing.
- Screen Capture Tool: (e.g., Snipping Tool, ShareX) for defect evidence.

## Schedule

| Date                  | Time      | Phases    | Tasks                                                                       |
| --------------------- | --------- | --------- | --------------------------------------------------------------------------- |
| **Fri, Oct 24** | Morning   | Planning  | Draft Test Plan, Set up GitHub, Initial Risk Analysis,Create whatsapp group |
|                       | Afternoon | Design    | Complete Risk Analysis, Design all Test Cases                               |
|                       | Evening   | Execution | Begin executing test cases and logging initial defects.                     |
| **Sat, Oct 25** | Morning   | Finalize  | Finish test execution, log all defects, monitor metrics.                    |
|                       | Afternoon | Reporting | Gather all metrics, write team reflection.                                  |
|                       | Evening   | Reporting | Assemble and review final `Group_Test_Management_Report.md`. and submit   |

## * Entry & Exit Criteria

- Entry Criteria (To start testing):
- The index.html application is runnable in the test environment.
- The Test Plan is reviewed and approved by all team members.
- The initial Risk Analysis (Deliverable 3) is complete and prioritized.
- All Test Cases (Deliverable 4) are written and reviewed.

## * Exit Criteria (To finish testing):

- 100% of all planned test cases have been executed.
- 100% of test cases for "High" priority risks have passed.
- All found defects (minimum 3) are logged in GitHub Issues.
- No "Critical" or "High" severity defects remain in an "Open" state.
- All required test metrics (Deliverable 5) have been calculated and documented.
- The final reflection (Deliverable 6) is complete.

## * Test Environment

- Hardware: Standard Laptop/Desktop PC
- Operating System: Windows 10/11 or macOS
- Browser: Google Chrome (Latest Version)

6. Risk Analysis
   Risk Register (Minimum 6)
   Priority: Critical,High,Medium,Low

| ID | Risk Description | Likelihood (1-10) | Impact (1-10) | Priority | Mitigation |
|----|------------------|------------------|---------------|-----------|-------------|
| R1 | 'Reset Game' button fails to clear game state or scores | 6 | 9 | Medium | Re-check state management logic; re-test after each change to reset function |
| R2 | 'Leaderboard' fails to save or display scores correctly from localStorage | 8 | 10 | High | Implement consistent localStorage key usage; clear cache before tests; re-test with boundary data |
| R3 | 'Bonus Round' points not calculated or added to total correctly | 7 | 8 | Medium | Recheck the arithmetic logic; add unit test for bonus formula; verify updates after each round |
| R4 | 'Leaderboard' data lost when browser cache is cleared | 5 | 7 | Medium | Document expected behavior; add “Save/Export” option for users if feasible |
| R5 | UI freezes or lag occurs when restarting multiple times | 4 | 6 | Low | Optimize DOM updates; test reset cycles ≥10 times; monitor console for performance warnings |
| R6 | Player confusion due to unclear success/error messages | 5 | 5 | Low | Improve message text and color cues; conduct quick usability feedback test |

- Risk Register (Minimum 6)
- Priority: Critical,High,Medium,Low

| ID    | Risk Description                                                          | Likehood(1-10) | Impact(1-10) | Priority  | Mitigation                                                                                        |
| ----- | ------------------------------------------------------------------------- | -------------- | ------------ | --------- | ------------------------------------------------------------------------------------------------- |
|       |                                                                           |                |              |           |                                                                                                   |
| R1    | 'Reset Game' button fails to clear game state or scores                   | 6              | 9            | 54        | Re-check state management logic; re-test after each change to reset function                      |
| ----- | -----------------                                                         | ------         | -----        | --------- | ----------------                                                                                  |
| R2    | 'Leaderboard' fails to save or display scores correctly from localStorage | 8              | 10           | 80        | Implement consistent localStorage key usage; clear cache before tests; re-test with boundary data |
| R3    | 'Bonus Round' points not calculated or added to total correctly           | 7              | 8            | 56        | Recheck the arithmetic logic; add unit test for bonus formula; verify updates after each round    |
| R4    | 'Leaderboard' data lost when browser cache is cleared                     | 5              | 7            | 35        | Document expected behavior; add “Save/Export” option for users if feasible                      |
| R5    | UI freezes or lag occurs when restarting multiple times                   | 4              | 6            | 24        | Optimize DOM updates; test reset cycles ≥10 times; monitor console for performance warnings      |
| R6    | Player confusion due to unclear success/error messages                    | 5              | 5            | 25        | Improve message text and color cues; conduct quick usability feedback test                        |
|       |                                                                           |                |              |           |                                                                                                   |
|       |                                                                           |                |              |           |                                                                                                   |
|       |                                                                           |                |              |           |                                                                                                   |

### Risk Coverage Chart (Excel)

Below is the visual summary of risk distribution created in Excel:
--Risk Coverage Chart:(https://github.com/juliesuarez/Debug-dynasty/blob/main/risk_chart.jpg)

8. | Test Design & Execution | ID | Feature | Steps | Expected Result | Actual Result | Risk Priority | Status/Pass/Fail |
   | ----------------------- | -- | ------- | ----- | --------------- | ------------- | ------------- | ---------------- |
   | TC-01                   |    |         |       |                 |               |               |                  |
   |                         |    |         |       |                 |               |               |                  |
   |                         |    |         |       |                 |               |               |                  |
   |                         |    |         |       |                 |               |               |                  |
   |                         |    |         |       |                 |               |               |                  |
   |                         |    |         |       |                 |               |               |                  |
   |                         |    |         |       |                 |               |               |                  |
9. Defect Reporting

- (Minimum 3 defects logged on GitHub Issues)
- [BUG-01]: [Paste Link to GitHub Issue 1 here]
- [BUG-02]: [Paste Link to GitHub Issue 2 here]
- [BUG-03]: [Paste Link to GitHub Issue 3 here]
- 
- 
- 
- 
- 
- 

10. Test Monitoring & Metrics| Metric                  | Formula                             | Calculation | Result |
    | ----------------------- | ----------------------------------- | ----------- | ------ |
    | Test Case Pass %        | (Passed / Total) × 100             |             |        |
    | Defect Density          | Defects / Test Cases                |             |        |
    | Risk Coverage Ratio     | (Tested Risks / Total Risks) × 100 |             |        |
    | Regression Success Rate | (Passed / Total) × 100             |             |        |

NOTE:  Regression Success Rate is for re-testing bugs after they are "fixed"

11. Reflection

- Impact of Risk Analysis
  (Discuss how the Risk Analysis (Deliverable 3) focused your team's effort. Did you spend more time on the Bonus Round and Leaderboard because they were "High Priority"?)
- 
- 
- 
- 
- 

7.2. Testing Trade-offs (Coverage, Time, Depth)

(Discuss what you had to de-prioritize due to time. Did you sacrifice deep testing on low-risk features to ensure high-risk features were fully covered?)
---------------------------------------------------------------------------------------------------------------------------------------------------------

7.3. Team Collaboration

(Discuss how the team worked. Did using GitHub Issues and a Project board help or hinder? How did the 3 roles interact?)
------------------------------------------------------------------------------------------------------------------------
