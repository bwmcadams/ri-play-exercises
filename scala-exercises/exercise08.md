# Exercise 8

## Implement schedule exceptions

Schedules should also allow for exception dates.

For example, Train 1 runs every Monday and Wednesday, except for the following dates:

- January 1st
- December 25th
- December 31st

Exceptions will be used to represent such things as holidays, days off and days in which a
specific train will be on maintenance.

HINT: Consider updating all your tests calls to `connections` with a date that does not 
overlap with schedule exceptions or day of week restrictions for any of your trains.  This will
reduce the number of changes you need to make to your test logic as it did with Exercise 7. 