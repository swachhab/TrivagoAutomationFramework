# TrivagoAutomationFramework
This framework is about executing web application test cases using Robot Framework and python. Written all the given test cases with execution reports.

# Pre-Requisites:
Mac/Windows System.
python
chrome-driver and its path in system variable.
plugins - robotframework, selenium, robotframework-extendedselenium2library
Some Knowledge about selenium and robot framework.


# Framework Structure:
1. Batch: This folder contains 
    a batch file “Run_Command.command” to trigger test execution. 
2. Test Selector file “test_selector.ini” to specify which test cases to run and just need to write name of test case file and ‘y’/’n’ in order to specify test cases to run.
3. Library: This folder contains
   “ApplicationLibrary.py” A python file in which robot keywords can be developed.
   “Common_Keywords.txt” This file contains robot keywords which are imported to all test cases.
4. Locators: This folder contains:
   “Locators_Lib.txt” This file contains all the locators that can be used by all test cases, this file is written in order to reduce effort while changing any locator.
5. Results: This folder contains all the log files and reports that robot generates. It stores all those files in sub directory with time stamp in its name in order to record reports of all runs.
6. src: This folder contains python’s source code that will drive whole test execution.
7. TestCases: In this folder all the test cases are stored.
