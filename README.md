### 1. 运行时数据区
[JVM故障诊断与性能优化--运行时数据区（一）](https://blog.csdn.net/yinweicheng/article/details/80624259)

[jvm运行时数据区与内存管理机制](https://blog.csdn.net/yinweicheng/article/details/80607402)

[jvm故障诊断与性能优化（六）--分析Java堆](https://blog.csdn.net/yinweicheng/article/details/80995112)

线程共享的区域包括java堆和方法区，java堆分为新生代和老年代，方法区存放class文件信息。对象过大会导致堆溢出。
线程私有的为虚拟机栈、本地方法栈与程序计数器，递归可能导致栈溢出。
java栈指的是虚拟机栈
### 2.垃圾回收机制
[JVM故障诊断与性能优化--垃圾回收概念与算法（三）](https://blog.csdn.net/yinweicheng/article/details/80656549)

[jvm垃圾收集器与内存分配策略](https://blog.csdn.net/yinweicheng/article/details/80611670)

[JVM故障诊断与性能优化-垃圾收集器与内存分配（四）](https://blog.csdn.net/yinweicheng/article/details/80678653)

新生代的收集方法为复制算法；老年代的收集算法为标记整理、标记清除算法。对Java堆中不同的区域采用不同的方法为分代收集算法。
根据串行/并行方式以及垃圾收集算法的不同，产生了不同的垃圾收集器
### 3.性能调优
[JVM故障诊断与性能优化--jvm参数了解（二）](https://blog.csdn.net/yinweicheng/article/details/80650648)

[JVM故障诊断与性能优化-性能监控工具（五）](https://blog.csdn.net/yinweicheng/article/details/80698644)

[虚拟机性能监控与故障处理](https://blog.csdn.net/yinweicheng/article/details/80651760)

[JVM调优分析与实战](https://blog.csdn.net/yinweicheng/article/details/80666570)

掌握jvm参数中堆内存，垃圾收集日志，以及常用非堆参数的设置。
学会使用jvm命令行进行进程管理，内存映像与栈跟踪，使用可视化工具调优。
学会使用常用的进程管理与快照分析工具。
### 4.类文件结构
[jvm类文件结构](https://blog.csdn.net/yinweicheng/article/details/80918101)

[AOP的底层实现--ASM](https://blog.csdn.net/yinweicheng/article/details/81005608)

掌握类文件结构，并能够进行ASM的简单应用。
### 5.字节码执行引擎
[jvm字节码执行引擎](https://blog.csdn.net/yinweicheng/article/details/80918187)

[从字节码角度看对象创建](https://blog.csdn.net/yinweicheng/article/details/81273819)

[IntegerCache、longCache缓存策略与String.intern()用法说明](https://blog.csdn.net/yinweicheng/article/details/81191812)

了解字节码指令，能够从字节码的角度看懂一些较难理解的问题。
### 6.类加载机制
[jvm类加载机制](https://blog.csdn.net/yinweicheng/article/details/80918153#t10)

[jvm类加载与执行子系统](https://blog.csdn.net/yinweicheng/article/details/80918232)

掌握两种类加载模型，并会使用类加载器，以及常用的osgi框架
### 7.虚拟机优化
[jvm类的早期优化](https://blog.csdn.net/yinweicheng/article/details/80918244)

[jvm晚期优化](https://blog.csdn.net/yinweicheng/article/details/80918264)

了解jvm运行和解析时的优化。
### 8.内存模型
[java内存模型](https://blog.csdn.net/yinweicheng/article/details/80918303)

掌握内存模型中主内存与工作内存的交互方式，volatile变量的规则，以及先行发生原则。
### 9.锁机制
[线程安全与锁优化](https://blog.csdn.net/yinweicheng/article/details/80918901)

了解常用锁定义，明白偏向锁，轻量级锁，重量级锁的原理。
