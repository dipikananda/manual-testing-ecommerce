# E-Commerce Website – Test Scenarios

## 1. Document Information

| Item                   | Details                           |
| ---------------------- | --------------------------------- |
| Project                | E-Commerce Website Manual Testing |
| Application Under Test | SauceDemo                         |
| Testing Type           | Manual Testing                    |
| Prepared By            | Dipika Nanda                      |
| Document Version       | 1.0                               |

---

## 2. Objective

The objective of this document is to identify high-level test scenarios for the SauceDemo e-commerce web application.

These scenarios will be used as the basis for preparing detailed test cases and executing the testing activities.

---

## 3. Modules Covered

The following modules are covered:

1. Login
2. Products
3. Product Sorting
4. Shopping Cart
5. Checkout
6. Order Confirmation

---

## 4. Test Scenarios

### 4.1 Login Module

| Scenario ID | Test Scenario                                                   | Priority |
| ----------- | --------------------------------------------------------------- | -------- |
| TS-001      | Verify login with valid username and password                   | High     |
| TS-002      | Verify login with invalid username                              | High     |
| TS-003      | Verify login with invalid password                              | High     |
| TS-004      | Verify login with blank username                                | High     |
| TS-005      | Verify login with blank password                                | High     |
| TS-006      | Verify login with both username and password blank              | High     |
| TS-007      | Verify password is masked                                       | Medium   |
| TS-008      | Verify locked user cannot log in                                | High     |
| TS-009      | Verify appropriate error message is displayed for invalid login | High     |
| TS-010      | Verify user can log out successfully                            | Medium   |

### 4.2 Products Module

| Scenario ID | Test Scenario                                        | Priority |
| ----------- | ---------------------------------------------------- | -------- |
| TS-011      | Verify products are displayed after successful login | High     |
| TS-012      | Verify product name is displayed correctly           | Medium   |
| TS-013      | Verify product description is displayed correctly    | Medium   |
| TS-014      | Verify product price is displayed correctly          | High     |
| TS-015      | Verify product image is displayed correctly          | Medium   |
| TS-016      | Verify user can open product details                 | Medium   |
| TS-017      | Verify user can add a product to the cart            | High     |
| TS-018      | Verify user can add multiple products to the cart    | High     |

### 4.3 Product Sorting Module

| Scenario ID | Test Scenario                                       | Priority |
| ----------- | --------------------------------------------------- | -------- |
| TS-019      | Verify products can be sorted by name A to Z        | Medium   |
| TS-020      | Verify products can be sorted by name Z to A        | Medium   |
| TS-021      | Verify products can be sorted by price low to high  | Medium   |
| TS-022      | Verify products can be sorted by price high to low  | Medium   |
| TS-023      | Verify selected sorting option is applied correctly | Medium   |

### 4.4 Shopping Cart Module

| Scenario ID | Test Scenario                                        | Priority |
| ----------- | ---------------------------------------------------- | -------- |
| TS-024      | Verify selected product appears in the shopping cart | High     |
| TS-025      | Verify multiple selected products appear in the cart | High     |
| TS-026      | Verify product details in the cart are correct       | High     |
| TS-027      | Verify product can be removed from the cart          | High     |
| TS-028      | Verify cart item count is updated correctly          | High     |
| TS-029      | Verify user can continue shopping from the cart      | Medium   |
| TS-030      | Verify user can proceed to checkout from the cart    | High     |

### 4.5 Checkout Module

| Scenario ID | Test Scenario                                         | Priority |
| ----------- | ----------------------------------------------------- | -------- |
| TS-031      | Verify checkout page is displayed correctly           | High     |
| TS-032      | Verify checkout with valid customer information       | High     |
| TS-033      | Verify first name is mandatory                        | High     |
| TS-034      | Verify last name is mandatory                         | High     |
| TS-035      | Verify postal code is mandatory                       | High     |
| TS-036      | Verify checkout validation for blank mandatory fields | High     |
| TS-037      | Verify user can cancel checkout                       | Medium   |
| TS-038      | Verify user can continue to order review              | High     |

### 4.6 Order Review and Confirmation Module

| Scenario ID | Test Scenario                                                         | Priority |
| ----------- | --------------------------------------------------------------------- | -------- |
| TS-039      | Verify selected products are displayed in the order summary           | High     |
| TS-040      | Verify product prices are displayed correctly in the order summary    | High     |
| TS-041      | Verify total price is calculated correctly                            | High     |
| TS-042      | Verify user can place an order with valid information                 | High     |
| TS-043      | Verify successful order confirmation is displayed                     | High     |
| TS-044      | Verify order completion message is displayed correctly                | High     |
| TS-045      | Verify user can return to the products page after completing an order | Medium   |

---

## 5. Scenario Summary

| Module                        | Number of Scenarios |
| ----------------------------- | ------------------: |
| Login                         |                  10 |
| Products                      |                   8 |
| Product Sorting               |                   5 |
| Shopping Cart                 |                   7 |
| Checkout                      |                   8 |
| Order Review and Confirmation |                   7 |
| **Total**                     |              **45** |

---

## 6. Priority Definition

### High

Business-critical functionality that must work correctly.

Examples:

* Login
* Add to cart
* Checkout
* Order placement

### Medium

Important functionality that affects the user experience but does not normally prevent the main business flow.

Examples:

* Product sorting
* Product details
* Cancel checkout

---

## 7. Next Testing Activity

The above test scenarios will be used to create detailed test cases.

Each test case will contain:

* Test Case ID
* Scenario ID
* Test Case Description
* Preconditions
* Test Steps
* Test Data
* Expected Result
* Actual Result
* Status
