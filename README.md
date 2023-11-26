# Playwright-Tests #JS

Description:
To Perform actions on Amazon.com, a test mail id was created and used for login.

Automation code for Amazon functionalities mentioned in test cases are created as different spec.js files which are all created as a data driven method from JSON file in serial mode.
Code is constructed with Page Object Model, and the tests to run in chrome browser in headed mode (other browsers can be added in config.js file for cross browser testings)

How to set it up:

1.The code can be directly imported from repo and run in Visual Studio Code, if Node.js and playwright are installed.
2.If above are not installed, visual studio code or any other platforms needs to be installed (https://code.visualstudio.com/download).
3.Node.js needs to be downloaded (https://nodejs.org/en/download) and installed (https://radixweb.com/blog/installing-npm-and-nodejs-on-windows-and-mac "explained with screenshots") and the environment variable path needs to be set via my computer->properties->advanced->environment variables->path-> set path
4.After installing Node.js, open VSC and install playwright with command :  npm init playwright@latest
5.The code can be run after these steps.

How to run code locally:

1.To run all the test cases through terminal use command : npx playwright test
2.To run specific test case use command : npx playwright test "name of test"
3.Tests can also be run in UI mode using : npx playwright test --ui


Manual Test cases:

https://docs.google.com/spreadsheets/d/1ojjrX3h_wzuDVp07EKABHxugNyqDneNa70p3eSwm-7E/edit?usp=sharing

