# Validate one-way trip with today's date

**Test Suite:** Select Flight Scenarios

## Precondition
The user is logged in.

## Test Steps

| Step | Test Data | Expected Result |
|---|---|---|
| 1. Navigate to the Select Flight page | — | Select Flight page is displayed |
| 2. Select "One way" trip type | — | "One way" is selected; Returning date field is hidden/disabled |
| 3. Select today's date as the departing date | Today's date | Date is accepted |
| 4. Select From and To destinations | From: New York, To: Sydney | Destinations are selected |
| 5. Click "Continue" | — | User is redirected to the Passenger Details page |

## Priority
High

## Status
Pass

## Test Environment
- Device: Lenovo laptop
- Browser: Chrome
- Network: Wi-Fi