# Exercise 7

## Secure the currency and random pages

We want to restrict access to our currency advisor page. To do this, only allow requests that have a valid header with key `api-key` and a 32 char alphanumeric code as the value (any value, as long as it's 32 chars in length, and contains only numbers and letters a-z).

Use Play's built-in authentication trait `AuthenticatedBuilder`.

      