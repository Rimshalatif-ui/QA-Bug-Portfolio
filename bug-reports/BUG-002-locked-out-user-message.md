# Bug Report: BUG-002

**Title:** No visual indication (icon/highlight) accompanying the locked-out error message

**App:** SauceDemo (https://www.saucedemo.com)

**Module:** Login

**Environment:** Chrome v128, Windows 11

**Severity:** Low

**Priority:** Medium

## Steps to Reproduce
1. Navigate to https://www.saucedemo.com
2. Enter username: `locked_out_user`, password: `secret_sauce`
3. Click "Login"
4. Observe the error message shown

## Expected Result
The error message "Epic sadface: Sorry, this user has been locked out" should be accompanied by a clear visual cue (e.g., red icon or highlighted border) to draw user attention, improving UX/accessibility.

## Actual Result
The error message is displayed as plain red text only, with no icon or additional visual emphasis, which may reduce visibility for users with visual impairments.

## Attachments
_(Add screenshot here if available)_

## Status
Open
