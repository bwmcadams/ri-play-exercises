# Exercise 10

## The price of the train should vary based on the current date

Use your current pricing implementation as the base, and modify the price based on the
following rules:

- If the date being booked is more than 2 weeks away, keep the price as is.
- If the date booked is less than 2 weeks but more than 1 day away, the price should rise to 150%.
- If the date is 1 day away then we provide a last minute discount of 25%
