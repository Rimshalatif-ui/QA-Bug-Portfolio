# Bug Report: BUG-001

**Title:** Login page accepts invalid password format without validation error

**Module:** Login

**Environment:** Chrome v128, Windows 11

**Severity:** Medium

**Priority:** High

## Steps to Reproduce
1. Navigate to the login page
2. Enter a valid username
3. Enter a password with only 2 characters
4. Click "Login"

## Expected Result
System should display a validation error stating "Password must be at least 8 characters."

## Actual Result
No validation error is shown; the request is submitted to the server directly.

## Attachments
_(Add screenshot here if available)_

## Status
Open
