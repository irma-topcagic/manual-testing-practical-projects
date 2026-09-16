# Validate that booking is not allowed when From and To destinations are the same

**Test Suite:** Select Flight Scenarios

## Precondition
The user is logged in.

## Test Steps

| Step | Test Data | Expected Result |
|---|---|---|
| 1. Navigate to the Select Flight page | — | Select Flight page is displayed |
| 2. Select "One way" trip type | — | "One way" is selected |
| 3. Select From destination | New York | Destination is selected |
| 4. Select To destination (same as From) | New York | Destination is selected |
| 5. Select a valid departing date | Valid future date | Date is accepted |
| 6. Click "Continue" | — | System should display a validation error and prevent the user from proceeding |

## Actual Result
The system allows the same destination to be selected in both the "From" and "To" fields with no validation error, and does not prevent the user from proceeding (booking continues to the next step).

## Priority
High

## Status
Fail

## Related Bug
FBA-4 / BUG-04-same-destination

## Test Environment
- Device: Lenovo laptop
- Browser: Chrome
- Network: Wi-Fi