[Cycle_summary.csv](https://github.com/mn8375/Final_project_Manual_Testing/files/12728688/Cycle_summary.csv)# Final project for ITF Manual Testing Course

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application. 

Application under test: https://www.anvelope-autobon.ro/


Tools used: Jira

# Functional specifications


# 1 Testing section

## 1.1 Test Planning

The Test Plan is designed to describe all details of testing for the "CONT NOU" and "INTRA IN CONT" modules from the autobon.ro application. 

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan

#### 1.1.1 Roles assigned to the project and persons allocated


#### 1.1.2 Entry criteria defined


#### 1.1.3 Exit criteria defined

#### 1.1.4 Test scope

* __Tests in scope:__ 
* __Tests not in scope:__ 

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

## 1.3 Test Analysis

The testing process will be executed based on the above requirements for the Dependents module. The following test conditions were found:
 * Enter test conditions here

## 1.4 Test Design

Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases 
are:

**Test cases:**
-> enter here test cases or at least the titles


The test cases with steps can be viewed here: [test_cases.pdf]()

## 1.5 Test Implementation

The following elements are needed to be ready before the test execution phase begins:

* enter here what needs to be ready for the test execution to begin

## 1.6 Test Execution

* Test cases are executed on the created test Cycle summary: [cycle_summary_execution.pdf]()   [UpExecutionId,CycleName,Issue Key,Test Summary,Project,Version,Priority,Executed By,Executed On,ExecutionStatus,ExecutionDefects,CreationDate,Assigned To,StepId,OrderId,Step,Test Data,Expected Result,Step Result,Comments,Step Custom Fields
bee4ecfb-f436-4ecb-86d0-a51abc341f7c,Lansare serviciu Hotel anvelope,NM-7,Verify if a new user can create a new account,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:46,PASS,,31/05/2023 15:35,,24aa4454-8a1d-4a43-bdeb-c4b25c2518e6,1,Open the browser and navigate to autobon.ro,Edge browser,The main page of app will be successfully loaded,PASS,,
bee4ecfb-f436-4ecb-86d0-a51abc341f7c,Lansare serviciu Hotel anvelope,NM-7,Verify if a new user can create a new account,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:46,PASS,,31/05/2023 15:35,,674ccf55-6be3-4cae-b3a8-c1fa9a187b0e,2,"On right top of main page click on ""person"" button",,"A pop up menu contains a ""CONT NOU"" button will open",PASS,,
bee4ecfb-f436-4ecb-86d0-a51abc341f7c,Lansare serviciu Hotel anvelope,NM-7,Verify if a new user can create a new account,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:46,PASS,,31/05/2023 15:35,,c06d9a7b-63af-4087-a65f-8692ad87e7f3,3,"Click on ""CONT NOU"" button",,The registration page is dispalyed,PASS,,
bee4ecfb-f436-4ecb-86d0-a51abc341f7c,Lansare serviciu Hotel anvelope,NM-7,Verify if a new user can create a new account,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:46,PASS,,31/05/2023 15:35,,1220bf70-9f49-4acd-9b5f-01cfe8818305,4,"In mandatory  text box ""Nume"" insert the name",Popescu,"The field is correctly marked as mandatory, with an *, and the value is successfully filled in and displayed.",PASS,,
bee4ecfb-f436-4ecb-86d0-a51abc341f7c,Lansare serviciu Hotel anvelope,NM-7,Verify if a new user can create a new account,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:46,PASS,,31/05/2023 15:35,,d9a4575d-81dd-4c48-9634-6bdaf07d1abf,5,"In mandatory  text box ""Prenume"" insert the name",Gigi,"The field is correctly marked as mandatory, with an *, and the value is successfully filled in and displayed.",PASS,,
bee4ecfb-f436-4ecb-86d0-a51abc341f7c,Lansare serviciu Hotel anvelope,NM-7,Verify if a new user can create a new account,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:46,PASS,,31/05/2023 15:35,,247683bf-aeef-492f-b2c1-2ff7245d337a,6,"In mandatory  text box ""Telefon"" insert the phone number",744666888,"The field is correctly marked as mandatory, with an *, and the value is successfully filled in and displayed.",PASS,,
bee4ecfb-f436-4ecb-86d0-a51abc341f7c,Lansare serviciu Hotel anvelope,NM-7,Verify if a new user can create a new account,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:46,PASS,,31/05/2023 15:35,,8065488b-7e4f-4343-b156-fb0c980e83f5,7,"In mandatory  text box ""Adresa de email"" insert the email address",popescu.gigi@yahoo.com,"The field is correctly marked as mandatory, with an *, and the value is successfully filled in and displayed.",PASS,,
bee4ecfb-f436-4ecb-86d0-a51abc341f7c,Lansare serviciu Hotel anvelope,NM-7,Verify if a new user can create a new account,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:46,PASS,,31/05/2023 15:35,,1428ecbb-e4f7-4f3c-88f2-2329bb2315ea,8,"Enter a valid value into the mandatory textbox ""Parola""",1a2b3c4d,"The field is correctly marked as mandatory, with an *, and the value is successfully filled in and displayed.",PASS,,
bee4ecfb-f436-4ecb-86d0-a51abc341f7c,Lansare serviciu Hotel anvelope,NM-7,Verify if a new user can create a new account,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:46,PASS,,31/05/2023 15:35,,6d15b351-5f2b-4a4f-b8e4-9686c50bc6fb,9,"Enter a valid value into the mandatory textbox  ""Confirmare parola""",1a2b3c4d,"The field is correctly marked as mandatory, with an *, and the value is successfully filled in and displayed with dots.",PASS,,
bee4ecfb-f436-4ecb-86d0-a51abc341f7c,Lansare serviciu Hotel anvelope,NM-7,Verify if a new user can create a new account,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:46,PASS,,31/05/2023 15:35,,70d58ce0-3e58-4d7a-a561-f2df0eddc6e8,10,"Tick the mandatory checkbox ""Am citit si sunt de acord cu Termenii si conditiile""",,The checkbox is ticked.,PASS,,
bee4ecfb-f436-4ecb-86d0-a51abc341f7c,Lansare serviciu Hotel anvelope,NM-7,Verify if a new user can create a new account,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:46,PASS,,31/05/2023 15:35,,e71205b9-8101-4a4b-973e-91d38f487c0c,11,"Click on ""Continua"" button",,The new account is correctly created and the user is redirected to his profile account page.,PASS,,
c7c40528-5d3f-4814-9367-3c3bcd82b1ca,Lansare serviciu Hotel anvelope,NM-8,Verify if correct validation messages are displayed when using invalid data for the fields,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:50,FAIL,,31/05/2023 15:35,,d73e6d97-467b-4277-b721-6f1bc05f53d0,1,"Enter an invalid value in the field ""Nume""",a1,the numeric character insertion should be refused and a message should appear,FAIL,,
c7c40528-5d3f-4814-9367-3c3bcd82b1ca,Lansare serviciu Hotel anvelope,NM-8,Verify if correct validation messages are displayed when using invalid data for the fields,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:50,FAIL,,31/05/2023 15:35,,0f117348-7355-41f1-9aee-5314223ad3f2,2,"Enter an invalid value in the field ""Prenume""",a1,the numeric character insertion should be refused and a message should appear,FAIL,,
c7c40528-5d3f-4814-9367-3c3bcd82b1ca,Lansare serviciu Hotel anvelope,NM-8,Verify if correct validation messages are displayed when using invalid data for the fields,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:50,FAIL,,31/05/2023 15:35,,ebdbf9ba-414e-43c4-9a5a-f9b5a2a5c4a2,3,"Enter an invalid value in the field ""Telefon""",0755aaa333,the letter character insertion should be refused and a message should appear,PASS,,
c7c40528-5d3f-4814-9367-3c3bcd82b1ca,Lansare serviciu Hotel anvelope,NM-8,Verify if correct validation messages are displayed when using invalid data for the fields,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:50,FAIL,,31/05/2023 15:35,,0c4ba1d1-32fc-4ee8-adf4-fa00dbf75db3,4,"Enter an invalid value in the field ""Telefon""",1,The phone number should be refused as non valid format and a message should be displayed,FAIL,,
c7c40528-5d3f-4814-9367-3c3bcd82b1ca,Lansare serviciu Hotel anvelope,NM-8,Verify if correct validation messages are displayed when using invalid data for the fields,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:50,FAIL,,31/05/2023 15:35,,32902723-58bb-4153-bc13-6e0cf9688fbd,5,"Enter an invalid value in the field ""Adresa de email""",a1a1gmail.com,"the email address should be refused and a message regarding missing ""@"" should appear",PASS,,
71ad06fb-317b-4e83-b783-fcdc1268f629,Lansare serviciu Hotel anvelope,NM-11,Verify if a user can login with the credentials,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:46,PASS,,31/05/2023 15:35,,9641be35-774d-4dd3-91a0-92b7b8829908,1,"On the home page of the application user choose the popup button ''human"" on the top right page",,"""INTRA IN CONT"" button will appear and it is active",PASS,,
71ad06fb-317b-4e83-b783-fcdc1268f629,Lansare serviciu Hotel anvelope,NM-11,Verify if a user can login with the credentials,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:46,PASS,,31/05/2023 15:35,,7e7f2a87-12a2-4e3a-bf38-4b7b6df0176b,2,"Click on ""INTRA IN CONT"" button",,Login page will appear,PASS,,
71ad06fb-317b-4e83-b783-fcdc1268f629,Lansare serviciu Hotel anvelope,NM-11,Verify if a user can login with the credentials,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:46,PASS,,31/05/2023 15:35,,f8eaf6ad-7fbf-4c80-ad17-599e760eaa7a,3,"Insert the email address in the field ""Introdu adresa de email"" and click on ""CONTINUA"" button",a1a1@gmail.com,Email address is accepted and password field will appear,PASS,,
71ad06fb-317b-4e83-b783-fcdc1268f629,Lansare serviciu Hotel anvelope,NM-11,Verify if a user can login with the credentials,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:46,PASS,,31/05/2023 15:35,,992953a7-7735-4433-b10a-b545b9acda5b,4,"Insert the password in the field ""Introdu parola contului tau Autobon"" anf click on ""CONTINUA"" button",12345,Login successfully and personal acount page will appear,PASS,,
e9146ef2-16e3-4205-a37a-f0cf645f6952,Lansare serviciu Hotel anvelope,NM-15,"Verify the functionality of ""Forgot Password"" option",Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:50,PASS,,31/05/2023 15:37,,29f9913b-ce46-4278-8f40-149b9c8bc090,1,"Click on the ""human"" button",,"""INTRA IN CONT"" popup menu  appear",PASS,,
e9146ef2-16e3-4205-a37a-f0cf645f6952,Lansare serviciu Hotel anvelope,NM-15,"Verify the functionality of ""Forgot Password"" option",Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:50,PASS,,31/05/2023 15:37,,3962ccc3-4d56-4c73-9d3e-ec0725e05b30,2,"Click on ""Ai uitat parola?"" option","""Ai uitat parola?""",A new page that  request the email address appear,PASS,,
e9146ef2-16e3-4205-a37a-f0cf645f6952,Lansare serviciu Hotel anvelope,NM-15,"Verify the functionality of ""Forgot Password"" option",Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:50,PASS,,31/05/2023 15:37,,a989e5a2-b2ed-4b90-bd24-f8ee6d1a7957,3,"In the field ""Introdu adresa de email"" insert the email address used when account was created",popescu.gigi@yahoo.com,An email containing a link for password change will be sent,PASS,,
0f9f9984-7b94-4d32-8f84-1ff9d513c01a,Lansare serviciu Hotel anvelope,NM-16,Verify if a message appear in case of wrong email address for password recovery,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:39,PASS,,31/05/2023 15:37,,ef4d43b8-5daf-4c6d-8936-e09e2f78cde1,1,"Click on ""Ai uitat parola?"" option","""Ai uitat parola?""",A new page that request the email address appear,PASS,,
0f9f9984-7b94-4d32-8f84-1ff9d513c01a,Lansare serviciu Hotel anvelope,NM-16,Verify if a message appear in case of wrong email address for password recovery,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:39,PASS,,31/05/2023 15:37,,750fb1e7-15df-46dc-a28f-9f43d089dd59,2,A wrong format for email address is inserted,gigi123@gmail,"The following message appear ""Domeniul email-ului nu contine nume si extensie""",PASS,,
0f9f9984-7b94-4d32-8f84-1ff9d513c01a,Lansare serviciu Hotel anvelope,NM-16,Verify if a message appear in case of wrong email address for password recovery,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:39,PASS,,31/05/2023 15:37,,31e11f51-35b9-4eb3-842b-da32a189cfb6,3,A different email address  that was not used when user account was created is inserted,gigi1234abc@gmail.com,"The following meassage appear ""Adresa de email, gigi1234abc@gmail.com, introdusă de tine nu este asociată niciunui cont Autobon. Hai să creăm un cont nou!""",PASS,,
c62f17fa-1264-4fac-94d5-f35e96088057,Lansare serviciu Hotel anvelope,NM-18,"Verify If using invalid login credentials, the user receive an appropriate error message indicating the clear reason for the login failure.",Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,03/06/2023 16:25,PASS,,03/06/2023 16:25,,c288be57-07c5-4d29-a845-91714bf14290,1,"A wrong email address is inserted and the correct password, then click on ""INTRA IN CONT"" button",gig.popescu@gmail.com 1a2b3c4d,"Following message appear ""Numele de utilizator sau parola sunt incorecte""",PASS,,
c62f17fa-1264-4fac-94d5-f35e96088057,Lansare serviciu Hotel anvelope,NM-18,"Verify If using invalid login credentials, the user receive an appropriate error message indicating the clear reason for the login failure.",Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,03/06/2023 16:25,PASS,,03/06/2023 16:25,,ae80d16b-2a43-44a9-9970-2367a1a28bc7,2,"The correct email address is inserted and a wrong password, then click on ""INTRA IN CONT"" button",gigi.popescu@gmail.com 1a2b3c4,"Following message appear ""Numele de utilizator sau parola sunt incorecte""",PASS,,
c62f17fa-1264-4fac-94d5-f35e96088057,Lansare serviciu Hotel anvelope,NM-18,"Verify If using invalid login credentials, the user receive an appropriate error message indicating the clear reason for the login failure.",Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,03/06/2023 16:25,PASS,,03/06/2023 16:25,,a1572ae1-13f7-42c6-8c8e-1c8b36d9cf8b,3,"A wrong email address is inserted and a wrong password, then click on ""INTRA IN CONT"" button",gig.popescu@gmail.com 1a2b3c4,"Following message appear ""Numele de utilizator sau parola sunt incorecte""",PASS,,
395a637c-7a10-4a04-ae38-73b79ed6c730,Lansare serviciu Hotel anvelope,NM-22,"Verify if the user is inactive for a certain period, will be  automatically logged out and redirected to the login page.",Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:40,FAIL,,31/05/2023 15:37,,abdfeed1-4070-41c2-b7ad-1c9eab6e3636,1,Log on the personal page,email address and password,The personal account page is open and active,PASS,,
395a637c-7a10-4a04-ae38-73b79ed6c730,Lansare serviciu Hotel anvelope,NM-22,"Verify if the user is inactive for a certain period, will be  automatically logged out and redirected to the login page.",Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,31/05/2023 15:40,FAIL,,31/05/2023 15:37,,b0fa0a39-19b8-460d-96a2-9eb72827587f,2,The page is minimized and not used for 20 min,,After 20 min the personal page account is still open and active,FAIL,,
2c5bcb63-b4f9-49f8-8526-5a895364614a,Lansare serviciu Hotel anvelope,NM-25,Verify if the user is able to see at account creation the characters inserted on password fields,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,12/06/2023 18:41,FAIL,,12/06/2023 18:40,,1bfff568-cdc4-4214-bc66-da92d5017196,1,"Enter a valid name in the field ""Nume""",Popescu,The value is successfully filled in and displayed.,PASS,,
2c5bcb63-b4f9-49f8-8526-5a895364614a,Lansare serviciu Hotel anvelope,NM-25,Verify if the user is able to see at account creation the characters inserted on password fields,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,12/06/2023 18:41,FAIL,,12/06/2023 18:40,,18294081-2922-4797-be5c-653daa450688,2,"Enter a valid name in the field ""Prenume""",Gigi,The value is successfully filled in and displayed.,PASS,,
2c5bcb63-b4f9-49f8-8526-5a895364614a,Lansare serviciu Hotel anvelope,NM-25,Verify if the user is able to see at account creation the characters inserted on password fields,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,12/06/2023 18:41,FAIL,,12/06/2023 18:40,,e0839841-c8c4-431b-a46d-10d556cfd206,3,"Enter the phone number in the field ""Telefon""",744666888,The value is successfully filled in and displayed.,PASS,,
2c5bcb63-b4f9-49f8-8526-5a895364614a,Lansare serviciu Hotel anvelope,NM-25,Verify if the user is able to see at account creation the characters inserted on password fields,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,12/06/2023 18:41,FAIL,,12/06/2023 18:40,,07635331-5804-4d9c-89f6-b68b6d5ac18c,4,"Enter the email address in the field ""Adresa de email""",popescu.gigi@yahoo.com,The value is successfully filled in and displayed.,PASS,,
2c5bcb63-b4f9-49f8-8526-5a895364614a,Lansare serviciu Hotel anvelope,NM-25,Verify if the user is able to see at account creation the characters inserted on password fields,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,12/06/2023 18:41,FAIL,,12/06/2023 18:40,,73ef89a2-67e3-41b9-9706-b3b6c30385f4,5,"Enter the password in the field ""Parola""",1a2b3c4d,Bullets appear in the field after each charcater inserted,PASS,,
2c5bcb63-b4f9-49f8-8526-5a895364614a,Lansare serviciu Hotel anvelope,NM-25,Verify if the user is able to see at account creation the characters inserted on password fields,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,12/06/2023 18:41,FAIL,,12/06/2023 18:40,,fd75eaa9-00fe-4a5d-87dc-f1cfb7c111c7,6,"Try to check if the password inserted in ""Parola "" field is correct",1a2b3c4f,There is no option to see what is behind bullets,FAIL,,
2c5bcb63-b4f9-49f8-8526-5a895364614a,Lansare serviciu Hotel anvelope,NM-25,Verify if the user is able to see at account creation the characters inserted on password fields,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,12/06/2023 18:41,FAIL,,12/06/2023 18:40,,c719e53e-a131-4a76-86c7-fc485d478ff8,7,"Enter the password in the field ""Confirmare parola""",1a2b3c4d,Bullets appear in the field after each charcater inserted,PASS,,
2c5bcb63-b4f9-49f8-8526-5a895364614a,Lansare serviciu Hotel anvelope,NM-25,Verify if the user is able to see at account creation the characters inserted on password fields,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,12/06/2023 18:41,FAIL,,12/06/2023 18:40,,d9ef63b1-95a4-449d-9817-56ff4e8bc895,8,"Try to check if the password inserted in ""Confirmare parola"" field is correct",1a2b3c4f,There is no option to see what is behind bullets,FAIL,,
1cb93717-816f-46f9-afd1-382a8cfb22df,Lansare serviciu Hotel anvelope,NM-27,Verify if there is a logoff option on the user account page,Noaptes Mihai,Lansare serviciu Hotel anvelope,Lowest,ITF Classes,12/06/2023 18:44,FAIL,,12/06/2023 18:43,,12dc1154-3cad-442d-946b-c21f83823594,1,Log on the personal page,email address and password,The personal account page is open and active,PASS,,
1cb93717-816f-46f9-afd1-382a8cfb22df,Lansare serviciu Hotel anvelope,NM-27,Verify if there is a logoff option on the user account page,Noaptes Mihai,Lansare serviciu Hotel anvelope,Lowest,ITF Classes,12/06/2023 18:44,FAIL,,12/06/2023 18:43,,68ef84be-764e-4b56-9ef6-2f2be9562eaf,2,"Click on ""LOGOUT"" button located on the bottom of the menu from the left side of the page",LOGOUT option,"The menu is inactive, logout not possible",FAIL,,
1cb93717-816f-46f9-afd1-382a8cfb22df,Lansare serviciu Hotel anvelope,NM-27,Verify if there is a logoff option on the user account page,Noaptes Mihai,Lansare serviciu Hotel anvelope,Lowest,ITF Classes,12/06/2023 18:44,FAIL,,12/06/2023 18:43,,ef492688-ba43-4ea7-822e-d4c10f0c86aa,3,"Scroll down to the bottom of ""INFORMATII GERNERALE"" submenu and click on  ""LOGOUT"" button",LOGOUT button,Button is active and user logout from his account,PASS,,
a3b4edc0-3412-4370-a30d-598aacdca347,Lansare serviciu Hotel anvelope,NM-29,Verify if a user can modify the account data,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,22/06/2023 16:09,PASS,,22/06/2023 16:08,,982bb751-053d-49c4-8b71-0a9dc2c98ed6,1,"In the left side menu on the personal account page choose ""MODIFICARE DATE CONT""","""MODIFICARE DATE CONT""","""MODIFICARE DATE CONT"" page will open",PASS,,
a3b4edc0-3412-4370-a30d-598aacdca347,Lansare serviciu Hotel anvelope,NM-29,Verify if a user can modify the account data,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,22/06/2023 16:09,PASS,,22/06/2023 16:08,,2ad6107f-e0a7-4830-a36d-b13590094c1a,2,"In the field ""Nume"" insert the new name",Mihai,Field is active and the new name is inserted,PASS,,
a3b4edc0-3412-4370-a30d-598aacdca347,Lansare serviciu Hotel anvelope,NM-29,Verify if a user can modify the account data,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,22/06/2023 16:09,PASS,,22/06/2023 16:08,,05c02f18-55e5-4afd-9b2a-8b19399a27bb,3,"In the field ""Prenume"" insert the new last name",Vasilescu,Field is active and the new last name is inserted,PASS,,
a3b4edc0-3412-4370-a30d-598aacdca347,Lansare serviciu Hotel anvelope,NM-29,Verify if a user can modify the account data,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,22/06/2023 16:09,PASS,,22/06/2023 16:08,,de847225-0aa2-4555-8fb1-635a12a86909,4,"In the field ""Telefon"" insert the new telephon number",722333777,Field is active and the new telephone number is inserted,PASS,,
a3b4edc0-3412-4370-a30d-598aacdca347,Lansare serviciu Hotel anvelope,NM-29,Verify if a user can modify the account data,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,22/06/2023 16:09,PASS,,22/06/2023 16:08,,41b9180d-8d33-4cec-b6b1-699e3bd0c0c1,5,"Click on red button ""SALVEAZA""","""SALVEAZA""",New inserted data are accepted and a message will be displayed,PASS,,
507192b3-7d7a-447f-b479-87d10d5a639e,Lansare serviciu Hotel anvelope,NM-30,Verify if the user can change the account password,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,22/06/2023 16:10,PASS,,22/06/2023 16:08,,4baf9dc3-3b58-40de-9327-7e50052a719f,1,"In the left side menu on the personal account page choose ""MODIFICARE PAROLA""","""MODIFICARE PAROLA""","""MODIFICARE PAROLA"" page will open",PASS,,
507192b3-7d7a-447f-b479-87d10d5a639e,Lansare serviciu Hotel anvelope,NM-30,Verify if the user can change the account password,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,22/06/2023 16:10,PASS,,22/06/2023 16:08,,5fe8fef1-5053-485a-ac29-eb6e64099d06,2,"In the field ""Parola noua"" insert the new password",1234abcd,Field is active and the new password is inserted,PASS,,
507192b3-7d7a-447f-b479-87d10d5a639e,Lansare serviciu Hotel anvelope,NM-30,Verify if the user can change the account password,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,22/06/2023 16:10,PASS,,22/06/2023 16:08,,91cf4210-cd59-4071-abbf-c9d244b3f101,3,"In the field ""Confirmare parola"" insert the new password",1234abcd,Field is active and the new password is inserted,PASS,,
507192b3-7d7a-447f-b479-87d10d5a639e,Lansare serviciu Hotel anvelope,NM-30,Verify if the user can change the account password,Noaptes Mihai,Lansare serviciu Hotel anvelope,Medium,ITF Classes,22/06/2023 16:10,PASS,,22/06/2023 16:08,,f3166fb6-7f87-4a9f-aa9e-c8e946aca354,4,"Click on red button ""SALVEAZA""","""SALVEAZA""",New inserted password is accepted and a message will be displayed,PASS,,
loading Cycle_summary.csv…]()

* Bugs have been created based on the failed tests. The complete bug reports can be found here: [created_bugs.pdf]()
    *  enter here bug titles


## 1.7 Test Completion

* Exit criteria was evaluated and passed
* The traceability matrix was generated and can be found here: [Traceability_Matrix.xlsx](https://github.com/mn8375/Final_project_Manual_Testing/files/12728125/Traceability_Matrix.xlsx)

* Test execution chart was generated, the final report shows.... -> describe the final report

-> enter here test execution report/chart

# 2 SQL section
