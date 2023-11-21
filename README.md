# Redmine Project  


### Revision History

| Date | Description   | Author   | Comments |
| :-----: | :---: | :---: | :---: |
| 05.09.2023 | Test Plan for version 1.0   | Andrada Pricop   | draft test plan |
| 09.21.2023 | v1.1  | Andrada Pricop   | Added more details for Test Process |
| 10.18.2023 | v1.1  | Andrada Pricop   | Added the final version for bugs report |


### Table of Content:

1. Introduction
    
            1.1 Project Objective 
            
            1.2 Functionalities in scope

            1.3 Functionalities and tests out of scope

2. Test process
    
            2.1 Test planning
            
            2.2 Test analysis

            2.3 Test design

            2.4 Test implementation

            2.5 Test execution

            2.6 Test closure

            2.7 Test monitoring and control

3. Test deliverables
    
            3.1 Test plan
            
            3.2 Test conditions

            3.3 Test cases

            3.4 Daily test summary reports

            3.5 Traceability matrix

            3.6 Test case results

            3.7 Bugs report

            3.8 Test completion report


### 1 Introduction
Redmine is a flexible project management web application. Written using the Ruby on Rails framework, it is cross-platform and cross-database.

Redmine is open source and released under the terms of the GNU General Public License v2 (GPL).


### 1.1 Project Objective
We need to raise the trust in the quality of the project as high as possible before releasing it to customers.


Application under test: https://www.redmine.org/ 


Documentation: https://www.redmine.org/guide


### 1.2 Functionalities in scope
  - All the features of My account module which were defined in Redmine business requirements will be tested using the following testing types: functional testing, GUI testing, API testing. 
  - The Redmine Web application will be tested on latest versions of Chrome and IE.


### 1.3 Functionalities and tests out of scope
  - All the features that are not under My account  module 
  - Non-functional testing like stress, performance is beyond scope of this project
  - No QA support for mobile applications developed, only web applications will be tested
  - Automation testing is beyond scope.

 
### 2 Test process
### 2.1 Test Planning

| Roles | Responsabilities | 
| :-----: | :---: |
| Andrada - Tester |  will test: all features from My account module: Information, Email notifications, Email address, Preferences and Password | 


#### Entry criteria:
- smoke test passed (being the most basic type of test, this is a very important entry criteria in the process of testing)
- testing environment is up and running
- roles needed for the project are allocated 
- functional specifications are defined
- test data is prepared

#### Exit criteria:
- 100% tests from Functional testing were wxecuted and 58.33% are passed
- 100% tests from GUI testing were executed and 80% are passed
- some Critical issues have Open status
- update tests are 100% passed 
- exploratory testing was performed on My account module

#### Risks:
- stability risks (crashes, disconnects, etc)
- IE browser might have performance issues
- the web page pagination could be impacted when opened on mobile devices
- stress conditions might impact the web application
- new browser might not be supported


### 2.2 Test analysis 
Analyze the business requirements to make sure that we have all the details for creating the test conditions 
Write test conditions (What?)
we plan on running a full regression test on the current version


### 2.3 Test design
all the test cases are written and reviewed 
All test cases will be created in Jira as test management tool


### 2.4 Test implementation
all the test data is available and reviewed (an account with Admin Role was created)
this test run includes only regression testing in which we will run tests that have the highest priority, this will be main priority
Test suites are created (Cycle Summary was created)


### 2.5 Test execution
the tests will be executed on the following browsers: Chrome and IE if time will be available we will extend tests on Mozilla and Brave browsers
Bugs will be created based on the failed test cases 
The full regression testing will be done after new application changes 
Retesting will be done after a bug is fixed 


### 2.6 Test closure
100% tests were executed and 90% of them are passed 
no Critical issues have Open status


### 2.7 Test monitoring and control
Various periodic reports will be generated to reflect the current status of testing process, in case of major problems control measures could be taken. 



### 3 Test deliverables
### 3.1 Test plan
[Test Plan]()


### 3.2 Test conditions 
 - we will use prod environment
 - testing using new accounts or existing account is necessary
   
[Test Conditions](https://github.com/Andrada2192/RedmineProject/blob/main/Test%20Conditions%20Jira%20RedmineApp%20.pdf)



### 3.3 Test cases
[Test Cases](https://github.com/Andrada2192/RedmineProject/blob/main/AllTestCases.pdf)



### 3.4 Daily test summary report
#### Raportul generat in data de 11/07/2023 arata rularea a 10 test case-uri dintre care 3 failed si 1 blocked.
![Daily report](https://github.com/Andrada2192/RedmineProject/blob/main/daily%20rep%207noi%20(2).png)  
![Daily report](https://github.com/Andrada2192/RedmineProject/blob/main/daily%20rep%207noi.png)


#### Raportul generat in data de 11/09/2023 arata rularea a 12 test case-uri dintre care 4 failed.
![Daily report](https://github.com/Andrada2192/RedmineProject/blob/main/386886359_638780408179584_6632357104543974468_n.png)
![Daily report](https://github.com/Andrada2192/RedmineProject/blob/main/380826740_876341894084574_3891748152558190536_n.png)



### 3.5 Traceability matrix
![Traceability Matrix](https://github.com/Andrada2192/RedmineProject/blob/main/TraceabilityMatrix.png)
           


### 3.6 Test case results
[Test Case Results](https://github.com/Andrada2192/RedmineProject/blob/main/TestCaseResults.pdf)



### 3.7 Bugs report
[Bugs Report](https://github.com/Andrada2192/RedmineProject/blob/main/BugsReport.pdf)



### 3.8 Test completion report
![Test Completion](https://github.com/Andrada2192/RedmineProject/blob/main/TestExecution.png)



### 3.9 Schedule
 - we have 3 days of testing
 - we have 22 test cases 
 - in order to finish the regression run we would need to run an ~ of 7 tests/day

