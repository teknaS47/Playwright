# [Playwright](https://playwright.dev/docs/intro)
Exploring Playwright for e2e testing

Open-source framework by Microsoft
Multi-browser support


E2E testing
End-to-end testing verifies that all components of a system can run under real-world scenarios. The goal of this form of testing is to simulate a user experience from start to finish.

# Installation
Create a folder to install Playwright 
```
yarn create playwright
```

Skip the options to set default values:
```
✔ Do you want to use TypeScript or JavaScript? · TypeScript
✔ Where to put your end-to-end tests? · tests
✔ Add a GitHub Actions workflow? (y/N) · false
✔ Install Playwright browsers (can be done manually via 'yarn playwright install')? (Y/n) · true
```

# Executing the tests
Running the example test
```
yarn playwright test
```

Checking the reports
```
yarn playwright show-report
```

Running tests in UI mode
```
yarn playwright test --ui
```

