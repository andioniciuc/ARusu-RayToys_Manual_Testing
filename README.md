# ARusu-RayToys
ARusu-Testare-Manuala-RayToys



# Proiect-Testare-Manuala



### test design



<h2>test plan </h2>



| Role  | Name |
|---|---|
| Product Owner | Anca Pop |
| Software Developer | Diana Popescu |
| Software Tester | Andreea Ioana Rusu |


| Date  | Description | Author  | Comments |
|---|---|---|---|
| 28.04.2023 | V1.0 | Andreea Ioana Rusu  |   |
| 05.05.2023 | V1.1 | Andreea Ioana Rusu | More details added on Test Implementation |
| 05.06.2023 | V1.2 | Andreea Ioana Rusu  | Test completion report added |


    1. Introduction
        1.1. Project objective
        1.2. Functionalities in scope
        1.3. Functionalities and tests out of scope
    2. Test process
        2.1. Test planning
        2.2. Test analysis
        2.3. Test design
        2.4. Test implementation
        2.5. Test execution
        2.6. Test closure
        2.7. Test monitoring and control
    3. Test deliverables
        3.1. Test plan
        3.2. Test conditions
        3.3. Test cases
        3.4. Daily test summary reports
        3.5. Traceability matrix
        3.6. Test case results
        3.7. Bugs report
        3.8. Test completion report


### 1. Introduction
This test plan document describes the strategies, process, workflows and methodologies used to plan, organize, execute and manage testing process for RayToys.

#### 1.1. Project Objective
The scope of the final project for ITF Manual Testing Course is to use all gained knowledge through the course and apply them in practice, using a live application. 

Application under test: https://raytoys.ro/.

Tools used: JIRA, Zephyr Squad.


#### 1.2. Functionalities in scope
- Features that need to be tested: functional testing and GUI testing. 
- The below user story was created in Jira and describes functional specifications of the website, for which the final project is performed upon.

*Screenshots din Jira cu user story-ul 

#### 1.3.Functionalities and tests out of scope
- Non-functional testing like stress, performance is beyond scope of this project. 
- No QA support for mobile application developed. Only web application will be tested. 
- Automation testing is beyond scope.


    
    
    ### 2. Test process
#### 2.1. Test planning

The Test Plan is designed to describe all details of testing for the Ray Toys website.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.

**Roles assigned to the project, persons allocated and responsibilities**
| Role  | Name |
|---|---|
| Product Owner | Anca Pop |
| Software Developer | Diana Popescu |
| Software Tester | Andreea Rusu |



**Entry criteria:**
- Business specifications are defined 
- Roles needed for the project are allocated 
- Initial project risks were detected and mitigated 

**Exit criteria:**
- All test cases have been executed 
- The unresolved bugs/defects have low priority 
- No detected major risks remained un-mitigated 
- All resolved bugs have been retested and approved by the testers
- Regression testing have been ran and no major bugs detected  
- All business requirements have been covered by test cases 
- All business requirements have been met 

**Risks:**
- Project risks: lack of experience of QA team, lack of tools, short deadline for Jira and Zephyr Squad, unavailability of RayToys demo environment
- Product risks: Validation constraints on the fields might be too restrictive to the end user 

#### 2.2 Test analysis 
- Analyze the business requirements to make sure that we have all the details to create the test conditions 
- Write test conditions that will be tested in out test process 

#### 2.3 Test design
- Functional test cases will be created in Jira 



#### 2.4 Test implementation
Verify if the following elements are ready before test execution:
* Test environment is up and running: https://raytoys.ro 
+ Cycle summary was created 
- Test cases were added to the cycle summary 


#### 2.5 Test execution
- Test cases are executed on the created cycle summary 
- Bugs have been created based on the failed test cases. The complete bug reports can be found here: *se poate pune link catre un fisier cu bug reports in Github 
- API tests are executed based on the checklist (requirements)
- Full regression pack is executed after changes made to the application 
#### 2.6 Test closure
- All exit criteria were met as mentioned in the Test Planning section (2.1)
- The traceability matrix was generated to demonstrate the business requirements coverage
- Test execution chart was generated, the final report shows a number of 7 failed test cases of a total 64

#### 2.7 Test monitoring and control
Various periodic reports were generated to reflect the current status of the testing process, in case of major problems control measures could be taken.

![Test Monitoring Progress](https://github.com/andioniciuc/ARusu-RayToys_Manual_Testing/blob/main/DailyTestExecutionProgress.png)


#### 3. Test deliverables

#### 3.1. Test plan
The plan identifies the items to be tested, the features to be tested, the type of testing to be performed, the roles and responsibilities for the testing process, the resources and schedule required to complete testing and the risks associated with the plan. 

#### 3.2. Test conditions
The following test conditions were created: 
![Test conditions](https://github.com/andioniciuc/ARusu-RayToys_Manual_Testing/blob/main/Tests.pdf)

​
#### 3.3. Test cases
*The following test cases were created: 
![Test Cases](https://github.com/andioniciuc/ARusu-RayToys_Manual_Testing/blob/main/TestCases(Jira).pdf)


#### 3.4. Daily test summary report 
*The daily report was generated: 
![Test Summary](https://github.com/andioniciuc/ARusu-RayToys_Manual_Testing/blob/main/Test_Summary.png)


#### 3.5. Traceability matrix
*The traceability matrix was generated: 
![Traceability Matrix](https://github.com/andioniciuc/ARusu-RayToys_Manual_Testing/blob/main/TraceabilityReport(Direct-Only)(Jira).pdf)

Traceability report was also exported in pdf format: ![Traceability Report](https://github.com/andioniciuc/ARusu-RayToys_Manual_Testing/blob/main/TraceabilityReport(Recursive)(Jira).pdf)

To show the time line a Gantt Chart was done: ![Gantt Chart (Jira)](https://github.com/andioniciuc/ARusu-RayToys_Manual_Testing/blob/main/GanttChart(Jira).pdf)

#### 3.6. Test case results
*The test cases results:
![Test Cases Results](https://github.com/andioniciuc/ARusu-RayToys_Manual_Testing/blob/main/TestCases_w_Results.pdf)

#### 3.7. Bugs report
*The bug report exported from Jira:
![Bug Report](https://github.com/andioniciuc/ARusu-RayToys_Manual_Testing/blob/main/Bug_Report.pdf)

#### 3.8. Test completion report
*The test completion report generated from Jira:
![Test Completion Report](https://github.com/andioniciuc/ARusu-RayToys_Manual_Testing/blob/main/ZephyrTestSteps+Executions+Results(Jira).pdf)




#### 3.9. Schedule
A test schedule includes the testing steps or tasks, the target start and end date and responsibilities. 


| Task  | Date | Name/Team member  | 
|---|---|---|
|Setup Project in Jira|28.04. 2023| Andreea Ioana Rusu |
| Run functional test cases | 28.04. 2023 | Andreea Ioana Rusu  |   
| Run GUI test cases | 02.05. 2023 | Andreea Ioana Rusu  | 
| Summary | 05.06.2023 | Andreea Ioana Rusu  | 

# General conclusions

Putting the acquired knowledge into practice; testing the RayToys website, through the JIRA application and the Zephyr plugin.

Total number of Story: 11

Total number of Taste Cases / Total number of Run Test Cases: 64

Bugs: 7 (2 high and 5 medium severity), degree of affecting the user: Low

The application was tested on the selected segment, which has optimal functionality.

No major defects and impact on the user.

The segment can be launched in real environment by the client.


