# Borrow calculator page


### Pre-requistes
- Install JDK 8
- Install Maven and configure in Env variables
- download chromedriver and place in /browser-drivers location of project
### How to Install this project
- Navigate to the current folder
- perform below command
  git clone https://github.com/akalavathi/borrowcalculator.git

### How to build and run a project

- 'mvn clean install -DskipTests' to run install required depedencies
- 'mvn test' to run all scripts
- BorrowingCalculatorScenarios.feature file as all scenarios

### Improvements required
- Reports
- screenshots
- detailed way dealing with elements
- currently works only for chrome
- run in pipeline

### Some imp notes

- urls should pass from test.properties only
- browser will be decided based on the property file
- TestRunner will run all the required tags of the project
- BasePage contains all driver information.