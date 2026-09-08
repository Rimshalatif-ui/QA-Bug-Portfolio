# Login Module - Test Cases

| Test Case ID | Description | Steps | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|
| TC_001 | Verify login with valid credentials | 1. Open login page 2. Enter valid username 3. Enter valid password 4. Click Login | User should be redirected to dashboard | As expected | Pass |
| TC_002 | Verify login with invalid password | 1. Open login page 2. Enter valid username 3. Enter invalid password 4. Click Login | Error message "Invalid credentials" should appear | As expected | Pass |
| TC_003 | Verify login with empty fields | 1. Open login page 2. Leave username and password blank 3. Click Login | Validation message should appear for required fields | As expected | Pass |
| TC_004 | Verify "Forgot Password" link | 1. Open login page 2. Click "Forgot Password" link | User should be redirected to password reset page | As expected | Pass |
| TC_005 | Verify login button is disabled with empty fields | 1. Open login page 2. Leave fields empty | Login button should remain disabled | As expected | Pass |
