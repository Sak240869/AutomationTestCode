
# Clip Board Health Project

This Project is for Clip Board Health Project Assignment


## Authors

- [@Sak240869](https://github.com/Sak240869)

## Tech Stack Used

1. Selenium for Test Automation
2. Java(8) for enhancements in Test Cases
3. TestNG for Test Driven and Data Driven Testing
4. Maven s a build tool
5. Git for Code Maintenance
6. Git Hub Actions for CI/CD 
7. Customized Extent Reports 
8. Log4J for logs

### Installation

1. Clone the project from [https://github.com/Sak240869/AutomationTestCode.git](https://github.com/Sak240869/AutomationTestCode.git)
2. Set JDK 1.8 under the Project settings
3. Change Project support to Maven
4. Build the Project

#### Running Tests

To run tests,

1. Local
* Go to  /src/main/java/org/health/config/config.properties
* Change runType to "local"
* Run testng.xml


2. Remote

* Go to  /src/main/java/org/health/config/config.properties
* Change runType to "docker"
* push the changes to main branch
* Job will run on Git Hub Actions and test execution will happen on Git Hub Actions Server

#### GitHub Actions

1. ci.yml contains all the steps of GitHub Actions workflow
2. Once the deployment is finished it deploy the reports on github-pages


#### Reporting
1. Local
Test Execution report can be seen under ExtentResults folder
2. docker
Test Execution report will be published on Git Hub Pages. below is the Url
   [https://sak240869.github.io/AutomationTestCode/ClipBoardHealthTestReport.html](https://sak240869.github.io/AutomationTestCode/ClipBoardHealthTestReport.html)

#### Logs
1. Local
   Test Execution report can be seen under ClipBoardHealthLoggerFiles folder


