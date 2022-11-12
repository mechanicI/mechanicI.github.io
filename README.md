


## mechanicI.github.io by munger
######             ***********不羡千金买歌舞，一篇珠玉是生涯***********
## 序言

### 介绍

*  **对于 Java 初学者来说：** 本文档倾向于提供一个比较详细的学习路径，对于Java整体的知识体系有一个初步认识。另外，本文的一些文章
也是学习和复习 Java 知识不错的实践；
*  **对于非 Java 初学者来说：** 本文档更适合回顾知识，准备面试，搞清面试应该把重心放在那些问题上。要搞清楚这个道理：提前知道那些面试常见，不是为了背下来应付面试，而是可以更有针对的学习重点。

Markdown 格式参考：[Github Markdown格式](https://guides.github.com/features/mastering-markdown/)，表情素材来自：[EMOJI CHEAT SHEET](https://www.webpagefx.com/tools/emoji-cheat-sheet/)。

利用 docsify 生成文档部署在 Github pages: [docsify 官网介绍](https://docsify.js.org/#/)

### 关于转载

如果需要转载本仓库的一些文章到自己的博客的话，记得注明原文地址就可以了。

### 为什么要做这个开源文档？

为什么要写这个博客呢？初始想法源于自己的个人那一段比较迷茫的学习经历。主要目的是为了通过这个开源平台来书写博客，整理收集面试过程出现过的问题，内容由其他[博客](https://github.com/Snailclimb/JavaGuide)https://github.com/Snailclimb/JavaGuide 
加上自己在工作中学习成果组成。


### 为什么要看源码：
- 提升技术功底：学习源码里的优秀设计思想，比如一些疑难问题的解决思路，还有一些优秀的设计模式，整体提升自己的技术功底
- 深度掌握技术框架：源码看多了，对于一个新技术或框架的掌握速度会有大幅提升，看下框架demo大致就能知道底层的实现，技术框架更新再快也不怕
- 快速定位线上问题：遇到线上问题，特别是框架源码里的问题(比如bug)，能够快速定位，这就是相比其他没看过源码的人的优势
- 对面试大有裨益：面试一线互联网公司对于框架技术一般都会问到源码级别的实现
- 知其然知其所以然：对技术有追求的人必做之事，使用了一个好的框架，很想知道底层是如何实现的
- 拥抱开源社区：参与到开源项目的研发，结识更多大牛，积累更多优质人脉

### 看源码方法：
- 先使用：先看官方文档快速掌握框架的基本使用
- 抓主线：找一个demo入手，顺藤摸瓜快速静态看一遍框架的主线源码，画出源码主流程图，切勿一开始就陷入源码的细枝末节，否则会把自己绕晕，凭经验猜
- 画图做笔记：总结框架的一些核心功能点，从这些功能点入手深入到源码的细节，边看源码边画源码走向图，并对关键源码的理解做笔记，把源码里的闪光点都记录下来，后续借鉴到工作项目中，理解能力强的可以直接看静态源码，也可以边看源码边debug源码执行过程，观察一些关键变量的值
- 整合总结：所有功能点的源码都分析完后，回到主流程图再梳理一遍，争取把自己画的所有图都在脑袋里做一个整合

## 目录

- [Java](#java)
    - [基础](#基础)
    - [容器](#容器)
    - [并发](#并发)
    - [JVM](#jvm)
    - [I/O](#io)
    - [Java 8](#java-8)
    - [编程规范](#编程规范)
- [网络](#网络)
- [操作系统](#操作系统)
    - [Linux相关](#linux相关)
- [数据结构与算法](#数据结构与算法)
    - [数据结构](#数据结构)
    - [算法](#算法)
- [数据库](#数据库)
    - [MySQL](#mysql)
    - [Redis](#redis)
- [系统设计](#系统设计)
    - [常用框架(Spring、Zookeeper ... )](#常用框架)
    - [权限认证](#权限认证)
    - [设计模式(工厂模式、单例模式 ... )](#设计模式)
    - [数据通信(消息队列、Dubbo ... )](#数据通信)
    - [网站架构](#网站架构)
- [面试指南](#面试指南)
    - [备战面试](#备战面试)
    - [常见面试题总结](#常见面试题总结)
    - [面经](#面经)
- [工具](#工具)
    - [Git](#git)
    - [Docker](#Docker)
- [资源](#资源)
    - [书单](#书单)
    - [实战项目推荐](#实战项目推荐)
    - [Github历史榜单](#Github历史榜单)
- [待办](#待办)


## Java

### 基础

* [Java 基础知识回顾](docs/java/Java基础知识.md)
* [Java 基础知识疑难点/易错点](docs/java/Java疑难点.md)
* [一些重要的Java程序设计题](docs/java/Java程序设计题.md)
* [J2EE 基础知识回顾](docs/java/J2EE基础知识.md)
* [jdk静态代理和动态代理和cglib动态代理](docs/java/静态代理和动态代理.md)

### 容器

* [Java容器常见面试题/知识点总结](docs/java/collection/Java集合框架常见面试题.md)
* [ArrayList 源码学习](docs/java/collection/ArrayList.md)  
* [LinkedList 源码学习](docs/java/collection/LinkedList.md)   
* [HashMap(JDK1.8)源码学习](docs/java/collection/HashMap.md)  

### 并发

* [Java 并发基础常见面试题总结](docs/java/Multithread/JavaConcurrencyBasicsCommonInterviewQuestionsSummary.md)
* [Java 并发进阶常见面试题总结](docs/java/Multithread/JavaConcurrencyAdvancedCommonInterviewQuestions.md)
* [并发容器总结](docs/java/Multithread/并发容器总结.md)
* [乐观锁与悲观锁](docs/essential-content-for-interview/面试必备之乐观锁与悲观锁.md)
* [JUC 中的 Atomic 原子类总结](docs/java/Multithread/Atomic.md)
* [AQS 原理以及 AQS 同步组件总结](docs/java/Multithread/AQS.md)

### JVM

* [一 Java内存区域](docs/java/jvm/Java内存区域.md)
* [二 JVM垃圾回收](docs/java/jvm/JVM垃圾回收.md)
* [三 JDK 监控和故障处理工具](docs/java/jvm/JDK监控和故障处理工具总结.md)
* [四 类文件结构](docs/java/jvm/类文件结构.md)
* [五 类加载过程](docs/java/jvm/类加载过程.md)
* [六 类加载器](docs/java/jvm/类加载器.md)

### I/O

* [BIO,NIO,AIO 总结 ](docs/java/BIO-NIO-AIO.md)
* [Java IO 与 NIO系列文章](docs/java/Java%20IO与NIO.md)
* [java序列化和反序列化](docs/java/java序列化和反序列化.md)

### Java 8 

* [Java 8 新特性总结](docs/java/What's%20New%20in%20JDK8/Java8Tutorial.md)
* [Java 8 学习资源推荐](docs/java/What's%20New%20in%20JDK8/Java8教程推荐.md)
* [Java8 forEach 指南](docs/java/What's%20New%20in%20JDK8/Java8foreach指南.md)

### 编程规范

- [Java 编程规范](docs/java/Java编程规范.md)

## Golang
### Golang学习
* [Golang学习](docs/golang/golang_learn_note.md)

## 网络

* [计算机网络常见面试题](docs/network/计算机网络.md)
* [计算机网络基础知识总结](docs/network/干货：计算机网络知识总结.md)
* [HTTPS中的TLS](docs/network/HTTPS中的TLS.md)

## 操作系统

### Linux相关

* [后端程序员必备的 Linux 基础知识](docs/operating-system/后端程序员必备的Linux基础知识.md)  
* [Shell 编程入门](docs/operating-system/Shell.md) 

## 数据结构与算法

### 数据结构

- [数据结构知识学习与面试](docs/dataStructures-algorithms/数据结构.md)

### 算法

- [算法学习资源推荐](docs/dataStructures-algorithms/算法学习资源推荐.md)  
- [几道常见的字符串算法题总结 ](docs/dataStructures-algorithms/几道常见的子符串算法题.md)
- [几道常见的链表算法题总结 ](docs/dataStructures-algorithms/几道常见的链表算法题.md)   
- [剑指offer部分编程题](docs/dataStructures-algorithms/剑指offer部分编程题.md)
- [公司真题](docs/dataStructures-algorithms/公司真题.md)
- [回溯算法经典案例之N皇后问题](docs/dataStructures-algorithms/Backtracking-NQueens.md)

## 数据库

### MySQL

* [MySQL 学习与面试](docs/database/MySQL.md)
* [一千行MySQL学习笔记](docs/database/一千行MySQL命令.md)
* [MySQL高性能优化规范建议](docs/database/MySQL高性能优化规范建议.md)
* [数据库索引总结](docs/database/MySQL%20Index.md)
* [事务隔离级别(图文详解)](docs/database/事务隔离级别(图文详解).md)
* [一条SQL语句在MySQL中如何执行的](docs/database/一条sql语句在mysql中如何执行的.md)
* [查询优化的Explain详解一](docs/database/查询优化的Explain详解一.md)
* [查询优化的Explain详解二](docs/database/查询优化的Explain详解二.md)

### Redis

* [Redis 总结](docs/database/Redis/Redis.md)
* [Redlock分布式锁](docs/database/Redis/Redlock分布式锁.md)
* [如何做可靠的分布式锁，Redlock真的可行么](docs/database/Redis/如何做可靠的分布式锁，Redlock真的可行么.md)

## 系统设计

### 常用框架

#### Spring

- [Spring 学习与面试](docs/system-design/framework/spring/Spring.md)
- [Spring 常见问题总结](docs/system-design/framework/spring/SpringInterviewQuestions.md)
- [Spring中bean的作用域与生命周期](docs/system-design/framework/spring/SpringBean.md)
- [SpringMVC 工作原理详解](docs/system-design/framework/spring/SpringMVC-Principle.md)
- [Spring中都用到了那些设计模式?](docs/system-design/framework/spring/Spring-Design-Patterns.md)
- [SpringBoot 使用指南](https://github.com/Snailclimb/springboot-guide)

#### ZooKeeper

- [ZooKeeper 相关概念总结](docs/system-design/framework/ZooKeeper.md)
- [ZooKeeper 数据模型和常见命令](docs/system-design/framework/ZooKeeper数据模型和常见命令.md)
- [Zookeeper分布式一致性协议ZAB](docs/system-design/framework/Zookeeper分布式一致性协议ZAB.md)

### 权限认证

- [权限认证基础:区分Authentication,Authorization以及Cookie、Session、Token](docs/system-design/authority-certification/basis-of-authority-certification.md)
- [适合初学者入门 Spring Security With JWT 的 Demo](https://github.com/Snailclimb/spring-security-jwt-guide)

### 设计模式

- [设计模式系列文章](docs/system-design/设计模式.md)

### 数据通信

- [数据通信(RESTful、RPC、消息队列)相关知识点总结](docs/system-design/data-communication/summary.md)
- [Dubbo 总结：关于 Dubbo 的重要知识点](docs/system-design/data-communication/dubbo.md)
- [消息队列总结](docs/system-design/data-communication/message-queue.md)
- [RabbitMQ 入门](docs/system-design/data-communication/rabbitmq.md)
- [RocketMQ的几个简单问题与答案](docs/system-design/data-communication/RocketMQ-Questions.md)
- [Kafka系统设计开篇-面试看这篇就够了](docs/system-design/data-communication/Kafka系统设计开篇-面试看这篇就够了.md)

### 网站架构

- [一文读懂分布式应该学什么](docs/system-design/website-architecture/分布式.md)
- [8 张图读懂大型网站技术架构](docs/system-design/website-architecture/8%20张图读懂大型网站技术架构.md)
- [【面试精选】关于大型网站系统架构你不得不懂的10个问题](docs/system-design/website-architecture/【面试精选】关于大型网站系统架构你不得不懂的10个问题.md)

## 面试指南

### 备战面试

* [【备战面试1】程序员的简历就该这样写](docs/essential-content-for-interview/PreparingForInterview/程序员的简历之道.md)
* [【备战面试2】初出茅庐的程序员该如何准备面试？](docs/essential-content-for-interview/PreparingForInterview/interviewPrepare.md)
* [【备战面试3】7个大部分程序员在面试前很关心的问题](docs/essential-content-for-interview/PreparingForInterview/JavaProgrammerNeedKnow.md)
* [【备战面试4】Github上开源的Java面试/学习相关的仓库推荐](docs/essential-content-for-interview/PreparingForInterview/JavaInterviewLibrary.md)
* [【备战面试5】如果面试官问你“你有什么问题问我吗？”时，你该如何回答](docs/essential-content-for-interview/PreparingForInterview/如果面试官问你“你有什么问题问我吗？”时，你该如何回答.md)
* [【备战面试6】美团面试常见问题总结（附详解答案）](docs/essential-content-for-interview/PreparingForInterview/美团面试常见问题总结.md)

### 常见面试题总结

* [第一周（2018-8-7）](docs/essential-content-for-interview/MostCommonJavaInterviewQuestions/第一周（2018-8-7）.md) (为什么 Java 中只有值传递、==与equals、 hashCode与equals)
* [第二周（2018-8-13）](docs/essential-content-for-interview/MostCommonJavaInterviewQuestions/第二周(2018-8-13).md)(String和StringBuffer、StringBuilder的区别是什么？String为什么是不可变的？、什么是反射机制？反射机制的应用场景有哪些？......)
* [第三周（2018-08-22）](docs/java/collection/Java集合框架常见面试题.md) （Arraylist 与 LinkedList 异同、ArrayList 与 Vector 区别、HashMap的底层实现、HashMap 和 Hashtable 的区别、HashMap 的长度为什么是2的幂次方、HashSet 和 HashMap 区别、ConcurrentHashMap 和 Hashtable 的区别、ConcurrentHashMap线程安全的具体实现方式/底层具体实现、集合框架底层数据结构总结）
* [第四周(2018-8-30).md](docs/essential-content-for-interview/MostCommonJavaInterviewQuestions/第四周(2018-8-30).md) （主要内容是几道面试常问的多线程基础题。）

### 面经

- [5面阿里,终获offer(2018年秋招)](docs/essential-content-for-interview/BATJrealInterviewExperience/5面阿里,终获offer.md)
- [蚂蚁金服2019实习生面经总结(已拿口头offer)](docs/essential-content-for-interview/BATJrealInterviewExperience/蚂蚁金服实习生面经总结(已拿口头offer).md)
- [2019年蚂蚁金服、头条、拼多多的面试总结](docs/essential-content-for-interview/BATJrealInterviewExperience/2019alipay-pinduoduo-toutiao.md)

## 工具

### Git

* [Git入门](docs/tools/Git.md)

### Docker

* [Docker 入门](docs/tools/Docker.md)
* [一文搞懂 Docker 镜像的常用操作！](docs/tools/Docker-Image.md)






## 资源

### 书单

- [Java程序员必备书单](docs/data/java-recommended-books.md)

### 实战项目推荐

- [onemall](https://github.com/YunaiV/onemall) : mall 商城，基于微服务的思想，构建在 B2C 电商场景下的项目实战。核心技术栈，是 Spring Boot + Dubbo 。未来，会重构成 Spring Cloud Alibaba 。

### Github榜单

- [Java 项目月榜单](docs/github-trending/JavaGithubTrending.md)

***

## 待办

- [ ] Java 多线程类别知识重构(正在进行中......)
- [ ] Netty 总结(正在进行中......)
- [ ] 数据结构总结重构(正在进行中......)



