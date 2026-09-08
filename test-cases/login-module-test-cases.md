# SauceDemo - Login Test Cases
**App URL:** https://www.saucedemo.com

| Test Case ID | Description | Steps | Test Data | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|
| TC_001 | Verify login with valid credentials | 1. Open saucedemo.com 2. Enter username 3. Enter password 4. Click Login | Username: `standard_user`, Password: `secret_sauce` | User should be redirected to Products page | As expected | Pass |
| TC_002 | Verify login with locked out user | 1. Open saucedemo.com 2. Enter username 3. Enter password 4. Click Login | Username: `locked_out_user`, Password: `secret_sauce` | Error message "Sorry, this user has been locked out" should appear | As expected | Pass |
| TC_003 | Verify login with invalid password | 1. Open saucedemo.com 2. Enter valid username 3. Enter wrong password 4. Click Login | Username: `standard_user`, Password: `wrong_pass` | Error message "Username and password do not match" should appear | As expected | Pass |
| TC_004 | Verify login with empty fields | 1. Open saucedemo.com 2. Leave both fields blank 3. Click Login | N/A | Error message "Username is required" should appear | As expected | Pass |
| TC_005 | Verify login with performance glitch user | 1. Open saucedemo.com 2. Enter username 3. Enter password 4. Click Login | Username: `performance_glitch_user`, Password: `secret_sauce` | Login should succeed but take longer to load Products page | As expected | Pass |
