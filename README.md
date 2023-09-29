# Final project for ITF Manual Testing Course

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application. 

Application under test: https://www.anvelope-autobon.ro/


Tools used: Jira by Atlassian with Zephyr plugin

# Functional specifications


# 1 Testing section

## 1.1 Test Planning

The Test Plan is designed to describe all details of testing for the "CONT NOU" and "INTRA IN CONT" modules from the autobon.ro application. 

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan

#### 1.1.1 Roles assigned to the project and persons allocated

Product owner: IT Factory

Project manager: Gabriela Radulescu

QA Tester: Mihai Noaptes

#### 1.1.2 Entry criteria defined
To ensure testing has been provided and made available to testers: Approved test plan, Access to relevant documentation for the software product, Test environments prepared (installation, software configuration, database, etc.), Access to systems and functionalities (accounts, permissions). entry criteria;
functional business specifications are defined;
esting environment is up and running;
smoke test passed (being the most basic type of test, this is a very important entry criteria in the process of testing).

#### 1.1.3 Exit criteria defined
all planned test cases were executed;
70% of the tests passed;
no critical issues/bugs have open status (all unresolved bugs have low priority and severity from the point of view of software functionality).
#### 1.1.4 Test scope

* __Tests in scope:__ All features of the "CONT NOU" and "INTRA IN CONT" modules that have been defined in the requirements and technical specifications, for the www.autobon.ro, must be tested. Other functionalities specific to web pages launched online, such as functional tests, GUI tests, etc.
  
* __Tests not in scope:__ Out-of-scope tests: compatibility tests with multiple operating systems (other than Windows), existing previously implemented functionality such as stress, performance, security tests. Only web pages will be tested, no mobile apps are developed. Automated testing is out of scope.


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

H. Customers cannot place orders

* ![Analiza riscuri](https://github.com/mn8375/Final_project_Manual_Testing/assets/130221800/bce0fd3d-41bd-431f-9a24-d4a5299a0625)


#### 1.1.6 Evaluating entry criteria

The entry criterias defined in the Test Planning phase have been achieved and the test process can continue. 

## 1.2 Test Monitoring and Control

It will be done by generating periodic reports that reflect the current status of the test.

![Test Metrics](https://github.com/mn8375/Final_project_Manual_Testing/assets/130221800/4421ae77-d0e1-4609-a09b-60ab1ab3bbaf)


## 1.3 Test Analysis

The testing process will be executed based on the above requirements for the Dependents module. The following test conditions were found:
 * Enter test conditions here

## 1.4 Test Design

Functional test cases were created in Jira. 

**Test cases:**

![Test cases](https://github.com/mn8375/Final_project_Manual_Testing/assets/130221800/a48a05d6-7a8c-4444-800e-64a676bd6607)


The test cases with steps can be viewed here: [test_cases.pdf]()

## 1.5 Test Implementation

Test environment is up and running: (https://www.anvelope-autobon.ro/).

## 1.6 Test Execution

* Test cases are executed on the created test Cycle summary: [Cycle_summary.xlsx](https://github.com/mn8375/Final_project_Manual_Testing/files/12728725/Cycle_summary.xlsx)

* Bugs tickets have been created based on the failed tests. The bug reports can be found below:
[NM-9.pdf](https://github.com/mn8375/Final_project_Manual_Testing/files/12728818/NM-9.pdf) ,
[NM-10.pdf](https://github.com/mn8375/Final_project_Manual_Testing/files/12728821/NM-10.pdf) ,
[NM-23.pdf](https://github.com/mn8375/Final_project_Manual_Testing/files/12728824/NM-23.pdf) ,
[NM-26.pdf](https://github.com/mn8375/Final_project_Manual_Testing/files/12728826/NM-26.pdf) ,
[NM-28.pdf](https://github.com/mn8375/Final_project_Manual_Testing/files/12728827/NM-28.pdf)

## 1.7 Test Completion

* Exit criteria was evaluated and passed
* The traceability matrix was generated and can be found here: [Traceability_Matrix.xlsx](https://github.com/mn8375/Final_project_Manual_Testing/files/12728125/Traceability_Matrix.xlsx)

* Test execution chart was generated, the final report shows that all 11 test were completed and we had 4 fails and 7 pass

below the final test execution report/chart

![Test Execution](https://github.com/mn8375/Final_project_Manual_Testing/assets/130221800/7945996c-7bbf-4585-bd98-87963fc25f0c)

