# Test Cases — E-commerce Website

**Project:** Online Store Testing
**QA Engineer:** Jibek Rysbekova
**Testing Type:** Functional Testing
**Test Level:** Manual Testing

---

## TC-001: Successful User Registration

**Priority:** High
**Type:** Positive

**Preconditions:**
- Registration page is open.
- User does not have an existing account.

**Test Data:**
- Email: jibek.test@example.com
- Password: Test12345!

**Steps:**
1. Open the registration page.
2. Enter a valid email.
3. Enter a valid password.
4. Click the Register button.

**Expected Result:**
User account is successfully created.

---

## TC-002: Registration with Invalid Email

**Priority:** High
**Type:** Negative

**Test Data:**
- Email: jibek123
- Password: Test12345!

**Steps:**
1. Open the registration page.
2. Enter an invalid email.
3. Enter a valid password.
4. Click Register.

**Expected Result:**
The system displays an email validation error.

---

## TC-003: Registration with Empty Password

**Priority:** High
**Type:** Negative

**Steps:**
1. Open the registration page.
2. Enter a valid email.
3. Leave the password field empty.
4. Click Register.

**Expected Result:**
The system displays a required field error.

---

## TC-004: Successful Login

**Priority:** High
**Type:** Positive

**Preconditions:**
- User has an existing account.

**Test Data:**
- Email: jibek.test@example.com
- Password: Test12345!

**Steps:**
1. Open the login page.
2. Enter valid email and password.
3. Click Login.

**Expected Result:**
User successfully logs in.

---

## TC-005: Login with Invalid Password

**Priority:** High
**Type:** Negative

**Steps:**
1. Open the login page.
2. Enter a registered email.
3. Enter an incorrect password.
4. Click Login.

**Expected Result:**
The system displays an authentication error.

---

## TC-006: Login with Empty Fields

**Priority:** Medium
**Type:** Negative

**Steps:**
1. Open the login page.
2. Leave email and password empty.
3. Click Login.

**Expected Result:**
The system displays validation messages.

---

## TC-007: Search for an Existing Product

**Priority:** Medium
**Type:** Positive

**Test Data:**
- Product: Laptop

**Steps:**
1. Open the homepage.
2. Enter Laptop in the search field.
3. Click Search.

**Expected Result:**
Relevant products are displayed.

---

## TC-008: Search for a Non-existing Product

**Priority:** Medium
**Type:** Negative

**Test Data:**
- Product: XYZ123456

**Steps:**
1. Open the homepage.
2. Enter XYZ123456 in the search field.
3. Click Search.

**Expected Result:**
A No products found message is displayed.

---

## TC-009: Add Product to Cart

**Priority:** High
**Type:** Positive

**Steps:**
1. Open the product catalog.
2. Select a product.
3. Click Add to Cart.
4. Open the shopping cart.

**Expected Result:**
The selected product appears in the cart.

---

## TC-010: Remove Product from Cart

**Priority:** Medium
**Type:** Positive

**Preconditions:**
- Shopping cart contains at least one product.

**Steps:**
1. Open the shopping cart.
2. Click Remove next to the product.
3. Check the cart.

**Expected Result:**
The product is removed from the cart.

---

## TC-011: Update Product Quantity

**Priority:** Medium
**Type:** Positive

**Preconditions:**
- Shopping cart contains one product.

**Steps:**
1. Open the shopping cart.
2. Change product quantity from 1 to 2.
3. Check the total price.

**Expected Result:**
The quantity is updated and the total price is recalculated correctly.

---

## TC-012: Successful Checkout

**Priority:** High
**Type:** Positive

**Preconditions:**
- Shopping cart contains a product.

**Steps:**
1. Open the shopping cart.
2. Click Checkout.
3. Enter valid delivery information.
4. Confirm the order.

**Expected Result:**
The order is successfully placed and confirmation is displayed.
