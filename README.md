<h1>Techirghiol City Hall Website Testing Project</h1>

The goal of the final project for the “IT Factory Manual Testing Course” is to use all the knowledge acquired during the course sessions, and to be able to apply it practically.

Tested parts of the website: https://www.primariatechirghiol.ro

Tools used: Jira and Zephyr Squad.

<h2>Functional specifications:</h2>

The stories below were created in Jira and describe some functional specifications of the Techirghiol City Hall website, for which the final project is being carried out:

![stor](https://github.com/user-attachments/assets/28a7ac5f-c06f-4e05-b6a0-c1dcb9b9715b)

Here you can find the release that was created for this project:

![relea](https://github.com/user-attachments/assets/d31638d1-6382-4b3f-a15f-3be91e0a0a25)

<h2>Testing Process</h2>

The testing process was operated based on the standard testing process, as described below.

<h3>1.1 Testing Planning</h3>

The Test Plan is designed to describe all the details of the testing.

The plan identifies the elements to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for the testing, the resources and schedule required to complete the testing, and the risks associated with the plan. The test plan that was created for this project can be found here:

*****

<h4>1.1.1. Assigned people and roles assigned to the project</h4>

<ul>
<li>Csipas Valeriu - Project manager</li>
<li>Moga Constantin - Product owner</li>
<li>Buga Ovidiu - Software developer</li>
<li>POKA NORBERT - Team Lead</li>
<li>Sabou Iulia - QA (Quality Assurance) 1</li>
<li>Talpoș Armand - QA 2</li>
<li>Oprișan Mugurel - QA 3</li>
</ul>

<h4>1.1.2 Defined Entry Criteria</h4>
The entry criteria for testing are as follows:
<ul>
<li>project risks have been identified and moderated;</li>
<li>roles and responsibilities have been assigned and agreed upon;</li>
<li>deadlines have been set;</li>
<li>scope has been set and communicated to team members;</li>
<li>testing objectives have been defined and communicated to team members.</li>
</ul>

<h4>1.1.3 Defined Exit Criteria</h4>
And the exit criteria for testing are as follows:
<ul>
<li>product risks have been found and mitigated;</li>
<li>no critical defects have remained open;</li>
<li>deadlines have been met;</li>
<li>at least 85% of all tests are passed;</li>
<li>test documentation is completed and communicated to stakeholders (TCR is generated);</li>
<li>all defects are documented and communicated to stakeholders.</li>
</ul>

<h4>1.1.4 Test Scope</h4>

<h5>Tests in scope:</h5>
<ul>
<li>Functional, performance, use case requirements testing;</li>
<li>Quality requirements and fit metrics primariatechirghiol.ro.</li>
</ul>

<h5>Tests out of scope:</h5>
<ul>
<li>Functional requirements testing for systems outside primariatechirghiol.ro;</li>
<li>Security testing;</li>
<li>Disaster recovery plan testing and business continuity;</li>
<li>Automated testing.</li>
</ul>

<h4>1.1.5 Detected risks</h4>

<h5>Product risks:</h5>
The risk associated with the final product is the one immediately mentioned:
<ul>
<li>potentially crashes the web page if it is loaded with too much data.</li>
</ul>

<h5>Project risks:</h5>
While the risks associated with the project are the following:
<ul>
<li>QA team member 2 risks getting infected with the COVID-19 virus due to the fact that where he is staying there are people sick with COVID-19, and he does not have the possibility to spend the nights in another home or room, which may increase the workload of the other team members;</li>
<li>QA team member 3 does not have enough experience in manual testing to complete it alone what it has to do.</li>
</ul>

<h4>1.1.6 Evaluation of entry criteria</h4>

The entry criteria defined in the Test Planning phase have been met, and the testing process can continue.

<h3>1.2 Monitoring and controlling testing</h3>
The testing process was continuously monitored, from start to finish. The Test status report was generated to effectively compare the current progress with the expected one. If deviations from the plan took hold of the entire development, then control measures were taken. The same happened if there was a risk of not meeting the objectives on time. The role of this stage is to increase quality and efficiency.

![execu list](https://github.com/user-attachments/assets/13888569-de10-4b62-a188-2a983701f974)

<h3>1.3 Testing analysis</h3>

The testing process was executed based on the application requirements.
The following test conditions were built:

![testcond](https://github.com/user-attachments/assets/5c754c8c-0ecd-400d-ba5f-41b75b670dcc)

<h3>1.4 Testing design</h3>

The functional test cases were created in Zephyr Squad based on the specification analysis. The test cases can be accessed here:

[TestCases](https://github.com/PokaNorbert/Primariatechirghiol.ro-Jira-Manual_Testing/tree/main/TestCases)

<h3>1.5 Testing Implementation</h3>

The following elements are required to be prepared before starting the testing execution phase:
<ul>
<li>The test environment is prepared in all respects;</li>
<li>The test data is available and accurate;</li>
<li>The most important test cases are grouped;</li>
<li>Permissions are available;</li>
<li>The smoke test has been passed.</li>

</ul>

<h3>1.6. Testing Execution</h3>

The test cases are executed on the created test Cycle summary: ”Primariatechirghiol_versiunea_1.0_limba_română”.

Defects/bugs have been created based on the failed tests. The full bug reports can be found here:

[Bugs](https://github.com/PokaNorbert/Primariatechirghiol.ro-Jira-Manual_Testing/tree/main/Bugs)

The following is a summary of the defects/bugs that were found:

![Medium-bug](https://github.com/user-attachments/assets/d7774193-d72e-4b19-8cfc-05a88d61d5c1)

Full regression testing is required on the affected areas after the bugs are fixed, and then each functionality that previously failed will need to be retested.

<h3>1.7 Test Completion</h3>
Since the exit criteria have been met, the Testing Team suggests this feature to "Go Live".

The traceability matrix has been generated, and can be found here:

![stor-traceabil](https://github.com/user-attachments/assets/e3b2c98f-a40c-4e9f-b3b5-311741ee1194)

The link between stories, tests and bugs/defects is properly reflected with the Traceability Matrix: 
<ul>
<li>The matrix above can show us a number of 14 stories (10 stories are visible in the attached screenshot);</li>
<li>The high number of defects/bugs displayed is caused by the fact that many defects are associated with several tests, not just one (thus, several links harmful to the user experience on the website were created);</li>
<li>The story called ”NPT-167” is linked to 5 test conditions: NPT-157-159-161-163-165;</li>
<li>Based on the same links: ”Story-Test condition”, ”NPT-130” is also linked to 5 test conditions: NPT-138-139-140-143-144, and ”NPT-127” only by ”NPT-128”;</li>
<li>There are 11 test conditions in total (most cover more than one story);</li>
<li>15 bugs/defects were identified (they are distributed across 11 stories).</li>
</ul>

The test execution diagram was generated, and can be found below:

![t exec-2](https://github.com/user-attachments/assets/ef06848e-ec0e-444b-b85c-36d12e0281e4)
![textexecut2-=](https://github.com/user-attachments/assets/646f9fac-46af-4818-8770-41ccd98a0be9)

The final report shows that 10 tests failed out of a total of 11.

A total of 15 defects/bugs were found, none of which are high priority, and 6 are medium priority.

<h1>Testing Consequences</h1>

The consequences of the testing performed are the following:
<ul>
<li>The total number of tests created is: 11, all of which were executed;</li>
<li>The coverage percentage of tests in the scope is: 100%;</li>
<li>For future projects, an even higher level of human attention is needed, and the speed of work is increased;
<li>Most of the defects have a medium level of severity. All defects affect the interaction that the end user has with the city hall website. Therefore, there is a probability that the end user will lose valuable time sitting on the website.</li>
</ul>
