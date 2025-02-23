# Deep Dive - Databases
## Databases
### Time-Series Databases
#### Gorilla
**Resources**
- [Gorilla: A Fast, Scalable, In-Memory Time Series Database](https://www.vldb.org/pvldb/vol8/p1816-teller.pdf)
### NoSQL Databases
#### Key-Value Stores
##### etcd

## Compaction Algorithms
### Gorilla's Compaction
**Resources**
- [The Morning Paper - Gorilla: A fast, scalable, in-memory time series database](https://blog.acolyer.org/2016/05/03/gorilla-a-fast-scalable-in-memory-time-series-database/)

**Implementation**
- [Github by keisku - Gorilla](https://github.com/keisku/gorilla/tree/main)
- [Github by ghilesmeddour - gorilla-time-series-compression](https://github.com/ghilesmeddour/gorilla-time-series-compression)
### Size-tiered Compaction Strategy (STCS)
### Leveled Compaction Strategy (LCS)
**Resources**
- [Github - Leveled Compaction](https://github.com/facebook/rocksdb/wiki/Leveled-Compaction)
- [ScyllaDB’s Compaction Strategies Series: Write Amplification in Leveled Compaction](https://www.scylladb.com/2018/01/31/compaction-series-leveled-compaction/)
- [DataStax- Leveled Compaction in Apache Cassandra](https://www.datastax.com/blog/leveled-compaction-apache-cassandra)
- [Compactions in Apache Cassandra - Performance Analysis of Compaction Strategies in Apache Cassandra](https://www.diva-portal.org/smash/get/diva2:948190/FULLTEXT02)
### Incremental Compaction Strategy (ICS)
### Time-Window Compaction Strategy (TWCS)

## Consensus Algorithms
### Raft
**Resources**
- [The Raft Consensus Algorithm](https://raft.github.io/)

**Use Cases**
- [Scylla - Raft Consensus Algorithm in ScyllaDB](https://opensource.docs.scylladb.com/stable/architecture/raft.html)
- [Scylla - Achieving NoSQL Database Consistency with Raft in ScyllaDB](https://www.scylladb.com/tech-talk/achieving-nosql-database-consistency-with-raft-in-scylla/)
- [etcd - Persistent Storage Files](https://etcd.io/docs/v3.5/learning/persistent-storage-files/)
- [NATS - JetStream Clustering](https://docs.nats.io/running-a-nats-service/configuration/clustering/jetstream_clustering)
