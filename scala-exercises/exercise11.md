# Exercise 11

## Find sink stations: stations with no departures

Our users have heard urban myths that on certain days of the year, there are stations you can
get to but not leave from.

These sink stations are probably scheduling errors - there should not be any stations without
departures at some point in the day.

Implement a way to check for these sink stations, given a date (full with day, month and year)
The output should be the `Set[Station]` that have arrivals but no departures on that date.
