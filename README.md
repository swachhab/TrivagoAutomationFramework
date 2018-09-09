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
   “Locators_Lib.txt” This file contains all the locators that can be used by all test cases, this file is written in order to  
   reduce effort while changing any locator.
5. Results: This folder contains all the log files and reports that robot generates. It stores all those files in sub  
   directory with time stamp in its name in order to record reports of all runs.
6. src: This folder contains python’s source code that will drive whole test execution.
7. TestCases: In this folder all the test cases are stored.

# Features or capabilities of this Framework
1. Anybody, without any language knowledge can write selenium test cases.
2. Very easy debugging of test results with concise html report.
3. All test cases are written in separate files, So if any new test case need to be added by some user in future, he/she just need to add a new file and name of file in test_selector.ini file.
4. Locators are separated from test cases, so that if there's any change in locator, it can be easily changed in that common file.
5. Reports are generating in seperate folder with time stamp in order to get historical report of any test case.
6. [For Future] This framework can easily be integrated with jenkins for end to end testing.
7. [For Future] We can easily add support for mobile devices with appium library of robot framework.
8. Last but not least, report file for current execution will get open automatically once test execution get over.
