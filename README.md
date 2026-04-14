# Hi, I'm Ayush 👋

**Distributed Systems Researcher & Engineer** | PhD @ Sorbonne | Postdoc @ Télécom SudParis/INRIA

I build high-performance distributed databases, storage systems, and geo-replication infrastructure.

## 🔬 Current Work
- Postdoctoral researcher @ Télécom SudParis/INRIA  
- Building CRDT layer for serverless AI agent communication
- First-author publications: VLDB 2026 (under review), IPDPS 2025, PaPoC 2025

## 🚀 Featured Projects

### [GoBlocks](https://github.com/deadlockcharlie/GoBlocks) - Replicated Leaderless Block-Storage
A distributed block storage system built in Go with replication, inspired by concepts from GFS and Ceph. Implements consistent hashing, service discovery and dynamic membership

- 🛠️ **Tech:** Golang, Zookeeper


### [GRACE](https://github.com/deadlockcharlie/ReplicatedGDB) - Geo-Replicated Graph Database
Middleware achieving **100x lower write latency** than consensus-based geo-replication while preserving application invariants across heterogeneous backends (Neo4j, MemGraph, ArangoDB, MongoDB).

- 📄 **Paper:** Preprint
- 🛠️ **Tech:** TypeScript, Node.js, Docker, Yjs (CRDTs)
- 📊 **Benchmarked:** LDBC SNB, Freebase, 6 geo-distributed sites

### [CALock](https://github.com/deadlockcharlie/calock) - Hierarchical Locking Protocol
Novel concurrency control protocol achieving **4.5x performance improvement** for hierarchical data structures through optimal lock granularity identification.

- 📄 **Paper:** IPDPS 2025  
- 🛠️ **Tech:** C++, POSIX threads, formal verification
- ✅ **Proven:** Correctness, safety, liveness properties

### CobbleDB - LSM Tree Store
Educational Log-Structured Merge tree key-value store achieving performance **comparable to RocksDB in <3K lines** of code through modular, compositional design.

- 🛠️ **Tech:** Java, RocksDB APIs
- ✨ **Features:** Multi-level compaction, transactions, replaceable components

### [AntidoteDB Cache](https://github.com/deadlockcharlie/antidote)
In-memory cache and checkpoint store for AntidoteDB distributed database achieving **40% read performance improvement** with zero write overhead.

- 📄 **Report:** "Persisting the AntidoteDB Cache" (2022)
- 🛠️ **Tech:** Erlang, Riak, CRDTs

## 💻 Tech Stack
**Languages:** Java, C++, TypeScript, Python, Erlang/Elixir  
**Systems:** Docker, Kubernetes, distributed databases, CRDTs, consistency protocols  
**Databases:** Neo4j, PostgreSQL, MongoDB, RocksDB, Redis

## 📚 Recent Publications
- **PG-CRDT: Property Graph Replication** - Preprint
- **CALock: Multi-granularity locking** - IPDPS 2025
- **Local-First Property Graphs** - PaPoC @ EuroSys 2025

[Full publication list →](https://deadlockcharlie.com/publications)

## 📫 Connect With Me
- 🌐 Website: [deadlockcharlie.com](https://deadlockcharlie.com)
- 💼 LinkedIn: [linkedin.com/in/ayushpandey8439](https://linkedin.com/in/ayushpandey8439)
- 📧 Email: ayushpandey8439@gmail.com
- 🎓 Scholar: [Google Scholar](link-if-you-have-one)

---

💡 **Currently seeking:** Distributed systems engineering, database infrastructure, or research scientist roles

Particularly interested in: geo-replication, consistency protocols, CRDTs, distributed databases, AI agent infrastructure
