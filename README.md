## ![test-automation-process-test-automation](https://github.com/IbrahimaDIALLOBowe/Capstone_Project_Guideline/assets/37409856/352b9d9f-bb04-440c-a03c-38f28a392481)


# Capstone_Project_Guideline

Project Description
In this section of the class, you are required to complete a capstone project. This project will help you implement all the topics you have learned and will continue to learn in the next 3 weeks for UI automation. This project consists of three main parts:

 

Part One:  involves building the project from scratch. Here, you will learn how to set up a project, work with Apache Maven for build management, import necessary dependencies, create source folder structures, packages, and files.
Part Two: of the project involves implementing the Page Object Model Design Pattern for storing UI elements. You'll write scenarios and Scenario Outlines using the Gherkin language, and craft step definitions. You'll also execute the test cases.
Part Three:  of the project mainly involves implementing your CI/CD knowledge. You'll work with version control tools, such as Git and GitHub, and use Jenkins for implementing pipelines.
Each part will be released once its content is covered in class. The project will run in parallel to the class topics.

## Part One  - Deadline July 21, 2023 

To begin with this section, please follow the steps detailed in the BDD framework: 

 1. Maven Project Setup and JRE Version     - In this section you need to update the GroupID and Artifact ID at the time of creating Maven Project. 
groupID<tek.capstone.bdd.framework>

artifactID<tek-capstone-guardians>

 

2. Adding Dependencies to POM.xml file
3. Creating packages, folders, files
4. Environment configuration
5. Creating File Utility and ReadYamlFiles classes
6. WebDriver Interface and Browsers Configuration
7. Creating Base class
8. Creating CommonUtility Class
9. Creating BaseUITest class
10. Creating Test Runner Class
11. Creating POM Factory class and Page Object Model Classes
12. Creating a feature file
13. Creating Step Definitions Class
This practice will enhance your confidence in building a Framework from scratch. Please do not copy and past the code from Wiki, you have to be able to write the for each class, method by yourself.

 

## Part TWO - Deadline August 11, 2023 
For the second part of this project, please follow the steps outlined below:

 

Create feature files for the specified features.
SignIn.feature
Home.feature
RetailAccount.feature
RetailOrder.feature
Generate step definition classes for each feature file.
HomeSteps.java
SignInSteps.java
RetailAccountSteps.java
RetailOrderSteps.java
Develop POM (Page Object Model) classes for each page of the application.
RetailHomePage.java
RetailSignInPage.java
RetailAccountPage.java
RetailOrderPage.java
 

Once these feature files and classes have been created, you should begin writing Scenarios and Scenario Outlines based on the requirements provided.

Please click on below link for Scenario and Scenario Outlines:

TEK Retail Application Scenarios

Implement your best coding skills and automation knowledge, along with BDD implementation. Your code should adhere to coding standards, such as appropriate naming conventions, method comments, and clean code practices.
 

## Part Three - Deadline August 31, 2023 

"For this part of the project, please follow the steps below:

Create a GitHub repository and name it 'Capstone Project - Guardians'.
Push your complete code to this repository.
Create a Jenkins job and follow the naming convention 'Capstone Project - Guardians- [Your Full Name]'.
For your final submission, please provide:

The URL of your GitHub repository
The URL of your Jenkins job
A screenshot of the Cucumber report generated from the Jenkins execution
