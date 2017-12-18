
Distributed Key-Value Storage built on P2P protocol.

It is an eventually consistent key-value database that favours write availability. It’s a faithful implementation of Amazon’s Dynamo, with advanced features such as vector clocks for conflict resolution. JustinDB is also fault-tolerant. Servers can go up or down at any moment with no single point of failure.

Why akka

Its a toolkit and runtime for building highly concurrent applications which comes with ideas that have been around from some time - actor model. Besides that it has many welcome features around clustering:

load balancing
location transparency
self maintenance
fault tolerance


Authentication, authorization, validation

In case it's not obvious, Justin performs no authentication, authorization, or any validation of input data. Clients must implement those things themselves.
