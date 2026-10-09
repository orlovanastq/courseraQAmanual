# TC-001: Verify successful checkout after placing an item in the cart

## Preconditions 
- The user is logged into the application with a valid account.
- The user is navigated to the product catalogue page.
- The shopping cart is empty.

## Environment: MindBridge, http://localhost:3000

## Test Steps:
  1. Click on the product "viral Software Testing platforms".
  2. Click on "Add to cart" button.
  3. Click on the cart icon from navigation bar.
  4. Click on "checkout" button.
  5. Enter a valid ZIP code "94105".
  6. Click on "place order" button.

## Expected result: 
- The order is successfully placed and a confirmation message is displayed.
- The shopping cart is cleared.
