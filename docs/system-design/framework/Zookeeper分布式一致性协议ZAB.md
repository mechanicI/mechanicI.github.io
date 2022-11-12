- 整个Zookeeper就是一个多节点分布式一致性算法的实现，底层采用的实现协议是ZAB。
### ZAB协议介绍
- ZAB 协议全称：Zookeeper Atomic Broadcast（Zookeeper 原子广播协议）。
Zookeeper 是一个为分布式应用提供高效且可靠的分布式协调服务。在解决分布式一致性方面，Zookeeper 并没有使用 Paxos ，而是采用了 ZAB 协议，ZAB是Paxos算法的一种简化实现。
- ZAB 协议定义：ZAB 协议是为分布式协调服务 Zookeeper 专门设计的一种支持 崩溃恢复 和 原子广播 的协议。下面我们会重点讲这两个东西。
基于该协议，Zookeeper 实现了一种 主备模式 的系统架构来保持集群中各个副本之间数据一致性。
