To install the Cypress project and run tests, follow these steps:

#####Pre requisites
######Node.js and npm:
Cypress is a JavaScript end-to-end testing framework and requires Node.js and npm to be installed. You can download them from the official Node.js website.

#####Step1
Clone the repository : 
Run the following command : git clone <repository-url>

#####Step2
Navigate to the Project Directory:
cd path/to/your/project

#####Step3
Open the Cypress Test Runner: npx cypress open
This will open the Cypress Test Runner interface.
Click on E2E testing
Select the browser and click on start E2E testing
select the spec file that you want to run
After runnung the tests, on the right side see the result of the tests

#####Alternatively
#####Step 3: Run Tests from the Command Line 
If you prefer to run tests from the command line, you can use the following commands:

Runs all tests headlessly in the terminal(without GUI)
npx cypress run

Run a specific test file
npx cypress run --spec "cypress/integration/your-test-file.spec.js"

Run on a specific browser
cypress run --browser <browser-name-or-path>

Run on a specific browser a specific test file
ypress run --browser <browser-name-or-path> --spec "cypress/integration/your-test-file.spec.js"

When you run the tests from command line screenshots of the failed tests will be available in the foleder cypress/screenshots
Video of the entire test would be available in the cypress/videos
