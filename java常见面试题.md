J2SE基础：
1. 九种基本数据类型的大小，以及他们的封装类。
2. Switch能否用string做参数？
3. equals与==的区别。
4. Object有哪些公用方法？
5. Java的四种引用，强弱软虚，用到的场景。
6. Hashcode的作用。
7. ArrayList、LinkedList、Vector的区别。
8. String、StringBuffer与StringBuilder的区别。
9. Map、Set、List、Queue、Stack的特点与用法。
10. HashMap和HashTable的区别。
11. HashMap和ConcurrentHashMap的区别，HashMap的底层源码。
12. TreeMap、HashMap、LindedHashMap的区别。
13. Collection包结构，与Collections的区别。
14. try catch finally，try里有return，finally还执行么？
15. Excption与Error包结构。OOM你遇到过哪些情况，SOF你遇到过哪些情况。
16. Java面向对象的三个特征与含义。
17. Override和Overload的含义去区别。
18. Interface与abstract类的区别。
19. Static class 与non static class的区别。
20. java多态的实现原理。
21. 实现多线程的两种方法：Thread与Runable。
22. 线程同步的方法：sychronized、lock、reentrantLock等。
23. 锁的等级：方法锁、对象锁、类锁。
24. 写出生产者消费者模式。
25. ThreadLocal的设计理念与作用。
26. ThreadPool用法与优势。
27. Concurrent包里的其他东西：ArrayBlockingQueue、CountDownLatch等等。
28. wait()和sleep()的区别。
29. foreach与正常for循环效率对比。
30. Java IO与NIO。
31. 反射的作用于原理。
32. 泛型常用特点，List<String>能否转为List<Object>。
33. 解析XML的几种方式的原理与特点：DOM、SAX、PULL。
34. Java与C++对比。
35. Java1.7与1.8新特性。
36. 设计模式：单例、工厂、适配器、责任链、观察者等等。
37. JNI的使用。

JVM：
1. 内存模型以及分区，需要详细到每个区放什么。
2. 堆里面的分区：Eden，survival from to，老年代，各自的特点。
3. 对象创建方法，对象的内存分配，对象的访问定位。
4. GC的两种判定方法：引用计数与引用链。
5. GC的三种收集方法：标记清除、标记整理、复制算法的原理与特点，分别用在什么地方，如果让你优化收集方法，有什么思路？
6. GC收集器有哪些？CMS收集器与G1收集器的特点。
7. Minor GC与Full GC分别在什么时候发生？
8. 几种常用的内存调试工具：jmap、jstack、jconsole。
9. 类加载的五个过程：加载、验证、准备、解析、初始化。
10. 双亲委派模型：Bootstrap ClassLoader、Extension ClassLoader、ApplicationClassLoader。
11. 分派：静态分派与动态分派。

总体来说java考察内容包括以下这些：
1，面向对象的一些基本概念：继承，多态之类的
2， 抽象类和接口
3， 静态类，内部类
4， Java集合类，同步和非同步
5， Java类加载机制
6， Java内存模型和垃圾回收算法
7， 线程同步机制（voliate,synchronized,重入锁，threadlocal），线程间通信（wait,notify）
8， 异常处理
9， 多线程同步问题，生产者消费者，读者写者，哲学家就餐，用java实现
10， 了解java中设计模式的思想，用了哪些设计模式，有什么好处