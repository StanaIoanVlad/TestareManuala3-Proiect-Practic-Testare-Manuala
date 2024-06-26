The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application.

Application under test: https://tryhackme.com/

Tool used: JIRA, Zephyr Squad.

<h2>Functional specifications:</h2>
In Jira was created 10 stories describing certain specifications,below you can find story image from Jira, describing the functional specifications of creating user account:

![1xc2c12123](https://github.com/StanaIoanVlad/TestareManuala3-Proiect-Practic-Testare-Manuala/assets/130207529/a53b904d-4d06-43c5-bb64-8f0d6bf790d6)


Link for the other 9 stories:
[Jira.pdf](https://github.com/StanaIoanVlad/TestareManuala3-Proiect-Practic-Testare-Manuala/files/14733665/Jira.pdf)


# 1 Testing Section

## 1.1 Test Planning

The Test Plan is designed to describe all details of testing for creating user account for TryHackMe.com application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.

#### 1.1.1 Roles assigned to the project and persons allocated

* Project manager - Andrei Popescu
* Product owner - Mădălina Ionescu
* Software developer - Gabriela Tomescu
* QA Engineer - Stana Ioan Vlad

#### 1.1.2 Entry criteria defined

* functional specifications are defined
* roles needed for the project are allocated
* initial project risks were detected and mitigated

#### 1.1.3 Exit criteria defined

* number of unresolved bugs is insignificant or they have low priority
* all tests have been executed
* all resolved bugs have been re-tested and approved by the QA team
* deadline was reached
* no detected major risk remained un-mitigated
  

#### 1.1.4 Test scope

* __Tests in scope:__ All the features of the Create User Account which were defined in the software requirement specs need to be tested: functional testing, GUI testing.
* __Tests not in scope:__ compatibility testing with multiple browsers

#### 1.1.5 Risks detected

* Project risks: lack of experience of the QA team, short deadline of Zephyr Squad trial, unavailability of test environment
* Product risks: validation constraints on the fields might be too restrictive to the end-user

#### 1.1.6 Evaluating entry criteria

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

## 1.2 Test Monitoring and Control

Various periodic reports were generated to reflect the current status of the testing process, in case of major problems control measures could be taken. The following status report was generated after 100% of the test cases were executed, on 24th of March.

The following report was generated using Test Metrics from Zephyr
![1dsac1](https://github.com/StanaIoanVlad/TestareManuala3-Proiect-Practic-Testare-Manuala/assets/130207529/577e3360-4e3b-415e-91e2-0baa64ce1f63)





## 1.3 Test Analysis

The testing process will be executed based on the above requirements for the Create a user account. 
The following test conditions were found:
*Verify if user can create account on TryHackMe - functional testing
*Check that the validcredential password will accept the user to logging into the website - positive testing
*Check that the invalid credential password will stop the user from logging into the website - negative testing
*Verify the login button - GUI Testing
*Checking the Graphical User Interface on tryhackme - GUI Testing
*Verify Warn of Weak Password Length - functional testing
*Verify if Password Reset works - functional testing
*Valid Credential Payment Subscription -positive testing
*Verify Subscription zone - functional testing


## 1.4 Test Design

Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases are boundary value analysis, equivalence partitioning and use case testing.
**Test Cases:**
[Test Case.pdf](https://github.com/StanaIoanVlad/TestareManuala3-Proiect-Practic-Testare-Manuala/files/14733772/Test.Case.pdf)



## 1.5 Test Implementation

The following elements are needed to be ready before the test execution phase begins:

* Testing environment is up and running: https://tryhackme.com/
* Access to the testing environment is given: Username : Admin | Password : admin123
* Cycle summary was created
* Test cases were added to the cycle summary

## 1.6 Test Execution

*Test cases are executed on the created test Cycle summary:
![1271hds](https://github.com/StanaIoanVlad/TestareManuala3-Proiect-Practic-Testare-Manuala/assets/130207529/d8177cd0-51fb-473f-a7ff-e1038d43a844)



*Bugs have been created based on the failed tests:
[Bugs.pdf](https://github.com/StanaIoanVlad/TestareManuala3-Proiect-Practic-Testare-Manuala/files/14733781/Bugs.pdf
![1x82jssk](https://github.com/StanaIoanVlad/TestareManuala3-Proiect-Practic-Testare-Manuala/assets/130207529/de761d3b-45b1-45f0-8228-aff925a696a6)



* Full regression testing is needed after the bugs are fixed.

## 1.7 Test Completion

* As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team.
* The traceability matrix was generated and can be found here:
* ![matricea transabilitatii](https://github.com/StanaIoanVlad/TestareManuala3-Proiect-Practic-Testare-Manuala/assets/130207529/5b3ac31f-a648-4614-a56a-8c12e43b4e92)
* Bug SIV-11 Overlayed Text & Image was found at Test Case SIV-10 Checking the Graphical User Interface
* Bug SIV-28 Login Button not visible on the homepage was found at Test Case SIV-8 Verify the login button
* 

## 1.8 Conclusions

During this testing, all 10 planned test cases were tested
for execution.
A total of 2 bugs were discovered from the 10 tests, whose
priorities are: 1 – highest, 1 – moderate.
The defects found were fixed and retested.
Retesting and regression testing will be done within the new version of the application.

![d1xe12](https://github.com/StanaIoanVlad/TestareManuala3-Proiect-Practic-Testare-Manuala/assets/130207529/41998f1f-95fb-48ab-858b-8e3347f1b077)
