Sprint 8 project

In this project we tested the rideshare application, Urban Routes.

The QA Engineer student wrote automated tests to check the functionality of Urban Routes. The tests were: 1. Setting the address 2. Selecting Supportive plan 3. Filling in the phone number 4. Adding a credit card 5. Writing a message for the driver 6. Ordering a Blanket and handkerchiefs 7. Ordering 2 Ice creams 8. The car search modal appears.

Test scripts for each step can be found in createAnOrder.e2e.js file in the 'test\specs' folder.

The QA Engineer student used the Page Object Model. Page objects and functions can be found in page.js and helper.js.

Device/environment description

Device - Lenovo Thinkpad X1
OS - Windows 11 HOME
Browser - Google Chrome Version 126.0.6478.127 (Official Build) (64-bit)
Remote server URL generated at: https://cnt-9aabf4b9-3199-4598-83b9-815559c60c97.containerhub.tripleten-services.com

Tools used
VS Code
GitHub
WebdriverIO
Devtools

Testing Method:
Functional Testing used.

How to run the tests

To generate a remote server URL, click the black recutangle button with "Start" text at the Sprint8 project page (via the link in the # Device/environment description). Copy the server address.
Open 'wdio.conf.js' file in 'hm08-qa-us' directory, paste the address in between the quotation marks for 'baseUrl' on the line 31 (example: baseUrl: 'https://cnt-9aabf4b9-3199-4598-83b9-815559c60c97.containerhub.tripleten-services.com'), and save the change.
Execute the 'npm run wdio' command from the project directory in the terminal to run all tests.