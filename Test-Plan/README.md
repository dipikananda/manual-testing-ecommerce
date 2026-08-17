
# Test Plan – E-Commerce Website

## 1. Document Information

| Item                   | Details                           |
| ---------------------- | --------------------------------- |
| Project                | E-Commerce Website Manual Testing |
| Application Under Test | SauceDemo                         |
| Testing Type           | Manual Testing                    |
| Application Type       | Web Application                   |
| Prepared By            | Dipika Nanda                      |
| Document Version       | 1.0                               |
| Status                 | Draft                             |

---

## 2. Project Overview

This test plan defines the testing approach for the SauceDemo e-commerce web application.

The objective is to verify that the major business functions of the application work as expected and to identify defects before release.

The testing will cover the complete user journey from login through product selection, shopping cart, checkout, and order confirmation.

---

## 3. Testing Objectives

The main objectives of testing are:

* Verify that users can successfully log in.
* Verify that products are displayed correctly.
* Verify product sorting functionality.
* Verify that products can be added to and removed from the shopping cart.
* Verify that checkout functionality works correctly.
* Verify mandatory field validations.
* Verify order summary and price calculations.
* Verify that users can successfully place an order.
* Identify and document defects.
* Perform regression testing after defects are fixed.

---

## 4. Scope of Testing

### 4.1 In Scope

The following modules will be tested:

1. Login
2. Products
3. Product Sorting
4. Shopping Cart
5. Checkout
6. Order Confirmation

### 4.2 Out of Scope

The following areas are outside the scope of this project:

* Performance testing
* Security testing
* Load testing
* Accessibility testing
* Backend source-code testing
* Production environment testing

---

## 5. Testing Types

The following testing types will be performed:

* Functional Testing
* UI Testing
* Smoke Testing
* Sanity Testing
* Regression Testing
* Negative Testing

---

## 6. Test Approach

Testing will be performed manually using predefined test scenarios and test cases.

The testing process will include:

1. Understanding application functionality.
2. Identifying test scenarios.
3. Creating detailed test cases.
4. Preparing test data.
5. Executing test cases.
6. Recording actual results.
7. Reporting defects.
8. Retesting fixed defects.
9. Performing regression testing.
10. Preparing the final test summary report.

---

## 7. Test Environment

| Item             | Details                    |
| ---------------- | -------------------------- |
| Application      | SauceDemo                  |
| Application Type | Web Application            |
| Browser          | Google Chrome              |
| Operating System | Windows                    |
| Testing Method   | Manual                     |
| Defect Tracking  | Jira / GitHub              |
| Documentation    | Microsoft Excel / Markdown |

---

## 8. Entry Criteria

Testing can begin when:

* The application is accessible.
* Test scenarios have been identified.
* Test cases have been prepared.
* Required test data is available.
* The test environment is available.

---

## 9. Exit Criteria

Testing can be considered complete when:

* All planned test cases have been executed.
* Critical and high-priority defects have been addressed or documented.
* Failed test cases have been investigated.
* Required retesting has been completed.
* Regression testing has been completed.
* The final test summary report has been prepared.

---

## 10. Defect Management

Defects identified during testing will be documented with the following information:

* Defect ID
* Defect Title
* Module
* Description
* Steps to Reproduce
* Expected Result
* Actual Result
* Severity
* Priority
* Environment
* Status
* Screenshot / Evidence

Defects will be classified according to severity and priority.

---

## 11. Deliverables

The following testing deliverables will be maintained:

* Test Plan
* Test Scenarios
* Test Cases
* Test Execution Report
* Bug Reports
* Test Summary Report

---

## 12. Risks and Mitigation

| Risk                            | Mitigation                                             |
| ------------------------------- | ------------------------------------------------------ |
| Application becomes unavailable | Reattempt testing when application is available        |
| Test data is unavailable        | Prepare valid and invalid test data in advance         |
| Defects block further testing   | Document blocker and continue with independent modules |
| Browser compatibility issue     | Perform testing using supported browsers               |
| Requirements are unclear        | Review application behaviour and document assumptions  |

---

## 13. Assumptions

* The SauceDemo application is available during testing.
* Test credentials required for the application are available.
* Testing is performed in a supported browser.
* The application functionality remains stable during the testing cycle.

---

## 14. Tools

* GitHub
* Microsoft Excel
* Google Chrome
* Browser DevTools
* Jira
* Postman

---

## 15. Approval

| Role      | Name         | Status   |
| --------- | ------------ | -------- |
| QA Tester | Dipika Nanda | Prepared |
| Reviewer  | N/A          | Pending  |
