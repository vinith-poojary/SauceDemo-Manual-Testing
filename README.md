# SauceDemo Software Testing Project

## Project Overview

This is a practical manual software testing project performed on the SauceDemo web application.

The project demonstrates a real-world QA testing workflow including test scenario preparation, test case design, test execution, defect identification, Jira bug reporting, and test documentation.

## Application Tested

SauceDemo

## Testing Type

Manual Testing

## Modules Tested

- Login
- Product Inventory
- Checkout

## Testing Activities Completed

- Identified test scenarios
- Designed test cases
- Executed test cases
- Recorded actual results
- Marked test cases as Pass/Fail
- Identified potential and confirmed defects
- Documented defects in a Bug Report
- Reported defects in Jira
- Captured screenshots/evidence
- Maintained testing documentation
- Organized testing artifacts in GitHub

## Test Artifacts

### Login
- Login Test Scenarios
- Login Test Cases
- Login Test Execution

### Product Inventory
- Product Inventory Test Scenarios
- Product Inventory Test Cases
- Product Inventory Test Execution

### Checkout
- Checkout Test Scenarios
- Checkout Test Cases
- Checkout Test Execution

### Defect Management
- Bug Report
- Jira Bug Reports
- Screenshots/Evidence
- Bug Retesting documentation

## Defects Identified

During testing, the following defects were identified:

1. **Postal Code Validation**
   - Postal Code accepts alphabetic and special-character input such as `abc123` and `@#$`.

2. **Reset App State UI Synchronization**
   - Reset App State clears the cart, but the product button continues to display `Remove` until the page is refreshed.

3. **Whitespace Validation**
   - First Name and Last Name fields accept whitespace-only input.

Each defect is documented separately and tracked using Jira.

## Tools Used

- LibreOffice Calc
- Jira
- GitHub
- SauceDemo

## Testing Workflow

```text
Application Understanding
        ↓
Test Scenarios
        ↓
Test Cases
        ↓
Test Execution
        ↓
Defect Identification
        ↓
Bug Report
        ↓
Jira Bug Tracking
        ↓
Retesting
        ↓
Documentation
