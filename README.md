## **Final Project for Manual testing course**


Application: https://www.reddit.com/


Api Documentation: https://www.reddit.com/dev/api/#GET_search

Author: Valentin Jipa

## **Table of Contents**

1. [Introduction](#Introduction)

     1.2. [What is reddit](#what-is-reddit)

     1.3. [Project objective](#project-objective)

     1.4. [Functional specifications](#functional-specifications)

     1.5. [Functinality in scope](#functinality-in-scope)

     1.6. [Functionalities and tests out of scope](#functionalities-and-tests-out-of-scope)

2. [Test Process](#test-process)

    2.1. [Test Planning](#test-Planning)
   
   2.1.1 [Entry criteria](#entry-criteria)
   
      2.1.2 [Exit criteria](#entry-criteria)

      2.1.3 [Risks](#project-risks)

   2.3. [Test Analysis](#project-risks)


## **Introduction**

### What is reddit

Reddit is a social news website and forum where content is socially curated and promoted by site members through voting. The site name is a play on the words "I read it."

### Project objective

The scope of the project for ITF Manual Testing Course is to use all gained knowledge during the course and apply them on a live applicattion. The project consist of a test plan used to describe the strategies, planification and scope for the web application.

Tools: Jira, Zephyr Squad

### Functional specifications: 

The stories attach [here](https://github.com/valentinJipa/ReposteryTest/blob/main/Jira_Stories.pdf) were created in Jira and describe the functionality of the home page and search moduels.

Here is an example of a story created for the search bar trending moduel:
![image](https://github.com/valentinJipa/ReposteryTest/assets/33808653/b76e527d-996f-427d-a937-e5d58aa52965)

### Release

Here can be found the release created for the project
![image](https://github.com/valentinJipa/ReposteryTest/assets/33808653/c0fb0e40-5205-4645-8e76-a187ce3c47e6)

### Functinality in scope

For this version of the application the functionalities in the scope of testing are:

<ul>
  <li>The Home page module - encompasses the elements found on the front page of reddit...</li> 
  <li>Search bar module - refers to the functionality and ui elements coresponding to the search algorithm of reddit...</li>
  <li>Throughtout the testing procces, functionality testing will be performed on 2 different browsers: firefox and chrome </li>  
</ul>

### Functionalities and tests out of scope

<ul>
  <li>All other modules besides home page and search bar will not be tested</li> 
  <li>Non-functionality testing like performance and security testing will not be performed in the current project</li>
  <li>There will be no mobile support for the project, only the web app will be tested</li>
  <li>Automation testing is beyond the scope of the project</li>
</ul>

## **Test Process**

### Test planning

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.

### Entry criteria:

<ul>
     <li>Business requirments are completed and deliveredto the testing team for evaluation</li>
     <li>Potential risks are detected and mitigated</li>
     <li>Test plan for the two modules are finished and ready to be executed</li>
     <li>The roles have been allocated</li>
</ul>

### Exit criteria:

<ul>
     <li>All tests have been executed</li>
     <li>At least 90% of test are passed</li>
     <li>No critical or major issues remain unresolved</li>
     <li>The bugs not resolved do not present a high risk</li>
     <li>Test reports and status have been created and send to the production team</li>
     <li>Deadline was reach successfully</li>
</ul>

### Project risks:

<ul>
     <li>Team is composed of one member which might affect the deadline</li>
     <li>Team lacks the experince and knowledge to guaranteed level of quality desired</li>
     <li>Not enough time can be allocated to test all functionalities of the scopes</li>
</ul>

### Product risks:

<ul>
     <li>Only two modules are in the testing scope, leading to pottential risks for the rest of the functionalities not in scope</li>
</ul>

### Test Analysis

Test conditions will be performed after the business requirments

Below can be found example for a few test conditions created in the scope of the project
![image](https://github.com/valentinJipa/ReposteryTest/assets/33808653/b0915b4f-fbfa-43cb-b0c7-78c485de850f)


### Test Design

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The full set of tests can be found in a comprehensive format [here](https://github.com/valentinJipa/ReposteryTest/blob/main/Zephyr_TestCases.pdf).
<ul>
     <li>GUI and functionality test cases were create created in Zephyr squad</li>
     <li>Blackbox testing methods like equivalence partition and boundary value analysis for the creation of test cases</li>
</ul>

### Test Implementation

Before begining the test execeution, the following elements need to be ready:

<ul>
     <li>The test environment is functional(Reddit home page)</li>
     <li>Tester gas access to the environment in question</li>
     <li>All test cases were added to jira in cycle summary</li>
</ul>

