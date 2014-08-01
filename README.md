cassandra-bloom-filter
======================

This is a Bloom Filter implementation extracted from Apache Cassandra. It comes with unit test code as well. I made the following changes:

- Take off the serialization part. 
- Use OpenBitSet only, skip OffHeapBitSet.
