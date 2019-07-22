# raids



一、nosql 简介

​	![1563770185112](C:\Users\dell\AppData\Roaming\Typora\typora-user-images\1563770185112.png)

​	1、高扩展性 （1、水平  2、垂直）

​	2、高可用

​	3、可靠性（存入数据库中）

·	4、基于内存的

​	5、持久化

​			5.1、rdb 周期性更新到数据库内

​			5.2、aof 日志记录

​	6、radis提供的方案（扩展）

​			6.1主从

​			6.2哨兵

​			6.3集群

​	7、raids 与 memcash区别

​			7.1 memcash 并行处理

​			7.2radis 串行处理 多实例  

二、关系型数据库

​	1、Oracle、MySQL    特点acdi  a:原子性   c:隔离性   i:一致性  d:永久性