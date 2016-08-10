# Exercise 4

## Validate date

Validate the date provided to your application on the `/currency/:date` route.

The date should be an existing day between January 1st, 2000 and the current date.

Feel free to use `java.time.LocalDate` (Java 8's new Date types) or `org.joda.DateTime` for this.

If the date is invalid, you should return a 400 result indicating if the format was incorrect or the date was out of range.
      