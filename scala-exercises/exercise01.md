# Exercise 1

## Calculate the hops between each station in a Train's path

A `Train` has a `schedule` which contains each `(Time, Station)` pair in the `Train`'s path.
As a pre-requisite to finding paths between two stations we need to create a new datastructure, `Hop`,
that contains two stations that a `Train` will visit and the direction in which they're visited: a `Train`
departs `from` a station and arrives `to` another station.

A `Hop` can be thought of as an edge between two vertices in a graph.  In other words, a train connection
from one station to another.

1.  On trains, calculate the back-to-back stations. Ex: `((a,b), (b,c), (c,d))`.
2.  Model each station-station edge as a `Hop` case class, with `from` and `to` stations,
    and the respective `Train`.
3.  On the `Hop` class, ensure that the `from` and `to` stations are included in the train schedule.
    This prevents data inconsistencies.
4.  On the `Hop` class, calculate departure and arrival time.
    Remember trains spend zero time on each station, so the arrival time of `Train` A to `Station` 1
    is the same as the departure `Time` of the following `Hop`.