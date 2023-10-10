# Final project Manual Testing

The scope of the final project is to use all gained knowledge throught the course and apply them in practice, using a live application. 

Application under test: https://www.anvelope-autobon.ro/


Tools used: Jira by Atlassian with Zephyr plugin

# Functional specifications

[Requirements.pdf](https://github.com/mn8375/Final_project_Manual_Testing/files/12846513/Requirements.pdf)


# 1 Testing section

## 1.1 Test Planning

The Test Plan is designed to describe all details of testing for the "CONT NOU" and "INTRA IN CONT" modules from the autobon.ro application. 

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan

#### 1.1.1 Roles assigned to the project and persons allocated

Product owner: IT Factory

Project manager: Gabriela Radulescu

QA Tester: Mihai Noaptes

#### 1.1.2 Entry criteria defined
To start the testing process has been provided to the testers: 
* Approved test plan 
* Access to relevant documentation for the software product 
* Test environments prepared (installation, software configuration, database, etc.)
* Access to systems and functionalities (accounts, permissions) 
* Functional business specifications are defined and testing environment is up and running

#### 1.1.3 Exit criteria defined

* Meeting the deadlines and budget constraints
  
* Executing and updating all the test cases
  
* Achieving the desired and sufficient coverage of the requirements and functionalities
  
* Identifying and fixing all the high-priority and critical bugs
  
* Re-testing and closing all the defects and executing the regression scenarios successfully


#### 1.1.4 Test scope

* Tests in scope: all features of the "CONT NOU" and "INTRA IN CONT" modules that have been defined in the requirements and technical specifications, for the www.autobon.ro, must be tested. Other functionalities specific to web pages launched online, such as functional tests, GUI tests, etc.
  
* Tests not in scope: compatibility tests with multiple operating systems (other than Windows), existing previously implemented functionality such as stress, performance, security tests. Only web pages will be tested, no mobile apps are developed. Automated testing is out of scope.


#### 1.1.5 Risks detected

* Project risks:
  
A. Insufficient testing staff

B. Inexperience of testing staff	

C. Testing is done under short time pressure	

D. Possibility to remain undiscovered bugs

* Product risks:
  
E. Risks related to the security of personal data

F. Risks of economic losses due to wrong deliveries			

G. The final product is unintuitive and complicated for users		

H. Customers can have difficulties to place orders

#### ![Risk analyze](https://github.com/mn8375/Final_project_Manual_Testing/assets/130221800/88decbdf-5212-433b-ac1d-7f67b0822f72)

1.6 Evaluating entry criteria

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue. 

## 1.2 Test Monitoring and Control

It will be done by generating periodic reports that reflect the current status of the test.

![Test Metrics](https://github.com/mn8375/Final_project_Manual_Testing/assets/130221800/4421ae77-d0e1-4609-a09b-60ab1ab3bbaf)


## 1.3 Test Analysis

The testing process will be executed based on the requirements for the Dependents module. 

![NM-5](https://github.com/mn8375/Final_project_Manual_Testing/assets/130221800/e2c5cb34-c026-4065-bbb2-35b4a28d1640)

![NM-12](https://github.com/mn8375/Final_project_Manual_Testing/assets/130221800/68ab4d39-5d76-464e-af9b-f744cdb49a34)

## 1.4 Test Design

Functional test cases were created in Jira. 

[Tests list.pdf](https://github.com/mn8375/Final_project_Manual_Testing/files/12852979/Tests.list.pdf)

## 1.5 Test Implementation

Test environment is up and running: (https://www.anvelope-autobon.ro/).

## 1.6 Test Execution

* Test cases are executed on the created test Cycle summary: [Cycle_summary.xlsx](https://github.com/mn8375/Final_project_Manual_Testing/files/12728725/Cycle_summary.xlsx)

* Bugs tickets have been created based on the failed tests. Below the bugs report:
  
[Bugs list.pdf](https://github.com/mn8375/Final_project_Manual_Testing/files/12852988/Bugs.list.pdf)

## 1.7 Test Completion

* The traceability matrix was generated and can be found here: [Traceability_Matrix.xlsx](https://github.com/mn8375/Final_project_Manual_Testing/files/12728125/Traceability_Matrix.xlsx)

* Test execution chart was generated, the final report shows that all 11 test were completed and we had 4 fails and 7 pass

below the final test execution report/chart

![Test Execution](https://github.com/mn8375/Final_project_Manual_Testing/assets/130221800/7945996c-7bbf-4585-bd98-87963fc25f0c)

General conclusions after testing

* During the testing, both proposed stories were covered and all 11 test cases planned for execution were completed.
* Out of the 11 tests, 4 were failed and a total of 5 medium and low priority bugs were discovered. These do not affect the exploitation of the application by the beneficiary company, but represent security risks for it and difficulties in the use by customers that can lead to economic losses.
* The reported defects are being fixed
* Product risks will be reduced by upgrading the application.
* Retesting and regression testing will be done for the new version of the application.

