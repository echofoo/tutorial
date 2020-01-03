

# 第6章 Java IO编程

## 1 IO简介

![1](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\1-1.png)
![2](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\1-2.png)
![3](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\1-3.png)
![4](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\1-4.png)
![5](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\1-5.png)
![6](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\1-6.png)
![7](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\1-7.png)
![8](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\1-8.png)
![9](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\1-9.png)

## 2 IO基础-File对象
![1](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\2-1.png)
![2](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\2-2.png)
![3](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\2-3.png)
![4](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\2-4.png)
![5](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\2-5.png)
![6](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\2-6.png)
![7](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\2-7.png)
![8](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\2-8.png)
![9](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\2-9.png)
![10](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\2-10.png)

## 3 Input和Output-InputStream
![1](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\3-1.png)
![2](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\3-2.png)
![3](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\3-3.png)
![4](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\3-4.png)
![5](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\3-5.png)
![6](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\3-6.png)
![7](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\3-7.png)
![8](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\3-8.png)
![9](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\3-9.png)
![10](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\3-10.png)
![11](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\3-11.png)

## 4. Input和Output-OutputStream
![1](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\4-1.png)
![2](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\4-2.png)
出于对磁盘、网络写入时效率的考虑，很多时候并不是输出一个字节就立即写入。而是先把字节放到内存的一个缓冲区里，等待缓存区满了之后，再一次性写入。
对于很多设备来说，一次性写一个字节和一次性写1000个字节花费的时间是完全一样的。所以我们有OutputStream有一个flush()方法，能够强制把缓冲区的数据输出。
通常我们不需要调用这个方法，因为缓冲区满的时候会自动调用这个方法。
我们在调用close方法关闭OutputStream之前，也会自动调用这个方法。
![3](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\4-3.png)
![4](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\4-4.png)
![5](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\4-5.png)
![6](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\4-6.png)
![7](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\4-7.png)
![8](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\4-8.png)
![9](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\4-9.png)

## 5 Input和Output-Filter模式
![1](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\5-1.png)
![2](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\5-2.png)
![3](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\5-3.png)
![4](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\5-4.png)
![5](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\5-5.png)
![6](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\5-6.png)
![7](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\5-7.png)
![8](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\5-8.png)
![9](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\5-9.png)
![10](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\5-10.png)
![11](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\5-11.png)

## 6 Input和Output-操作Zip
![1](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\6-1.png)
![2](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\6-2.png)
![3](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\6-3.png)
![4](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\6-4.png)
![5](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\6-5.png)
![6](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\6-6.png)


## 7 Input和Output-classpath资源
![1](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\7-1.png)
![2](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\7-2.png)
![3](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\7-3.png)
![4](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\7-4.png)
![5](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\7-5.png)
![6](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\7-6.png)


## 8 Input和Output-InputStream- 序列化
![1](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\8-1.png)
![2](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\8-2.png)
![3](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\8-3.png)
![4](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\8-4.png)
![5](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\8-5.png)
![6](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\8-6.png)
![7](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\8-7.png)
![8](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\8-8.png)
![9](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\8-9.png)

## 9 Reader
![1](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\9-1.png)
![2](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\9-2.png)
![3](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\9-3.png)
![4](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\9-4.png)
![5](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\9-5.png)
![6](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\9-6.png)
![7](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\9-7.png)
![8](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\9-8.png)
![9](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\9-9.png)
![10](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\9-10.png)

编码字符使用的是**系统默认的编码**

![11](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\9-11.png)
![12](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\9-12.png)
![13](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\9-13.png)

## 10 Writer 

![1](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\10-1.png)
![2](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\10-2.png)
![3](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\10-3.png)
![4](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\10-4.png)
![5](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\10-5.png)
![6](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\10-6.png)
![7](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\10-7.png)
可以写入char[]数组，或者直接写入String
![8](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\10-8.png)
![9](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\10-9.png)
使用的编码字符是**系统默认的编码**
![10](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\10-10.png)
![11](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\10-11.png)
![12](D:\GitHub\廖雪峰Java讲义\pic\6-Java IO编程\10-12.png)