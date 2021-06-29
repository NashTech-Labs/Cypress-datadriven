# Cypress-datadriven

This template will help you to have a data driven framework with Cypress. Here, we are using an .xlsx file(excel) file to read the test data. Since, cypress doesn't support .xlsx file, therefore we will conc=vert the excel file to JSON data, and as a result we will use that JSON data in our test cases.

# Why we need a Data Driven Framework? 

These are the main keypoints for having an data driven approach in our testing framework.

1. Allows to test application with multiple sets of data values during Regression testing.
2. Test data and verification data can be organized in just one file, and it is separate from the test case logic.
3. Data-driven testing can perform any phase of the development.
4. Allows developers and testers to have clear separation for the logic of their test cases/scripts from the test data.
5. Any changes in the test script do not have any sideffect on the test data.
6. To create an individual test for each data set is a lengthy and time-consuming process. Data Driven Testing framework resolves this issue by keeping the data separate from Functional tests.

**Plugin Used:-**
We wil have to use an external plugin in order to achieve our use case.  We can do so by running the following command at the project root level.

```
npm install node-xlsx --save-dev
```
**Technologies used**:-
Programming language - JavaScript

Build tool - Node Js

Automation tool - Cypress

IDE - Visual Code Studio

Assertion framework - Chai, Mocha, jQuery

**Steps for execution:-**

In order to run the test, we just have to go into the directory 

1.  Check out to the directory ../Cypress-datadriven/ReadExcel-Cypress

2. To open the cypress dashboard, use the command

```
node_modules/.bin/cypress open
```

3.  To run the test in Headless mode, use the command
```
node_modules/.bin/cypress run
```

4. To run the test in browser, use the command

```
node_modules/.bin/cypress run --browser chrome
```

For better understading, please refer to the blog
https://blog.knoldus.com/reading-data-from-excel-file-cypress/
