# Learning Playwright Fundamentals 2x

This repository contains a Playwright automation learning project with examples covering basic test creation, annotations, browser contexts, multiple pages, and test options.

## Project Structure

- tests/01_Basics/ - introductory Playwright examples
- tests/02_First_tests/ - examples focused on running and configuring tests
- tests/Template.spec.ts - starter template for new tests
- playwright.config.ts - Playwright configuration
- package.json - project dependencies and scripts

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Install the required Playwright browsers:
   ```bash
   npx playwright install
   ```

3. Run all tests:
   ```bash
   npx playwright test
   ```

4. Run a specific test file:
   ```bash
   npx playwright test tests/02_First_tests/237_BCP_Test_Options.spec.ts
   ```

5. Run tests in headed mode:
   ```bash
   npx playwright test --headed
   ```

## Notes

These examples are intended for learning and practicing Playwright fundamentals, including assertions, test configuration, and browser context management.
