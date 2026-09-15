# Select Flight — Test Scenarios

## Valid Scenarios (FBA-T1 – FBA-T6)

| Key | Test Scenario |
|---|---|
| FBA-T1 | Validate booking "Return" trip type |
| FBA-T2 | Validate booking "One way" trip type |
| FBA-T3 | Validate booking a flight with the same departure and return date |
| FBA-T4 | Validate one-way trip with today's date |
| FBA-T5 | Validate that default trip type is "Return" |
| FBA-T6 | Validate that selecting a new flight deselects the previously selected one |

## Invalid Scenarios (FBA-T7 – FBA-T14)

| Key | Test Scenario |
|---|---|
| FBA-T7 | Validate that booking is not allowed when return date is before departure date |
| FBA-T8 | Validate that booking is not allowed when "From" field is left unselected |
| FBA-T9 | Validate that booking is not allowed when "To" field is left unselected |
| FBA-T10 | Validate that booking is not allowed when From and To destinations are the same |
| FBA-T11 | Validate that booking is not allowed when the departure date is in the past |
| FBA-T12 | Validate that booking is not allowed when the return date is in the past |
| FBA-T13 | Validate that return date field is hidden/disabled when "One way" is selected |
| FBA-T14 | Validate that booking is not allowed when no flight is selected before clicking Continue |

---

# Passenger Details — Test Scenarios

## Valid Scenarios (FBA-T16)

| Key | Test Scenario |
|---|---|
| FBA-T16 | Validate providing valid information for passenger details |

## Invalid Scenarios (FBA-T17 – FBA-T18)

| Key | Test Scenario |
|---|---|
| FBA-T17 | Validate providing invalid information such as very long names or numbers in text fields |
| FBA-T18 | Validate error when required fields are left empty |

---

# Payment — Test Scenarios

## Valid Scenarios (FBA-T19, FBA-T29)

| Key | Test Scenario |
|---|---|
| FBA-T19 | Validate payment with Visa and Master card |
| FBA-T29 | Validate that user can go back after payment to book a new flight |

## Invalid Scenarios (FBA-T20, FBA-T24, FBA-T27, FBA-T28)

| Key | Test Scenario |
|---|---|
| FBA-T20 | Validate that payment is not allowed when no card type (Visa/Master) is selected |
| FBA-T24 | Validate that payment is not allowed when card number contains letters or special characters |
| FBA-T27 | Validate that payment is not allowed when expiry month/year is left unselected |
| FBA-T28 | Validate that payment is not allowed on double-clicking the "Pay now" button |