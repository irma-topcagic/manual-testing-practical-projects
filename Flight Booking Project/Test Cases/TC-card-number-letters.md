# Validate that payment is not allowed when card number contains letters or special characters

**Test Suite:** Payment Scenarios

## Precondition
The user has valid passenger details and is on the Pay by Credit Card page.

## Test Steps

| Step | Test Data | Expected Result |
|---|---|---|
| 1. Navigate to the Pay by Credit Card page | — | Payment page is displayed |
| 2. Select Visa as card type | — | Card type is selected |
| 3. Enter card holder's name | Irma Topcagic | Value is accepted |
| 4. Enter card number containing letters/special characters | xyzz 0000 0000 0000 | System should display a validation error (card number must contain only digits) |
| 5. Select expiry date | 12 / 2026 | Value is accepted |
| 6. Click "Pay now" | — | System should prevent the payment and keep the user on the same page |

## Actual Result
No error shown, payment proceeds to the Confirmation page.

## Priority
Highest

## Status
Fail

## Related Bug
FBA-12 / BUG-11-card-number-letters

## Test Environment
- Device: Lenovo laptop
- Browser: Chrome
- Network: Wi-Fi