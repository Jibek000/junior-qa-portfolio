# Bug Reports — E-commerce Website

**Project:** Online Store Testing
**QA Engineer:** Jibek Rysbekova
**Testing Type:** Manual Testing

Note: The following bug reports are educational examples.
They are hypothetical and have not been verified on a live website.

---

## BUG-001: Registration accepts an invalid email address

**Severity:** Medium
**Priority:** High
**Module:** Registration
**Environment:** Google Chrome / Windows 11

**Preconditions:**
Registration page is open.

**Steps to Reproduce:**
1. Open the registration page.
2. Enter `jibek123` in the email field.
3. Enter a valid password.
4. Click the Register button.

**Expected Result:**
The system should display an email validation error.

**Actual Result:**
The system accepts the invalid email address.

**Status:** New

---

## BUG-002: Incorrect total price in shopping cart

**Severity:** High
**Priority:** High
**Module:** Shopping Cart
**Environment:** Google Chrome / Windows 11

**Preconditions:**
At least one product is added to the cart.

**Steps to Reproduce:**
1. Open the product catalog.
2. Add two products with different prices to the cart.
3. Open the shopping cart.
4. Check the total price.

**Expected Result:**
The total price should equal the sum of all product prices multiplied by their quantities.

**Actual Result:**
The displayed total price is incorrect.

**Status:** New

---

## BUG-003: Login button does not respond

**Severity:** Medium
**Priority:** High
**Module:** Authorization
**Environment:** Google Chrome / Windows 11

**Preconditions:**
Login page is open.

**Steps to Reproduce:**
1. Enter valid login credentials.
2. Click the Login button.
3. Wait for the response.

**Expected Result:**
The user should be successfully logged in.

**Actual Result:**
Nothing happens after clicking the Login button.

**Status:** New

---

## BUG-004: Product image is not displayed

**Severity:** Low
**Priority:** Medium
**Module:** Product Catalog
**Environment:** Google Chrome / Windows 11

**Preconditions:**
Product catalog is open.

**Steps to Reproduce:**
1. Open the product catalog.
2. Find a product with a missing image.
3. Observe the product image area.

**Expected Result:**
The product image should be displayed correctly.

**Actual Result:**
The product image is missing or broken.

**Status:** New

---

## BUG-005: Cart quantity is not updated

**Severity:** Medium
**Priority:** Medium
**Module:** Shopping Cart
**Environment:** Google Chrome / Windows 11

**Preconditions:**
A product is added to the shopping cart.

**Steps to Reproduce:**
1. Open the shopping cart.
2. Change product quantity from 1 to 2.
3. Check the displayed quantity.

**Expected Result:**
The product quantity should be updated to 2.

**Actual Result:**
The displayed quantity remains unchanged.

**Status:** New
