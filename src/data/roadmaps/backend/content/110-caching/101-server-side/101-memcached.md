# Memcached

Memcached (pronounced variously mem-cash-dee or mem-cashed) is a general-purpose distributed memory-caching system. It is often used to speed up dynamic database-driven websites by caching data and objects in RAM to reduce the number of times an external data source (such as a database or API) must be read. Memcached is free and open-source software, licensed under the Revised BSD license. Memcached runs on Unix-like operating systems (Linux and macOS) and on Microsoft Windows. It depends on the `libevent` library.

Memcached's APIs provide a very large hash table distributed across multiple machines. When the table is full, subsequent inserts cause older data to be purged in the least recently used (LRU) order. Applications using Memcached typically layer requests and additions into RAM before falling back on a slower backing store, such as a database.

Memcached has no internal mechanism to track misses which may happen. However, some third-party utilities provide this functionality.

Visit the following resources to learn more:

- [Memcached, From Wikipedia](https://en.wikipedia.org/wiki/Memcached)
- [Memcached, From Official Github](https://github.com/memcached/memcached#readme)
- [Memcached Tutorial](https://www.tutorialspoint.com/memcached/index.htm)
