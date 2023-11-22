---
name: Manual Test Pass
about: Used to track running a manual test pass. Only create this item when following test plan instructions.
title: Manual Test Pass
labels: 
---

This issue is to track running a manual test pass. Used for build validation or release.

## Running Tests

For each case in the `Tests` block below, run the steps. Then check the expected state after the steps have been run: 

If the expected state matches the actual state, check the checkbox inside the case to mark the task as complete. 

If anything along the way has prevented the test from being run, or the expected state does not match the actual state, then create an Issue to file the test failure:

1. Click the Issue symbol on the right hand side when hovering over the task line to create an issue with the task name.
1. Copy the body of the failed test case into the issue
1. Add an **Actual** line after the **Expected** line to describe the behavior
1. Or edit the steps to describe where the failure happened (earlier in the case) and adjust the actual and expected
1. Modify the issue title to accurately describe the failure (like you would for a behavioral issue)

## Tests

<!-- Paste in block of test cases to run -->
