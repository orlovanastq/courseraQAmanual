# TC-002: Verify checkout validation with invalid zip code.
**Environment: MindBridge (http://localhost:3000)**

## Preconditions
- The user is logged into the application with a valid account.
- The user is navigated to the product catalogue page.
- The shopping cart is empty.

## Test steps
1. Click on the product "Viral Software Testing Platforms".
2. Click the "Add to Cart" button.
3. Click on the cart icon from the navigation bar.
4. Click the "Checkout" button.
5. Enter a invalid ZIP code "12345".
6. Click the "Place Order" button.

## Expected result
- The order is not placed.
- The warning message "No valid zip code" is displayed on the screen.
- The user remains on the checkout page.
