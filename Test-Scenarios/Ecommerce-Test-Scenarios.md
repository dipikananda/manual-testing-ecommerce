# E-Commerce Website – Test Scenarios

## Project Overview

This project covers manual testing of the SauceDemo e-commerce web application.

Application: https://www.saucedemo.com/

Testing Type:
- Functional Testing
- UI Testing
- Negative Testing
- Smoke Testing
- Regression Testing

## Test Scenarios

| Scenario ID | Module | Test Scenario | Priority |
|---|---|---|---|
| TS001 | Login | Verify login with valid username and password | High |
| TS002 | Login | Verify login with invalid username | High |
| TS003 | Login | Verify login with invalid password | High |
| TS004 | Login | Verify login with blank username | High |
| TS005 | Login | Verify login with blank password | High |
| TS006 | Login | Verify login with both fields blank | High |
| TS007 | Login | Verify password field is masked | Medium |
| TS008 | Login | Verify locked user cannot login | High |
| TS009 | Products | Verify products are displayed after successful login | High |
| TS010 | Products | Verify product name is displayed correctly | Medium |
| TS011 | Products | Verify product price is displayed correctly | Medium |
| TS012 | Products | Verify product image is displayed | Medium |
| TS013 | Products | Verify product can be added to cart | High |
| TS014 | Products | Verify multiple products can be added to cart | High |
| TS015 | Products | Verify product sorting functionality | Medium |
| TS016 | Cart | Verify selected product appears in cart | High |
| TS017 | Cart | Verify product can be removed from cart | High |
| TS018 | Cart | Verify cart item count is updated correctly | High |
| TS019 | Cart | Verify cart retains selected products | High |
| TS020 | Cart | Verify checkout can be initiated from cart | High |
| TS021 | Checkout | Verify checkout page is displayed | High |
| TS022 | Checkout | Verify checkout with valid customer information | High |
| TS023 | Checkout | Verify first name is mandatory | High |
| TS024 | Checkout | Verify last name is mandatory | High |
| TS025 | Checkout | Verify postal code is mandatory | High |
| TS026 | Checkout | Verify checkout can be cancelled | Medium |
| TS027 | Checkout | Verify order summary is displayed correctly | High |
| TS028 | Checkout | Verify total price is calculated correctly | High |
| TS029 | Order | Verify user can successfully place an order | High |
| TS030 | Order | Verify order confirmation is displayed | High |
