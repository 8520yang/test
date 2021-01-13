# test
# LongAdder的源码
先判断cells数组是不是为空，cells数组是懒惰创建的，发生了才会创建cells数组。刚开始为空，

![Image text](https://github.com/8520yang/test/blob/master/img-folder/1.png)
## LongAccumulate()方法内部：
### 当还没有开始创建cell，走的第二个分支，初始化并且开始创建cell单元，初始化两个cell单元对象
![Image text](https://github.com/8520yang/test/blob/master/img-folder/2.png)
