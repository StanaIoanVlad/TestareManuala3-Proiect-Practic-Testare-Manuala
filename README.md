The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application.

Application under test: https://tryhackme.com/

Tool used: JIRA, Zephyr Squad.

<h2>Functional specifications:</h2>
In Jira was created 10 stories describing certain specifications,below you can find story image from Jira, describing the functional specifications of creating user account.
![1xc2c12123](https://github.com/StanaIoanVlad/TestareManuala3-Proiect-Practic-Testare-Manuala/assets/130207529/360290ff-f63e-482e-a1ec-cb6477d94bb0)
Link for other 9 story:
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
* exploratory regression testing must be performed on the Add product to cart module

#### 1.1.4 Test scope

* __Tests in scope:__ All the feature of Dependents module which were defined in software requirement specs need to be tested: functional testing, GUI testing and API testing
* __Tests not in scope:__ performance testing, integrations of the dependents module with other modules, compatibility testing with multiple browsers

#### 1.1.5 Risks detected

* Project risks: lack of experience of the QA team, short deadline of Zephyr Squad trial, unavailability of test environment
* Product risks: validation constraints on the fields might be too restrictive to the end-user

#### 1.1.6 Evaluating entry criteria

The entry criterias defined in the Test Planning phase have been achieved and the test process can continue.

## 1.2 Test Monitoring and Control

Various periodic reports were generated to reflect the current status of the testing process, in case of major problems control measures could be taken. The following status report was generated after 100% of the test cases were executed, on 23th of March.

The following report was generated using Test Metrics from Zephyr
![1dsac1](https://github.com/StanaIoanVlad/TestareManuala3-Proiect-Practic-Testare-Manuala/assets/130207529/577e3360-4e3b-415e-91e2-0baa64ce1f63)





## 1.3 Test Analysis

The testing process will be executed based on the above requirements for the Create a user account. The following test conditions were found:
  * Any new user who visit the website can create an account.
  * User is able to create check password policy when making account
  * Registred user can reset its password if forgoten.

## 1.4 Test Design

Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases are boundary value analysis, equivalence partitioning and use case testing.
**Test Cases:**
![1c21x](https://github.com/StanaIoanVlad/TestareManuala3-Proiect-Practic-Testare-Manuala/assets/130207529/f281c0fb-9b28-45e9-adb4-c8c55f8b6ae0)


## 1.5 Test Implementation

The following elements are needed to be ready before the test execution phase begins:

* Testing environment is up and running: https://tryhackme.com/
* Access to the testing environment is given: Username : Admin | Password : admin123
* Cycle summary was created
* Test cases were added to the cycle summary

## 1.6 Test Execution

*Test cases are executed on the created test Cycle summary:
![c1231d](https://github.com/StanaIoanVlad/TestareManuala3-Proiect-Practic-Testare-Manuala/assets/130207529/c19bd5fe-83ee-471c-ae8c-25835afe2555)

*Bugs have been created based on the failed tests.
![1x82jssk](https://github.com/StanaIoanVlad/TestareManuala3-Proiect-Practic-Testare-Manuala/assets/130207529/14aca4fb-10e6-44f9-af7d-f8161ca45752)
![12112](https://github.com/StanaIoanVlad/TestareManuala3-Proiect-Practic-Testare-Manuala/assets/130207529/df26e82b-d8a9-4717-9ce7-b81c92c5eab6)

* Full regression testing is needed after the bugs are fixed.

## 1.7 Test Completion

* As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team.
* The traceability matrix was generated and can be found here:
* ![matricea transabilitatii](https://github.com/StanaIoanVlad/TestareManuala3-Proiect-Practic-Testare-Manuala/assets/130207529/5b3ac31f-a648-4614-a56a-8c12e43b4e92)

*Test execution chart was generated, the final report shows that a number 2 tests have failed of a total of 10
* A number of 10 test cases were planned for execution and all of them were executed
* A number of 2 total bugs were found, from which the priority is: 1 is high, 1 are medium

![d1xe12](https://github.com/StanaIoanVlad/TestareManuala3-Proiect-Practic-Testare-Manuala/assets/130207529/41998f1f-95fb-48ab-858b-8e3347f1b077)
