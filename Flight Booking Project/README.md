# Flight Booking Application — Manual Testing

Manual testing project for the Flight Booking web application (travel.agileway.net), covering the full booking flow: flight selection, passenger details, and payment.

## Test Summary

| Metric | Value |
|---|---|
| Total test cases | 28 |
| Passed | 11 |
| Failed | 12 |
| Bugs | 11 |
| Test tool used | Jira + Zephyr Scale |
| Test cycle | Version 1.0 (FBA-R1) |


## Scope

The following screens/flows were tested:
- **Select Flight** — trip type, destination selection, date selection, flight selection
- **Passenger Details** — passenger name input
- **Pay by Credit Card** — card type, card details, expiry, payment confirmation


## Key Findings

Testing uncovered several validation gaps in the booking flow — the application allows bookings to proceed with missing or logically invalid data (e.g. same origin/destination, past dates, no flight selected, no payment card type selected).

## Tools Used

- **Jira + Zephyr Scale** — test case management and execution tracking
- **Manual browser testing** — Chrome