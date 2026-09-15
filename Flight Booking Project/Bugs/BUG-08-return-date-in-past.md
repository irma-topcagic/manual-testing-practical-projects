# Booking proceeds without validation when return date is in the past

**Related Jira issue:** FBA-8

**Priority:** Medium

## Steps to reproduce
1. Navigate to [Agile Travel](http://travel.agileway.net/flights/start)
2. Select Return trip, From: San Francisco, To: New York
3. Departing: valid future date
4. Returning: past date
5. Select a flight, click Continue

## Expected
Validation error preventing booking (past return date)

## Actual
No error shown, booking proceeds

## Severity
Medium

