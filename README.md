# Travel Plan QA

![Playwright Tests](https://img.shields.io/badge/tests-playwright-2EAD33)

QA portfolio project for **Travel Plan**, a road trip planning app.

## About the app

Travel Plan helps travelers find points of interest along the way, plan their stops and discover new tourist spots. The app currently has more than 90,000 points on the map, each with location, phone number and social media links.

The app's source code is private. This repository contains only the test documentation and the automated tests, which run against the published app.

## What is tested

| Flow | Type | Status |
| --- | --- | --- |
| Login | Automated (Playwright) | In progress |
| Create a new route | Automated (Playwright) | Planned |
| Explore the map | Automated (Playwright) | Planned |

## Repository structure

```
docs/
  test-plan.md      Scope, approach, environments and risks
  test-cases.md     Test cases for each flow
  bug-reports/      Bugs found, with steps to reproduce
tests/              Playwright tests
```

## Tools

- [Playwright](https://playwright.dev/) with TypeScript
- GitHub Actions (continuous integration)

## How to run the tests

```bash
npm install
npx playwright install
npx playwright test
```

## Author

Paulo Régis Carvalho, QA Analyst · [LinkedIn](https://www.linkedin.com/in/pauloregisscarvalho/)
