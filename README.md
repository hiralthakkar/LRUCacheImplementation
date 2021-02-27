# LRUCacheImplementation
Thread-safe LRU cache implementation

This implementation focuses on the cache being thread-safe using lock. There's also an event being triggered for least recently used item being evicted for the consumers to catch.

The tests include basic tests for add, delete or get operation and as well as multi-threaded tests.

Time taken to analyse and design the solution: 1 hour
Time taken to implement (inlcuding tests): 4 hours
