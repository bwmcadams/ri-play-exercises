# Exercise 3

## Ensure that all connections are valid

Our `Train` system has a number of properties that we need to ensure within our solution: trains can
only travel one way, connections are time-based, etc.  In this exercise we will implement these
properties to ensure that all the connections available to the user are valid.

Don't forget to write tests to validate each property.

1.  Ensure that the path starts no earlier than the indicated departure time.
2.  Ensure no impossible connections are used: arrival time should be earlier than or equal to
    departure time for every station.
3.  Don't allow cycles in the paths. An individual train will never visit the same station twice,
    but the train system may have cycles due to users changing trains mid-journey.