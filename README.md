# java-consolidation-expansion




JVM  JVM内存结构、Java内存模型、垃圾回收、JVM参数及调优、Java对象模型、HotSpot、类加载机制、虚拟机性能监控与故障处理工具

编译与反编译

Java基础知识  阅读源代码、Java中各种变量类型、熟悉Java String的使用，熟悉String的各种函数、自动拆装箱、熟悉Java中各种关键字、集合类、枚举、Java IO&Java NIO，并学会使用、Java反射与javassist、Java序列化、注解、JMS、JMX、泛型、单元测试、正则表达式、常用的Java工具库、什么是API&SPI、异常、时间处理、编码方式、语法糖、

Java并发编程   什么是线程，与进程的区别、阅读源代码，并学会使用、线程池、线程安全、锁、死锁、volatile、synchronized、sleep 和 wait、wait 和 notify、notify 和 notifyAll、ThreadLocal、写一个死锁的程序、写代码来解决生产者消费者问题、守护线程、守护线程和非守护线程的区别以及用法

Java底层知识    字节码、class文件格式、CPU缓存，L1，L2，L3和伪共享、尾递归、位运算

设计模式   了解23种设计模式、会使用常用设计模式、实现AOP、实现IOC、不用synchronized和lock，实现线程安全的单例模式、nio和reactor设计模式

网络编程    tcp、udp、http、https等常用协议、三次握手与四次关闭、流量控制和拥塞控制、OSI七层模型、tcp粘包与拆包、http/1.0 http/1.1 http/2之前的区别、Java RMI，Socket，HttpClient、cookie 与 session、用Java写一个简单的静态文件的HTTP服务器、了解nginx和apache服务器的特性并搭建一个对应的服务器、用Java实现FTP、SMTP协议、进程间通讯的方式、什么是CDN？如果实现？、什么是DNS？、反向代理、

框架知识    Servlet线程安全问题、Servlet中的filter和listener、Hibernate的缓存机制、Hibernate的懒加载、Spring Bean的初始化、Spring的AOP原理、自己实现Spring的IOC、Spring MVC、Spring Boot2.0、Spring Boot的starter原理，自己实现一个starter、Spring Security、

应用服务器    JBoss、tomcat、jetty、Weblogic

工具   git & svn、maven & gradle

jdk新特性   java7、java8、java9、java10、java11

性能优化   使用单例、使用Future模式、使用线程池、选择就绪、减少上下文切换、减少锁粒度、数据压缩、结果缓存

线上问题分析  dump获取（线程Dump、内存Dump、gc情况）、dump分析（分析死锁、分析内存泄露）、自己编写各种outofmemory，stackoverflow程序（HeapOutOfMemory、 Young OutOfMemory、MethodArea OutOfMemory、ConstantPool OutOfMemory、DirectMemory OutOfMemory、Stack OutOfMemory Stack OverFlow）、常见问题解决思路（内存溢出、线程死锁、类加载冲突）、使用工具尝试解决以下问题，并写下总结（当一个Java程序响应很慢时如何查找问题、当一个Java程序频繁FullGC时如何解决问题、如何查看垃圾回收日志、当一个Java应用发生OutOfMemory时该如何解决、如何判断是否出现死锁、如何判断是否存在内存泄露）

编译原理知识    编译与反编译、Java代码的编译与反编译、Java的反编译工具、词法分析，语法分析（LL算法，递归下降算法，LR算法），语义分析，运行时环境，中间代码，代码生成，代码优化

操作系统知识  Linux的常用命令、进程同步、缓冲区溢出、分段和分页、虚拟内存与主存

数据库知识   MySql 执行引擎、MySQL 执行计划、SQL优化、事务（事务的隔离级别、事务能不能实现锁的功能）、数据库锁（行锁、表锁、使用数据库锁实现乐观锁）、数据库主备搭建、binlog、内存数据库（h2）、常用的nosql数据库（redis、memcached、mongo）、分别使用数据库锁、NoSql实现分布式锁、性能调优

数据结构与算法知识   简单的数据结构（栈、队列、链表、数组、哈希表）、树（二叉树、字典树、平衡树、排序树、B树、B+树、R树、多路树、红黑树）、排序算法（各种排序算法和时间复杂度 深度优先和广度优先搜索 全排列、贪心算法、KMP算法、hash算法、海量数据处理）

大数据知识     Zookeeper（基本概念、常见用法）、Solr，Lucene，ElasticSearch、Storm，流式计算，了解Spark，S4、Hadoop，离线计算（HDFS、MapReduce）、分布式日志收集flume，kafka，logstash、数据挖掘，mahout

网络安全知识   什么是XSS（XSS的防御）、什么是CSRF、什么是注入攻击（SQL注入、XML注入、CRLF注入）、什么是文件上传漏洞、加密与解密（MD5，SHA1、DES、AES、RSA、DSA）、什么是DOS攻击和DDOS攻击（memcached为什么可以导致DDos攻击、什么是反射型DDoS）、SSL、TLS，HTTPS、如何通过Hash碰撞进行DOS攻击、用openssl签一个证书部署到apache或nginx

分布式（数据一致性、服务治理、服务降级）、分布式事务（2PC、3PC、CAP、BASE、 可靠消息最终一致性、最大努力通知、TCC）、Dubbo（服务注册、服务发现，服务治理）、分布式数据库（怎样打造一个分布式数据库、什么时候需要分布式数据库、mycat、otter、HBase）、分布式文件系统（mfs、fastdfs）、分布式缓存（缓存一致性、缓存命中率、缓存冗余）

微服务   ServiceMesh、Docker & Kubernets、Spring Boot、Spring Cloud

高并发   分库分表、CDN技术、消息队列

监控  监控什么（CPU、内存、磁盘I/O、网络I/O等）、监控手段（进程监控、语义监控、机器资源监控、数据波动）、监控数据采集（日志、埋点）、Dapper

负载均衡    tomcat负载均衡、Nginx负载均衡、DNS（DNS原理、DNS的设计）、CDN（数据一致性）

扩展      云计算（IaaS、SaaS、PaaS、虚拟化技术、openstack、Serverlsess）、搜索引擎（Solr、Lucene、Nutch、Elasticsearch）、区块链（哈希算法、Merkle树、公钥密码算法、共识算法、Raft协议、Paxos 算法与 Raft 算法、拜占庭问题与算法、消息认证码与数字签名）、比特币（挖矿、共识机制、闪电网络、侧链、热点问题、分叉）、以太坊（超级账本）


人工智能   数学基础、机器学习、人工神经网络、深度学习、应用场景、常用框架（TensorFlow、DeepLearning4J）

其他语言（Groovy、Python、Go、NodeJs、Swift、Rust）

书籍

面试