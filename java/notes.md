# Notes

## Stream exception handling

> https://dzone.com/articles/exception-handling-in-java-streams

## Java Thread Pool

> [Thread pool vs Fork-Joint pool](https://stackify.com/java-thread-pools/)

## Concurrency

- Multithreaded application must ensure a couple of rules for a consistent behavior:
  - Mutual Exclusion: only one thread executes a critical section at a time.
  - Visibility: changes made by one thread to the shared data, are visible to other threads to maintain data consistency
- `Synchronized` keyword provide both of the above properties.
- `Volatile` only ensure the visibility aspect of the data change.

## Java HashMap Implementation

- http://coding-geek.com/how-does-a-hashmap-work-in-java/

## Oracle Java SE Specifications

- https://docs.oracle.com/javase/specs/

## Direct memory access
- https://highlyscalable.wordpress.com/2012/02/02/direct-memory-access-in-java/