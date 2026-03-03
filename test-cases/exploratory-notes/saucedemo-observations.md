# SauceDemo - Login Validation Observations

## Observation 1: Validation Icons on Both Fields

When submitting the login form with only one field empty:

- Error message correctly specifies the missing field (Username or Password)
- Red underline highlights the specific field related to the error
- However, X icons appear next to both username and password fields regardless of which field fails validation

### Notes:
This behavior may cause minor user confusion, as both fields visually appear invalid even when only one is missing input.
