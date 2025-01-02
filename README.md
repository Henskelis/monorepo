# TypeScript Monorepo Example

This repo will include the following:

* TypeScript configuration
* Formatter, linter and spell checker with automatic formatting on a pre-commit git hook
* Turborepo to manage relationships between projects of the repo
* Web App (showcase and documentation)
* Internal library to share code
* Internal CLI tool to create or manage packages
* Packages (projects to be released)
* Tests
  * Unit tests with Vitest and JSDOM
  * E2E tests with Playwright
  * MCR tests coverage reports
* CI/CD
  * CI - Code quality checks and running tests
  * CD - Build packages, create releases and deploy web app 
