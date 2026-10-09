# Bug Report - Invalid characters accepted in ZIP code field

**Title:**
<!-- Order is placed successfully when entering special characters in Zip Code field -->

**Environment:** MindBridge, http://localhost:3000

**Preconditions:**
- User is logged in and has item in the shopping cart.

**Steps to Reproduce:**
1. Navigate to the Checkout page.
2. Fill in all required fields with valid data.
3. Enter special characters `#$%^&` into the "ZIP Code" field.
4. Click the "Place order" button.

**Expected Result:**
'An error message (e.g., "Invalid ZIP code") should be displayed, and the order should NOT be placed.'

**Actual Result:**
<!-- The order is successfully placed and added to the orders list.-->

**Severity:** High / Medium / Low
<!-- High (Data validation failure leading to invalid data in DB)-->

**Notes / Evidence:**
<!--  -->
