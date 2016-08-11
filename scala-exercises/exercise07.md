# Exercise 7

## Introduce recurring train schedules

So far, we've assumed train schedules are the same every day of the year.
We're about to refine our data model to chage that.

We should be able to define trips that run recurrently on certain days of the week.

For example, we may want to support:

- Train 1 runs its route every Monday and Wednesday
- Train 2 runs every day of the week
- Train 3 runs only on the weekends

Update the `connections` methods to include a day of the week, so the search only uses trains
that run on that day.

HINT: To avoid too much re-factoring of your tests, consider creating an "All Week" and 
"Weekend Only" schedule for the two trains added to `TestData.planner`.  Use a weekend
day when updating the existing `connections` method calls.