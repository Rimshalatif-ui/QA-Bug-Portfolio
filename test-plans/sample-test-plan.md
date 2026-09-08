# Test Plan: SauceDemo E-Commerce Application

**App URL:** https://www.saucedemo.com

## 1. Objective
To verify that the login, product browsing, cart, and checkout functionalities of the SauceDemo application work as expected across valid, invalid, and edge-case scenarios.

## 2. Scope
**In Scope:**
- Login with different user types (standard, locked-out, problem, performance-glitch users)
- Product listing and sorting
- Add/remove items from cart
- Checkout flow (information entry, order summary, order completion)

**Out of Scope:**
- Backend/database testing
- Payment gateway integration (SauceDemo uses a mock checkout)

## 3. Test Approach
- Manual functional testing for UI validations and user flows
- Exploratory testing to uncover visual/UX bugs (e.g., problem_user image issue)
- Automation (Cypress) for regression coverage on critical flows: login, add to cart, checkout

## 4. Environment
- Browser: Chrome, Firefox
- OS: Windows 11
- Test Data: Predefined SauceDemo users (standard_user, locked_out_user, problem_user, performance_glitch_user)

## 5. Entry Criteria
- Application accessible at https://www.saucedemo.com
- Test data (user credentials) available

## 6. Exit Criteria
- All planned test cases executed
- No critical/high severity bugs open
- 95% test case pass rate achieved

## 7. Deliverables
- Test Cases (see `test-cases/`)
- Bug Reports (see `bug-reports/`)
- Cypress Automation Scripts (see `automation/`)
- Test Execution Summary

## 8. Risks & Mitigation
| Risk | Mitigation |
|---|---|
| Third-party demo site may change without notice | Re-validate test cases periodically |
| Limited backend visibility (mock data) | Focus testing on UI/UX and functional flows |
