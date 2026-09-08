# SauceDemo - Cart & Checkout Test Cases
**App URL:** https://www.saucedemo.com

| Test Case ID | Description | Steps | Test Data | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|
| TC_006 | Verify adding a product to cart | 1. Login as standard_user 2. Click "Add to Cart" on any product | N/A | Product should be added, cart icon should show count "1" | As expected | Pass |
| TC_007 | Verify removing a product from cart | 1. Login and add a product to cart 2. Go to cart page 3. Click "Remove" | N/A | Product should be removed, cart count should update to "0" | As expected | Pass |
| TC_008 | Verify checkout with valid information | 1. Add product to cart 2. Click Checkout 3. Enter First Name, Last Name, Zip Code 4. Click Continue 5. Click Finish | Name: John, Last: Doe, Zip: 12345 | Order should complete with "Thank you for your order!" message | As expected | Pass |
| TC_009 | Verify checkout with empty required fields | 1. Add product to cart 2. Click Checkout 3. Leave fields empty 4. Click Continue | N/A | Error message "First Name is required" should appear | As expected | Pass |
| TC_010 | Verify cart badge count with multiple items | 1. Login as standard_user 2. Add 3 different products to cart | N/A | Cart icon should display count "3" | As expected | Pass |
