我分析了上百份大中小厂的面经，整理了 Java 面试中最最最常问的一些问题！小伙伴们可以对照着这篇文章学习或者准备面试。内容会继续完善，欢迎你在评论区说出你遇到的高频面试题！
以下所有问题的答案可以参考（大部分都能找到）：[林老师带你学编程](https://www.wolzq.com)（「Java 学习+面试指南」一份涵盖大部分 Java 程序员所需要掌握的核心知识。准备 Java 面试，首选《[林老师带你学编程](https://www.wolzq.com)》！）。

⭐代表重要程度和必考程度，⭐越多代表越重要，越会被考官问到。
Java
Java基础  ⭐⭐⭐⭐
1. Java 中的几种基本数据类型是什么？对应的包装类型是什么？各自占用多少字节呢？
2. String、 StringBuffer 和 StringBuilder 的区别是什么? String 为什么是不可变的?
3. String s1 = new String("abc");这段代码创建了几个字符串对象？
4. == 与 equals?hashCode 与 equals ?
5. 包装类型的缓存机制了解么？
6. 自动装箱与拆箱了解吗？原理是什么？
7. 深拷贝和浅拷贝区别了解吗？什么是引用拷贝？
8. 谈谈对 Java 注解的理解，解决了什么问题？
9. Exception 和 Error 有什么区别？
10. Java 反射？反射有什么缺点？你是怎么理解反射的（为什么框架需要反射）？
11. Java 泛型了解么？什么是类型擦除？介绍一下常用的通配符？
12. 内部类了解吗？匿名内部类了解吗？
13. BIO,NIO,AIO 有什么区别?
参考答案：Java 基础常见面试题总结

Java 集合框架  ⭐⭐⭐
1. 说说 List,Set,Map 三者的区别？三者底层的数据结构？
2. 有哪些集合是线程不安全的？怎么解决呢？
3. 比较 HashSet、LinkedHashSet 和 TreeSet 三者的异同
4. HashMap 和 Hashtable 的区别？HashMap 和 HashSet 区别？HashMap 和 TreeMap 区别？
5. HashMap 的底层实现
6. HashMap 的长度为什么是 2 的幂次方
7. ConcurrentHashMap 和 Hashtable 的区别？
8. ConcurrentHashMap 线程安全的具体实现方式/底层具体实现
参考答案：Java 集合常见面试题总结

jvm ⭐⭐⭐⭐⭐
1. jvm 内存结构
2. jvm 调优参数
3. 什么是类加载？何时类加载？类加载流程？
4. 知道哪些类加载器。类加载器之间的关系？
5. 类加载器的双亲委派了解么？ 结合 Tomcat 说一下双亲委派（Tomcat 如何打破双亲委托机制？...）。
6. 为什么需要双亲委派
7. Java 内存模型
8. 栈中存放什么数据，堆中呢？
9. 大对象放在哪个内存区域
10. 堆区如何分类
11. 垃圾回收有哪些算法
12. GC 的全流程
13. GC 中老年代用什么回收方法？
参考答案：Java JVM常见面试题

多线程 ⭐⭐⭐
1. 线程和进程的区别。
2. 什么是上下文切换?
3. 什么是线程死锁?如何避免死锁?
4. 乐观锁和悲观锁了解么？
5. 说说 sleep() 方法和 wait() 方法区别和共同点?
6. Java 线程池有哪些参数？阻塞队列有几种？拒绝策略有几种？新线程添加的流程?
7. 实现 Runnable 接口和 Callable 接口的区别。
8. 讲一下 JMM(Java 内存模型)。volatile 关键字解决了什么问题？说说 synchronized 关键字和 volatile 关键字的区别。
9. AQS 原理了解么？AQS 组件有哪些？
10. 用过 CountDownLatch 么？什么场景下用的？
参考答案：Java 并发常见面试题总结

Java IO ⭐⭐
1.什么是IO流?
2.java中有几种类型的流?
3.字节流和字符流哪个好?怎么选择?
4.读取数据量大的文件时，速度会很慢，如何选择流?
5. IO模型有几种?
6.阻塞IO和非阻塞型IO的区别是什么？
参考答案：Java IO常见面试题总结

异常/反射 ⭐⭐
1.error和exception有什么区别?
2.说出5个常见的RuntimeException?
3.throw和throws的区别?
4.Java中异常分类有哪些？
5.如何自定义异常？
6.Java中异常处理要怎么处理？
参考答案：Java异常/反射常见面试题总结

常见框架
Spring ⭐⭐⭐⭐⭐
1. 什么是 Spring 框架?
2. 列举一些重要的 Spring 模块？
3. 谈谈自己对于 Spring IoC 和 AOP 的理解
4. Spring Bean 的生命周期说一下
5. Spring 中的 bean 的作用域有哪些?
6. 拦截器和过滤器了解么？
7. Spring 动态代理默认用哪一种
参考答案：Spring 常见面试题总结

Mybatis ⭐⭐⭐⭐
1.Mybatis优点?
2.Mybatis缺点?
3.什么时候用Mybatis?
4.Mybatis的核心组件有哪些?分别是?
5.#{}和${}的区别是什么?
6.Mybatis中9个动态标签是?
参考答案：Mybatis常见面试题总结


SpringMVC ⭐⭐⭐
1、什么是 SpringMVC？
2 、Spring MVC 的优点有哪些？
3 、SpringMVC 工作原理？
4 、SpringMVC 流程是什么？
6 、SpringMvc 的控制器是不是单例模式,如果是,有什么问题,怎么解决？
参考答案：SpringMVC常见面试题总结

SpringBoot ⭐⭐⭐⭐
1.什么是SpringBoot?
2.SpringBoot的特征?
3.如何快速构建一个SpringBoot项目?
4.SpringBoot启动类注解?它是由哪些注解组成?
5.什么是yaml?
6.SpringBoot支持配置文件的格式?
参考答案：SpringBoot常见面试题总结

SpringCloud ⭐⭐⭐
1.什么是SpringCloud?
2.什么是微服务?
3.SpringCloud有哪些特征?
4.SpringCloud核心组件?
5.SpringCloud基于什么协议?
6.SpringCloud和Dubbo区别?
参考答案：SpringCloud常见面试题总结

Netty ⭐
1. BIO,NIO 和 AIO 有啥区别？
2. Netty 是什么？为啥不直接用 NIO 呢?
3. 为什么要用 Netty？Netty 应用场景了解么？
4. 介绍一下 Netty 的核心组件？
5. Bootstrap 和 ServerBootstrap 了解么？
6. NioEventLoopGroup 默认的构造函数会起多少线程？
7. Netty 线程模型了解么？
8. 什么是 TCP 粘包/拆包?有什么解决办法呢？
9. Netty 长连接、心跳机制了解么？
参考答案：Netty 常见面试题总结

权限认证 ⭐⭐⭐
1. 认证 (Authentication) 和授权 (Authorization)的区别是什么？
2. 什么是 Cookie ? Cookie 的作用是什么?如何在服务端使用 Cookie ?
3. Cookie 和 Session 有什么区别？如何使用 Session 进行身份验证？
4. 如果没有 Cookie 的话 Session 还能用吗？
5. 为什么 Cookie 无法防止 CSRF 攻击，而 token 可以？
6. 什么是 Token?什么是 JWT?如何基于 Token 进行身份验证？
7. 什么是 OAuth 2.0？
8. 什么是 SSO(单点登录)？
参考答案：权限认证常见面试题

数据库
MySQL ⭐⭐⭐⭐⭐
基础
1. 非关系型数据库和关系型数据库的区别？
2. 事务的四大特性了解么?
3. MySQL 事务隔离级别？默认是什么级别？
4. 乐观锁与悲观锁的区别?
5. MySQL 数据库两种存储引擎的区别?
索引
1. 为什么索引能提高查询速度?
2. 聚集索引和非聚集索引的区别？非聚集索引一定回表查询吗?
3. 索引这么多优点，为什么不对表中的每一个列创建一个索引呢？(使用索引一定能提高查询性能吗?)
4. 索引底层的数据结构了解么？Hash 索引和 B+树索引优劣分析
5. B+树做索引比红黑树好在哪里？
6. 最左前缀匹配原则了解么？
7. 什么是覆盖索引
进阶
1. 一条 SQL 语句在 MySQL 中如何执行的？
2. explain 命令了解么？
3. 简单说一下 SQL 调优思路。
4. 简单说一下大表优化的思路。
5. 分库分表了解么？为什么要分库分表？有哪些常见的分库分表工具(sharding-jdbc、TSharding、MyCAT...)？
参考答案：MySQ 常见面试题总结

Redis ⭐⭐⭐⭐
1. 分布式缓存常见的技术选型方案有哪些？说一下 Redis 和 Memcached 的区别和共同点
2. 说一下有缓存情况下查询数据和修改数据的流程。
3. Redis 有哪些数据结构？SDS 了解么？
4. Redis 内存满了怎么办？
5. Redis 内存淘汰算法除了 LRU 还有哪些？
6. Redis 给缓存数据设置过期时间有啥用？ Redis 是如何判断数据是否过期的呢？
7. Redis 事务了解么？(Redis 可以通过 MULTI，EXEC，DISCARD 和 WATCH 等命令来实现事务功能)
8. 缓存穿透和缓存雪崩问题了解么？有哪些解决办法？
9. 如何基于 Redis 实现分布式锁？
参考答案：Redis 常见面试题总结

Elasticsearch ⭐⭐
1. 解释一下 Elasticsearch 集群中的索引的概念?
2. 解释一下 Elasticsearch 集群中的Type 的概念?
3. 你能否在 Elasticsearch 中定义映射?
4. Elasticsearch 的文档是什么?
5. 解释一下 Elasticsearch 的分片?
6. 定义副本、创建副本的好处是什么?
7. 请解释在 Elasticsearch 集群中添加或创建索引的过程?
8. 在 Elasticsearch  中删除索引的语法是什么?
参考答案：Elasticsearch常见面试题总结

MongoDB ⭐
1. 你说的 NoSQL 数据库是什么意思?NoSQL 与 RDBMS 直接有什么区别?为什么要使用和不使用 NoSQL 数据库?说一说 NoSQL 数据库的几个优点?
2. NoSQL 数据库有哪些类型?
3. MySQL 与 MongoDB 之间最基本的差别是什么?
4. 你怎么比较 MongoDB、CouchDB 及 CouchBase?
5. MongoDB 成为最好 NoSQL 数据库的原因是什么?
6.32 位系统上有什么细微差别?
7. journal 回放在条目(entry)不完整时(比如恰巧有一个中途故障了)会遇到问题吗?
8. 分析器在 MongoDB 中的作用是什么?
9. 名字空间(namespace)是什么?
参考答案：MongoDB常见面试题总结

分布式
RPC 基础 ⭐
1. 了解 RPC 吗？有哪些常见的 RPC 框架？
2. 如果让你自己设计 RPC 框架你会如何设计？
3. 服务之间的调用为啥不直接用 HTTP 而用 RPC？
参考答案：RPC 基础常见面试题总结

Dubbo ⭐⭐
1. Dubbo 了解吗？
2. Dubbo 的工作原理了解么？注册中心扮演了什么角色？注册中心挂了可以继续通信吗？
3. Dubbo 的负载均衡策略了解么？
4. Dubbo 的 spi 机制了解么？带来了啥好处？
参考答案：Dubbo 常见面试题总结

网络 ⭐⭐
1. OSI 与 TCP/IP 各层的结构与功能,都有哪些协议?为什么网络要分层？
2. 计算机网络的一些常见状态码
3. ping 所使用的协议
4. TCP 的三次握手与四次挥手的内容？ TCP 为什么连接是三次握手而断开是四次握手？
5. TCP 与 UDP 的区别及使用场景
6. TCP 是如何保证传输的可靠性？
7. 一次完整的 HTTP 请求所经的步骤
8. HTTP 协议了解么？HTTP 是基于 TCP 还是 UDP 的？
9. HTTP 报文的内容简单说一下！ HTTP 请求报文和响应报文中有哪些数据？
10. HTTP 和 HTTPS 的区别了解么？
11. HTTP 请求有哪些常见的状态码？
12. HTTP 长连接和短连接了解么？
13. Cookie 和 Session 的关系
14. URI 和 URL 的区别是什么?
参考答案：计算机网络常见面试题总结

操作系统 ⭐⭐
- 进程和线程的区别
- 进程有哪几种状态?
- 进程间的通信方式
- 线程间的同步的方式
- 进程的调度算法
- 什么是死锁？死锁的四个必要条件，解决死锁的方法
- 常见的内存管理机制，快表和多级页表
- 分页机制和分段机制的共同点和区别
- CPU 寻址了解吗?为什么需要虚拟地址空间?
- 虚拟内存(Virtual Memory)
- 页面置换算法
参考答案：操作系统常见面试题总结

算法和数据结构
算法 ⭐⭐⭐⭐
1. LRU 算法了解吗？你能实现一个吗？
2. 写排序算法（快排、堆排）
3. 使用数组实现一个栈
4. 使用数组实现一个队列
5. 实现一个链表、反转链表、
参考答案：算法常见面试题总结

数据结构 ⭐⭐⭐⭐
1. 数组 vs 链表
2. 栈的应用场景
3. 队列的分类、应用场景
4. 红黑树的特点、红黑树 vs 二叉查找树
5. 哈希表、哈希表应用场景
6. 布隆过滤器了解吗？
参考答案：数据结构常见面试题总结

系统设计
设计模式 ⭐⭐⭐
1. 何为设计模式？有哪些常见的设计模式？
2. 单例模式了解么？说一下单例模式的使用场景。手写一个单例模式的实现。
3. 观察者模式了解么？说一下观察者模式的使用场景。
4. 工厂模式了解么？说一下工厂模式的使用场景。
5. 责任链模式了解么？哪些开源项目（Netty、MyBatis ...）中用到了责任链模式？怎么用的？
6. SOLID 原则了解么？简单谈谈自己对于单一职责原则和开闭原则的理解。
7. 阅读 Spring 源码的时候什么设计模式最让你印象深刻？能简单讲讲吗？
参考答案：设计模式常见面试题总结

分布式 ID ⭐⭐⭐
1. 何为 ID？
2. 何为分布式 ID？
3. 一个合格的分布式 ID 需要满足什么要求?
4. 分布式 ID 常见的生成方法有哪些？（数据库主键自增、数据库的号段模式、UUID、SNOWFLAKE 等等）
参考答案：分布式 ID 常见面试题总结

分布式锁 ⭐⭐⭐⭐
基于 Redis 实现分布式锁：
- 如何基于 Redis 实现一个最简易的分布式锁？
- 为什么要给锁设置一个过期时间？
- 如何实现锁的优雅续期？
- 如何实现可重入锁？
- Redis 如何解决集群情况下分布式锁的可靠性？
基于 ZooKeeper 实现分布式锁：
- 如何基于 ZooKeeper 实现分布式锁？
- 为什么要用临时顺序节点？
- 为什么要设置对前一个节点的监听？
- 如何实现可重入锁？
参考答案：分布式锁常见面试题总结

消息队列
消息队列 ⭐⭐⭐
1. 为什么要用消息队列?
2. 对比一下常见的消息队列?
3. 如何保证消息不被重复消费?
4. 如何保证消息消费的顺序性?
参考答案：消息队列常见面试题总结

Kafka ⭐⭐
1.什么是kafka?
2.kafka 的3个关键功能?
3.kafka通常用于两大类应用?
4.kafka特性有哪些?
5.kafka 的5个核心Api?
6.什么是Broker  (代理)  ?
7.什么是Producer  (生产者)  ?
参考答案：Kafka常见面试题总结

中间件
Tomcat ⭐⭐
1.你怎样给 tomcat 去调优?
2. 如何禁用 DNS 查询？
3. 怎么调整线程数？
4. 如何加大 tomcat 连接数？
5. tomcat 中如何禁止列目录下的文件？
6.怎样加大 tomcat 的内存。
参考答案：Tomcat 常见面试题总结

Nginx ⭐
1.什么是nginx?
2.nginx主要特征?
3.nginx 常用命令?
4.工作模式及连接数上限?
5.nginx负载均衡几种算法?
参考答案：Nginx常见面试题总结

Zookeeper ⭐⭐⭐
1. ZooKeeper 是什么？
2. Zookeeper 都有哪些功能？
3. 说说Zookeeper 的文件系统有哪些功能
4. Zookeeper 怎么保证主从节点的状态同步？
5. zookeeper 是如何保证事务的顺序一致性的？
6. 分布式集群中为什么会有 Master主节点？
7. zk 节点宕机如何处理？
参考答案：Zookeeper 常见面试题总结

软技能 
软技能为主观题，分为：做事方法、学习能力、沟通协作等维度，没有非常标准的答案，大家可以根据问题，进行思考自己要如何回答会比较得当，提前做好相关的准备。
做事方法方式考核题 ⭐⭐⭐
1. 开发过程中，发现自己负责任务有延期的迹象，你要如何处理？
2. 开发过程中，一个bug一直解决不了，没有任何头绪，此时要如何处理？
3. 同事找你咨询问题，但是你目前比较忙，这个时候你要怎么办？
4. 如果到测试阶段才发现，自己理解的需求和PM（产品经理）要求不一致，这个时候你该怎么办？
5. 多个版本迭代过来的需求非常多，但是工期又比较赶，这个时候你要如何去协调处理？
6. 后端对接过程中，如果前端要求数据处理让后端来处理，但是后端处理又很麻烦，这个时候你作为后端开发要怎么处理？
7. 领导安排的任务，你接手后感觉很困难，很难理解项目流程，无法进行后续需求开发，这个时候你要怎么处理？
8. 接到一个开发需求任务，你会做哪些事情，来去保质保量的完成？
9. 如果跟你配合的同事请假或者其它事项，导致你的任务也会一起延期，这个时候你会怎么做？
10. 提交代码阶段，不小心将别人的代码覆盖了，这个时候你会怎么处理？

学习能力考核题 ⭐⭐⭐
1. 你是通过哪些方式来提升你的专业技能的？
1. 新项目中包含很多你不了解的技术，这个时候你应该如何快速掌握他们？
1. 对于现有项目的技术痛点，比如页面代码重复，没有通用为组件 ，你会做哪些事情来完善优化它？
1. 开发过程中，遇到一个bug，你会通过哪些方式来寻找bug的解决方案？
1. 如果安排你进行一个代码重构任务，在保持功能不变的情况下，提高执行速度，你打算如何实施？

沟通协作能力考核题 ⭐⭐
1. 跟同事沟通反馈问题的时候，你会提供哪些要点？
2. 你认为项目的周报，要包含哪些要点，为什么要包含这些要点？
3. 跟同事沟通协调任务的时候，对方无法跟你达成一致，甚至反对影响到任务的时候，你会怎么处理？
4. 因为个人原因导致任务延期了，你打算跟领导如何解释说明？
5. 跟前端对接过程中，你提出的需求前端一直理解不了，你解释多遍都没有作用，这个时候你要怎么办？

经验总结
1. 学完了某个知识点之后，你可以去看看对应的八股文和知识点总结（https://www.wolzq.com/）。
2. 多面试，不要害怕失败，多总结经验。
3. 尽早准备，不论是找工作前、面试前还是面试后。
4. 如果是求职目标是中小厂、国企的话，算法相对来说不是那么重要。
5. 如果你的学历比较一般的话，格外注意要把重心放在自己的项目经历上。
6. 熟悉自己的简历。
7. 电话和视频面试很平常，面试前提前准备一下。
8. 复盘！！！不管是面试失败还是成功，都要养成复盘的好习惯。
