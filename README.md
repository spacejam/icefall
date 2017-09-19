# icefall :snowflake:

location-agnostic serverless and mobile database

it's hard to build systems that work well for both phones, which occasionally lose connectivity, and multi-datacenter stateful systems

icefall brings together reliable, strongly consistent databases with CRDT's and operational transform to maximize reliability, performance,
and allowing users to bend on consistency when desired.

over time, we see stateful systems struggle to handle the realities of users who want to access and create content at low latencies worldwide, 
sometimes while they are offline.

inspired by systems such as [antidote](http://syncfree.github.io/antidote/), [realm](https://github.com/realm/realm-core), and
the way real-world companies like facebook handle replication of relevant state to locations as close to the user as possible.
