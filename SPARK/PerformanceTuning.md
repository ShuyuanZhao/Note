# Introduction

Apache Spark 具有内存计算的特性。因此，群集中的资源（CPU，内存等）可能会成为瓶颈。

合理的优化方法可使：

- Ensure proper use of all resources in an effective manner.
- Eliminates those jobs that run long.
- Improves the performance time of the system.
Guarantees that jobs are on correct execution engine.


## Data Serialization
为了减少内存，RDD可以序列化形式存储。合理的序列化方式可以提高网络传输效果并减少内存存储。

## Memory Tuning
Consider the following three things in tuning memory usage:

- Amount of memory used by objects (the entire dataset should fit in-memory)
- The cost of accessing those objects
- Overhead of garbage collection.

## Memory Management
Consider Spark memory management under two categories: execution and storage.

## Other consideration


## Spark Conf 设置

[官方参数文档](https://spark.apache.org/docs/latest/configuration.html)



## Conclusion




### 参考
[1] https://data-flair.training/blogs/apache-spark-performance-tuning/
