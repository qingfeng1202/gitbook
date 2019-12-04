## Java 简介
Java是由Sun Microsystems公司于1995年5月推出的Java面向对象程序设计语言和Java平台的总称。由James Gosling和同事们共同研发，并在1995年正式推出

### Java发展历史
- 1995年5月23日，Java语言诞生
- 1996年1月，第一个JDK-JDK1.0诞生
- 1996年4月，10个最主要的操作系统供应商申明将在其产品中嵌入JAVA技术
- 1996年9月，约8.3万个网页应用了JAVA技术来制作
- 1997年2月18日，JDK1.1发布
- 1997年4月2日，JavaOne会议召开，参与者逾一万人，创当时全球同类会议规模之纪录
- 1997年9月，JavaDeveloperConnection社区成员超过十万
- 1998年2月，JDK1.1被下载超过2,000,000次
- 1998年12月8日，JAVA2企业平台J2EE发布
- 1999年6月，SUN公司发布Java的三个版本：标准版（JavaSE,以前是J2SE）、企业版（JavaEE以前是J2EE）和微型版（JavaME，以前是J2ME）
- 2000年5月8日，JDK1.3发布
- 2000年5月29日，JDK1.4发布
- 2001年6月5日，NOKIA宣布，到2003年将出售1亿部支持Java的手机
- 2001年9月24日，J2EE1.3发布
- 2002年2月26日，J2SE1.4发布，自此Java的计算能力有了大幅提升
- 2004年9月30日18:00PM，J2SE1.5发布，成为Java语言发展史上的又一里程碑。为了表示该版本的重要性，J2SE1.5更名为Java SE 5.0
- 2005年6月，JavaOne大会召开，SUN公司公开Java SE 6。此时，Java的各种版本已经更名，以取消其中的数字"2"：J2EE更名为Java EE，J2SE更名为Java SE，J2ME更名为Java ME
- 2006年12月，SUN公司发布JRE6.0
- 2009年04月20日，甲骨文74亿美元收购Sun。取得java的版权。
- 2010年11月，由于甲骨文对于Java社区的不友善，因此Apache扬言将退出JCP。
- 2011年7月28日，甲骨文发布 Java7.0 的正式版。
- 2014年3月18日，Oracle公司发表 Java SE 8。
- 2017年9月21日，Oracle公司发表 Java SE 9
- 2018年3月21日，Oracle公司发表 Java SE 10
- 2018年9月25日，Java SE 11 发布
- 2019年3月20日，Java SE 12 发布

### Java分为三个体系：
- J2SE Java的标准版本 (Java2 Standard Edition) 定位在客户端，主要用于桌面应用软件的编程
- J2EE 企业版本(Java2 Enterprise Edition)定义在服务器端Java2的企业版，主要用于分布式网络程序的开 发，如电子商务网站
- J2ME (Java2 Micro Edition) 主要应用于嵌入式系统开发，如手机和PDA的编程
<img src="..\..\..\img\Java教程\Java入门\J2SE-J2EE-J2ME.png" /><br>
简单来说，Java SE就是标准版，包含标准的JVM和标准库，而Java EE是企业版，它只是在Java SE的基础上加上了大量的API和库，以便方便开发Web应用、数据库、消息服务等，Java EE的应用使用的虚拟机和Java SE完全相同。<br>
Java ME就和Java SE不同，它是一个针对嵌入式设备的“瘦身版”，Java SE的标准库无法在Java ME上使用，Java ME的虚拟机也是“瘦身版”。<br>
Java SE是整个Java平台的核心，而Java EE是进一步学习Web应用所必须的。我们熟悉的Spring等框架都是Java EE开源生态系统的一部分。<br>

#### Java学习路线推荐
- 首先要学习Java SE，掌握Java语言本身、Java核心开发技术以及Java标准库的使用
- Javaweb方向：需要继续学习Spring等框架、数据库开发、分布式架构, 了解Html、css、JavaScript
- 大数据方向：需要学习Hadoop、Spark、Flink这些大数据平台就是需要学习的，他们都基于Java或Scala开发
- 总结：Java SE的核心技术是基础

### Java语言特点
- 面向对象性：两个重要的概念：类与对象；三大特征：封装、继承、多态<br>
- 健壮性：1.去除了c/c++的指针 2.提供了垃圾自动回收机制。--->仍然可能出现内存溢出、内存泄漏<br>
- 跨平台性：write once,run anywhere。 “一次编译，到处运行”  -->JVM的支持<br>

### 名词解释
#### 1.JVM、JRE、JDK
- JVM: Java虚拟机(Java Virtual Machine)，解释运行Java字节码文件，Java语言的可移植性正是建立在Java虚拟机的基础上，任何平台只要装有针对于该平台的Java虚拟机，字节码文件（.class）就可以在该平台上运行。这就是“一次编译，多次运行”
- JRE: Java运行环境（Java Runtime Environment)，它包含Java虚拟机（jvm）、Java核心类库和支持文件
- JDK：Java 语言的软件开发工具包(Java Development Kit)，它包含JRE和JAVA工具



