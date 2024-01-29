#### To install the Cypress project and run tests, follow these steps:

##### Pre requisites
Node.js and npm:
Cypress is a JavaScript end-to-end testing framework and requires Node.js and npm to be installed. You can download them from the official Node.js website.

#### Step1
Clone the repository : 
Run the following command : git clone <repository-url>

##### Step2
Navigate to the Project Directory:cd path/to/your/project

##### Step3
 a) Open the Cypress Test Runner: npx cypress open<br>
 b) This will open the Cypress Test Runner interface.<br>
 c) Click on E2E testing<br>
 d) Select the browser and click on start E2E testing<br>
 e) select the spec file that you want to run<br>
 After runnung the tests, on the right side see the result of the tests<br>

##### Alternatively
##### Step 3: Run Tests from the Command Line 
If you prefer to run tests from the command line, you can use the following commands:<br>
Runs all tests headlessly in the terminal(without GUI)<br>
npx cypress run<br>

Run a specific test file<br>
npx cypress run --spec "cypress/integration/your-test-file.spec.js"<br>

Run on a specific browser<br>
cypress run --browser <browser-name-or-path><br>

Run on a specific browser a specific test file<br>
ypress run --browser <browser-name-or-path> --spec "cypress/integration/your-test-file.spec.js"<br>

When you run the tests from command line screenshots of the failed tests will be available in the foleder cypress/screenshots<br>
Video of the entire test would be available in the cypress/videos.
