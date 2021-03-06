## 事务

---

### 事务特性

原子性、一致性、隔离性、持久性，这四个属性通常称为ACID特性。

* 原子性（atomicity）。一个事务是一个不可分割的工作单位，事务中包括的诸操作要么都做，要么都不做。
* 一致性（consistency）。事务必须是使数据库从一个一致性状态变到另一个一致性状态。一致性与原子性是密切相关的。
* 隔离性（isolation）。一个事务的执行不能被其他事务干扰。即一个事务内部的操作及使用的数据对并发的其他事务是隔离的，并发执行的各个事务之间不能互相干扰。
* 持久性（durability）。持久性也称永久性（permanence），指一个事务一旦提交，它对数据库中数据的改变就应该是永久性的。接下来的其他操作或故障不应该对其有任何影响。


### 分布式事务

* [分布式事务](分布式事务.md)
* [分布式系统常见的事务处理机制](https://mp.weixin.qq.com/s/ja0VRPkfHL9dtOP_PxwxKw)
* [微服务架构下处理分布式事务的典型方案](https://mp.weixin.qq.com/s/RKwvfKXIHrrkuCqOGZ4CPw)
* [解决分布式系统事务一致性的几种方案对比](https://mp.weixin.qq.com/s/kzmTKKH-t6tpJ97fa6TYPg)
* [多库多事务降低数据不一致概率](https://mp.weixin.qq.com/s/FvB-hOBT13SMfZko5iagAg)

#### 开源框架

* [tcc-transaction是TCC型事务java实现](https://github.com/changmingxie/tcc-transaction)
