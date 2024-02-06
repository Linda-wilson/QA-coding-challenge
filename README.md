#### To install the Cypress project and run tests, follow these steps:

##### Pre requisites
Node.js and npm:
Cypress is a JavaScript end-to-end testing framework and requires Node.js and npm to be installed. You can download them from the official Node.js website.

#### Step1 : Clone the repository
Run the following command: <i> git clone https://github.com/Linda-wilson/QA-coding-challenge.git </i>

##### Step2 : Navigate to the project directory
Run the following command: <i> cd path/to/your/project </i>

##### Step3 : Run the tests from cypress test runner
 (make sure you are on the master branch and not main branch)<br>
 a) Open the Cypress Test Runner with the following command :<i> npx cypress open</i><br>
     This will open the Cypress Test Runner interface<br>
 b) Click on E2E testing<br>
 c) Select the browser and click on start E2E testing<br>
 d) Select the spec file that you want to run<br>
 After runnung the tests, on the leftside you see the test results<br>

##### Alternatively
##### Step 3: Run Tests from the Command Line 
Runs all tests headless in the terminal(without GUI)<br>
<i>npx cypress run </i><br>

When you run the tests from command line screenshots of the failed tests will be available in the foleder cypress/screenshots
Video of the entire test would be available in the folder cypress/videos

Run a specific test file<br>
<i>npx cypress run --spec "cypress/e2e/your-test-file.spec.js"</i><br>

Run on a specific browser<br>
<i>cypress run --browser <browser-name-or-path></i><br>
By default runs on Electron browser<br>

Run on a specific browser a specific test file<br>
<i>cypress run --browser <browser-name-or-path> --spec "cypress/e2e/your-test-file.spec.js"</i><br>

When you run the tests from command line screenshots of the failed tests will be available in the folder cypress/screenshots<br>
Video of the entire test would be available in the folder cypress/videos.
