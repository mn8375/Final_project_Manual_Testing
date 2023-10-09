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
To ensure testing has been provided and made available to testers: Approved test plan, Access to relevant documentation for the software product, Test environments prepared (installation, software configuration, database, etc.), Access to systems and functionalities (accounts, permissions). Functional business specifications are defined and testing environment is up and running;

#### 1.1.3 Exit criteria defined

all planned test cases were executed;

63% of the tests passed;

5 bugs were found and an update of application will come to solve them

retesting and regression testing will be made after application update

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

H. Customers can have difficulties to place orders

![Analiza riscuri](https://github.com/mn8375/Final_project_Manual_Testing/assets/130221800/730d5716-21fe-4e80-a225-6b3b611afdca)

#### 1.1.6 Evaluating entry criteria

The entry criterias defined in the Test Planning phase have been achieved and the test process can continue. 

## 1.2 Test Monitoring and Control

It will be done by generating periodic reports that reflect the current status of the test.

![Test Metrics](https://github.com/mn8375/Final_project_Manual_Testing/assets/130221800/4421ae77-d0e1-4609-a09b-60ab1ab3bbaf)


## 1.3 Test Analysis

The testing process will be executed based on the requirements for the Dependents module. 

![NM-5](https://github.com/mn8375/Final_project_Manual_Testing/assets/130221800/e2c5cb34-c026-4065-bbb2-35b4a28d1640)

![NM-12](https://github.com/mn8375/Final_project_Manual_Testing/assets/130221800/68ab4d39-5d76-464e-af9b-f744cdb49a34)

## 1.4 Test Design

Functional test cases were created in Jira. 

**Test cases:**

![Test cases](https://github.com/mn8375/Final_project_Manual_Testing/assets/130221800/a48a05d6-7a8c-4444-800e-64a676bd6607)


Some test cases with steps can be viewed here: 

[NM-22.pdf](https://github.com/mn8375/Final_project_Manual_Testing/files/12766237/NM-22.pdf)
[NM-27.pdf](https://github.com/mn8375/Final_project_Manual_Testing/files/12766214/NM-27.pdf)
[NM-25.pdf](https://github.com/mn8375/Final_project_Manual_Testing/files/12766213/NM-25.pdf)
[NM-8.pdf](https://github.com/mn8375/Final_project_Manual_Testing/files/12766212/NM-8.pdf)
[NM-7.pdf](https://github.com/mn8375/Final_project_Manual_Testing/files/12766211/NM-7.pdf)

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

