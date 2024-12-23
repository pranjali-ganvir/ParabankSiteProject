# Automate Parabank Site 
In this project, I have automated core functionalities of the [Parabank online banking application](https://parabank.parasoft.com/parabank/index.htm) using Selenium, TestNG, and Cucumber with Data-Driven Testing. The key test scenarios include:

* Register a New Account: Automate the user registration process by filling out dynamic data (like name, address, and credentials) using data-driven testing from Cucumber's Scenario Outline. This allows testing registration with multiple sets of user data.
* Log in to the Application: Log in with different sets of credentials to validate both successful and unsuccessful login attempts. Use data-driven testing to verify login functionality for multiple users.
* Create a New Savings Account: Once logged in, automate the creation of a savings account.
* Transfer Amount Between Accounts: Automate the process of transferring funds between accounts.

### Built With
* [Java 8](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html) as programming language
* [Maven](https://maven.apache.org/) for Package Management and Build Automation
* [Selenium](https://www.selenium.dev/) for Web Automation
* [TestNG](https://testng.org/) for Java testing framework that supports annotations, parallel execution, and detailed reporting for efficient test automation.
* [Cucumber](https://cucumber.io/docs/cucumber/) for writing BDD-style tests in Gherkin syntax.


### Prerequisites
  Basic understanding of Java with Maven, Selenium, TestNG and Cucumber.

### Running the project

*Project can be run as _TestNG Suite_ by - right clicking the project and select "Run As -> TestNG Suite".

*To execute whole project use maven command - mvn clean test or right click on project - Run as - select maven clean and maven test to execute project

*Project can be run as _Junit Test Runner_ by - right clicking the Cucumber Test Runner class and select "Run As -> Test Runer.

*To update maven project right click the project, and select "Maven -> Update Project -> Check the 'Force Update of Snapshots/Releases' -> Ok". This will update the "Maven Dependencies" project.

*Run maven build command if you don't see "Maven Dependencies" folder: mvn clean install
