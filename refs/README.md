# References

## Prerequisites
- [mongodb.com](https://www.mongodb.com/)
  - Join [MongoDB Developer Community](https://www.mongodb.com/community/forums/)

## Basics
- [MongoDB University: Learning Path for MongoDB Developers](https://university.mongodb.com/learning_paths/developer)
- [MongoDB Documentation](https://www.mongodb.com/docs/)
  - [CRUD](https://www.mongodb.com/docs/manual/crud/)
  - [Replication](https://www.mongodb.com/docs/manual/replication/)
  - [Sharding](https://www.mongodb.com/docs/manual/sharding/)
  - [Causal Consistency](https://www.mongodb.com/docs/manual/core/causal-consistency-read-write-concerns/)
  - [Transactions](https://www.mongodb.com/docs/manual/core/transactions/)
- [MongoDB Specifications](https://github.com/mongodb/specifications)
  - [CRUD](https://github.com/mongodb/specifications/blob/master/source/crud/crud.rst)
  - [Causal Consistency](https://github.com/mongodb/specifications/blob/master/source/causal-consistency/causal-consistency.rst)
  - [Transactions](https://github.com/mongodb/specifications/blob/master/source/transactions/transactions.rst)

## Causal Consistency
- [Clock:CACM1978](CACM1978%20Time%20Clocks%20and%20the%20Ordering%20of%20Events%20in%20a%20Distributed%20System.pdf)
  - 看到 P562 左栏
- [CM:DC1995](DC1995%20Causal%20Memory%20Definitions%20Implementation%20and%20Programming.pdf)
  - 看到 Section 5 (证明部分可以暂时不看)
- [HLC:OPODIS2014](OPODIS2014%20Logical%20Physical%20Clocks.pdf)
  - 看到 Section 3

## Protocols (In this Order)
- [MongoDB-CC:SIGMOD2019](./SIGMOD2019%20Implementation%20of%20Cluster-wide%20Logical%20Clock%20and%20Causal%20Consistency%20in%20MongoDB.pdf)
  - 全文阅读, 重点在 Section 4, Section 5, Appendix A1, Appendix A2
  - [SIGMOD2019 Video](https://www.bilibili.com/video/BV1JY4y1e7bw?share_source=copy_web)
  - [MongoDB Presentation Video](https://www.mongodb.com/presentations/implementation-of-cluster-wide-causal-consistency-in-mongodb)
- [MongoDB-CMv:SRDS2020](./SRDS2020%20A%20Generic%20Specification%20Framework%20for%20Weakly%20Consistent%20Systems.pdf)
  - 只需看 Section V.A 与 V.B
  - [SRDS2020 Presentation Video](https://www.bilibili.com/video/BV1LF411G7ip?share_source=copy_web)
    - From 16:45
- [MongoDB-TC:VLDB2019](./VLDB2019%20Tunable%20Consistency%20in%20MongoDB.pdf)
  - 全文阅读, 重点在前 7 节
  - [MonogDB Presentation Video](https://www.bilibili.com/video/BV13p4y1z7mn?share_source=copy_web)
- [VerifyMongoDBTX2022](https://arxiv.org/abs/2111.14946)
  - 全文阅读
  - [MongoDB数据一致性协议的规约与测试](https://www.bilibili.com/video/BV1Zq4y1F78g?share_source=copy_web)

## Advanced
- [Source Code Learning](https://github.com/mongodb/mongo)
  - [y123456yz / reading-and-annotate-mongodb-3.6](https://github.com/y123456yz/reading-and-annotate-mongodb-3.6)
  - [y123456yz / reading-and-annotate-mongodb-4.4](https://github.com/y123456yz/reading-and-annotate-mongodb-4.4)
  - [Notes](https://github.com/Tsunaou/Papers-Reading-Notes/tree/master/Notes)

## Ultimate Goals
- To design and implement TCC in MongoDB

## Miscellaneous
- [Some Random Notes on MongoDB](https://github.com/hengxin/awesome-dbs/tree/master/MongoDB)