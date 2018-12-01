# CAPBASETree
CAP, BASE理论

<pre>
CAP理论
      CAP原则又称为CAP定理，指的是，在一个分布式系统中，Consistency(一致性)， Availability(可用性)，
      Partion tolerance(分区容错性)，三者不可兼得。

      CAP原则是NOSQL数据库的基石。

      分布式系统的CAP理论，理论首先把分布式系统中的三个特性进行了如下归纳：
          1）一致性（Consistency):在分布式系统中的所有数据备份，在同一时刻是否同样的值
          2）可用性(Avalibility)：在集群中一部分节点故障后，集群整体状态是否还能响应客户端的读写请求
          3）分区容忍性（Partion tolerance）:以实际效果而言，分区相当于对通信的时限要求。系统如果不能在
             时限内达成数据一致性，就意味着发生了分区情况，必须就当前操作在C和A之间做出选择。
</pre>

<pre>
BASE理论
      BASE是Basic Available（基本可用）,Soft state(软状态), Eventually consistent(最终一致性)三个短语
      的简写，BASE理论是对CAP中一致性和可用性权衡的结果，其来源于对大规模互联网系统分布式实践的杰伦，是基于
      CAP定理逐步演化而来的，其核心思想是即使无法做到强一致性，但每个应用都可根据自身的业务特点，采用适当的方
      式来使系统达到最终一致性。
</pre>