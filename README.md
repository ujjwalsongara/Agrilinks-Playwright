# Playwright-Automation
    Playwright is a framework for Web Testing and Automation. It is built to enable cross-browser web automation that is reliable and fast. Playwright, also has its own test runner for end-to-end tests called Playwright Test.

# Prerequisites
    Before running the Playwright tests, ensure that you have the following installed:

-   Node.js (version 14 or higher)
-   npm (Node Package Manager)

# Setup

1.  Clone the Repository:
        git clone https://github.com/your-username/playwright.git
        cd playwright

2.  Install Dependencies:
        npm install

3.  Install Browsers:
        npx playwright install


#   Project Structure
    
    The project directory structure is as follows:

-   tests/e2e: Contains all test files.
-   playwright.config.js: Configuration file for Playwright.
-   package.json: Contains project dependencies and scripts.
-   config.json: This file contains the project data.

#   Running Tests

NOTE: Need to run the below commands inside playwright/frontend/ folder

    Run tests one by one then use below command:
        npx playwright test --ui         

    Run all tests together
        npx playwright test

    To generate Allure HTML Reports:
        npm run allure:report


#   Resources

- [Playwright Documentation](https://playwright.dev/docs/intro)
- [Playwright GitHub Repository](https://github.com/microsoft/playwright)
- [Node.js Documentation](https://nodejs.org/en/docs/)
