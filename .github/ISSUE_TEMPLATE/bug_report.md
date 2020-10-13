---
name: Bug report (Mcmemrle)
about: Create a report to help us improve
title: 'Bug 1'
labels: 'Assertion Error'
assignees: 'Wake Tech'

---

**Describe the bug**
User Input for retirment past year 2020 causing error in program

**Program**
Retirment Calculator

**Component**
Full_Retirement_Calc.py

**Error Type**
Coding Error

**Severity**
Fatal

**Priority**
TBD

**State**
Fixed

**To Reproduce**
Steps to reproduce the behavior:
1. 1.	Run “test__full_retirement_calc.py” module : test_retirement_0
2.	Shows Assertion Error for 2020 Input Error
3.	Move to “Current_Year” on Full_retirement_calc.py Then to module full_retirement_age. The First “IF” loop returns the current year and this returns -1, -1. 
4.	.Change Return Statement to Return 67, 0. This is pulled from the Social security website as the last age to retire at currently. 
5.	This will make this clear this Assertion Error 
**Expected behavior**
With these changes the user will be able to input any age free up to our current year for finding the retirement age by inputting the year and month they were born in.

**Screenshots**


**Desktop (please complete the following information):**
 - OS: Windows 10
 - Browser Chrome
 

**Additional context**
N/A

**Assigned**
Unassigned

**Defect Type**
For ODC later.  
One of
* Interface
* Function
* Build/Package/Merge
* Assignment
* Documentation
* Checking
* Algorithm
* Timing/Serialization

**Defect Trigger**
For ODC later.
One of
* Review and Inspection Triggers
* Unit and Function Test Triggers
* System and Field Test Triggers

**Defect Impact**
For ODC later.
One of
* Capability
* Usability
* Performance
* Reliability
* Installability
* Maintainability
* Documentation
* Migration
* Standards
* Integrity/Security
