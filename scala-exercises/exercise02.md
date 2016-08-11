# Exercise 2

## Calculate all the connection paths between two stations

Given a Journey Planner, users want to know all the possible ways to get from `Station` A
to `Station` B, given a departure `Time`.

HINT: When writing tests for your connections evaluate [the collection-related Scala Test matchers](http://www.scalatest.org/user_guide/using_matchers#workingWithSequences)
at your disposal.  This could save you a lot of time when asserting the content of a collection type
(like a `Seq`, or a `Map` which is unordered.)

1.  In `JourneyPlanner`, calculate a map of `Station -> Set[Hop]` initialized with all hops of all
    trains, grouped by the `Hop`'s arrival station.
2.  In `JourneyPlanner`, add a method to calculate connections between two stations given a
    departure time.
    The return type should reflect the possibility of having more than one path between the two
    stations. All connections must have a train arrival time of equal to later than the given
    departure time