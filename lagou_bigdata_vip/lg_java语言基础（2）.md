任务四：分支结构的概念

for 循环更适合明确循环次数的场合，不是只能用于该场合中。

switch（）中支持的数据类型有：
byte、short、char、int
从jdk1.5开始支持枚举类型
从jdk1.7开始支持String类型
不支持类型Boolean、double、float

![image-20210313233019945](https://github.com/ethelbing/backup_typora_pic/master/imgs/image-20210313233019945.png)

## 一维数组的基本概念

当需要在Java程序中记录单个数据内容时，则声明一个变量即可。
当需要在Java程序中记录多个类型相同的数据内容时，则声明一个一位数组即可，一维数组本质上就是在内存空间中申请一段连续存储的单元。
数组是相同数据类型的多个元素的容器，元素按线性顺序排列，在Java语言中体现为一种引用数据类型。

数组类型[] 数组名称= new 数据类型[数组长度]

## 内存结构分析

### 内存结构之栈区
栈用于存放程序运行过程当中所有的局部变量。
一个运行的Java程序从开始到结束会有多次变量的声明。

### 内存结构之堆区
JVM会在其内存空间中开辟一个称为“堆”的存储空间，这部分空间用于存储使用new关键字创建的数组和对象。
int[] aa=new int[10]
局部变量-->栈区
int[] aa
实例化、初始化变量时候-->堆区
new int[10]

![image-20210314013149792](https://github.com/ethelbing/backup_typora_pic/master/imgs/image-20210314013149792.png)

$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
$$

## 一维数组优缺点
通过下标索引，速度快
要求所有元素类型相同
内存空间要求必须连续，并且长度一旦确定不能修改
增加和删除元素时可能移动大量元素，效率低

## 一维数组之间拷贝
arr.arraycopy(arra,1,arrb,0,3)
从arra下标1开始拷贝到arrb从零开始，拷贝3个下标


