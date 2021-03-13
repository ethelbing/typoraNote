# 一、初识计算机和Java语言

## 计算机的基本概念
计算机（computer）俗称电脑，是现代一种用于高级计算，使用非常广泛的设备，主要有计算机硬件和软件两个部分组成。

计算机硬件是客观存在的各种计算机相关设备，

计算机软件是用于控制各种硬件设备完成各种功能。

## 常见的主要硬件
计算机硬件（computer hardware）主要包括：
>> 中央处理器（CPU）
>> 内存
>> 硬盘
>> 输入输出设备
>> 主板
>> 机箱和电源灯辅助设备

## 主要硬件的详解
### CPU的概述
CPU --中央处理器（Central Prodcessing Unit)
   --是计算机中最核心的部件，类似于人的大脑
   --是一台计算机运算核心和控制核心，所有预算都有CPU完成
   --其功能主要是解释计算机指令以及处理计算机软件中的数据

### 内存的概述
-- 是计算机中的内存部件，内存（Memory）也被称为内存储器
-- 用于暂时存放CPU中的运算数据，以及与硬盘等外部存储器交换的数据
-- CPU可以直接访问内存的数据，而且效率比较高
-- 容量不能实现永久存储，一旦断电会造成数据的丢失
-- 时刻记住Ctrl+S快捷键进行保存

### 硬盘的概述
-- 是计算机中的存储部件
-- 主要用于永久存放数据内容，容量大且断电不丢失
-- CPU不能直接访问硬盘中数据，若希望访问则需要先加载到内存中

### 科普
1TB = 1024GB
1GB = 1024MB
1MB = 1024KB
1KB = 1024Byte（字节）

### 输入输出设备
键盘叫标准输出设备
显示器交标准输入设备

## 常见主要软件
 计算机软件（Computer Software）可分为系统软件和应用软件， 系统软件是操作系统，使其他软件的基础。
 主流的操作系统有：Windows/Unit/Linux/IOS/Android

## 计算机的体系结构

![image-20210309235426619](https://github.com/ethelbing/backup_typora_pic/master/imgs/image-20210309235426619.png)

## 计算机语言的发展
人与计算机之间交流的表达方式，该语言有很多种。

 第一代语言：机器语言
  指令以二进制代码形式存在，最开始使用穿孔卡片。
 第二代语言：汇编语言
  使用助记符表示一条机器指令，如：ADD、SUB等
 第三代语言：高级语言
  Java、C、C++、PHP、Python、Scala等

## Java语言的发展
20世纪90年代（1990年），单片机系统 
植入到家电设备 sun 开展了绿色假话  詹姆斯-高斯林 C++
1983年 发现C++不能跨平台，改写C++
橡树 oak语言  程序员喜欢咖啡，爪哇岛来命名语言--Java

### Java语言发展历史
 1995 Java问世
 1996 Java1.0
 1999 Java1.2发布（Java SE、Java EE、Java ME）
 ---
 2004 tiger 发布（Java5.0），Java登入火星
 2011 7月份由Oracle正式发布Java7.0
 2014 3-19，Oracle公司发布Java8.0的正式版
 2017 9-21，Java9.0正式发布
 2018 9-25的，Oracle官方宣布发布Java11正式版本。

## Java语言的主要版本
### Java SE
Java SE（Java Platform，Standard Editor）称之为“Java平台标准版”，Java平台的基础。
 Java SE包含了运行Java应用所需要的基础环境和核心类库。
 Java SE还定义了基于桌面应用的基础类库，通过使用这些类库，我们可以编写出类似于像Office那样的仿佛多彩的桌面应用。
### Java EE
 Java EE（Java Platform，Enterprise Edition）称之为“Java 平台企业版”
 Java EE构建在Java SE基础之上，用于构建企业级应用，所谓企业级应用是指那些为商业组织，大型企业而创建的应用系统，例如：电信的“计费系统”、银行的“网银系统”，企业中的“客户关系管理系统”等等。
### Java ME
 Java ME（Java platform，Micro Editior)称之为Java平台微型版。
 为机顶盒、移动电话和PDA等嵌入式消费电子设备提供的Java解决方案。
 随着3G移动智能平台时代的到来，特别是以Java为核心编程语言的Android智能平台的迅速普及，Java ME已经走向淘汰。

## 开发工具下载和安装
方法一：官网下载  oracle.com /sum.com
方法二：搜索下载

## 相关概念
bin dll/exe文件：
>>  该目录主要存放JDK的各种工具命令
conf 配置文件
>>  该目录下主要存放jdk的相关配置文件
include 头文件
>> 该目录主要存放一些平台的头文件 
jmods 模块
>>  主要存放了jdk的各种模块
legal 授权文件
>> 主要存放了jdk各模块的授权文档
lib 包
>> 主要存放了jdk工具的一些补充jar包和源代码

jdk - Java开发工具包（Java Development Kit）。
Java开发人士安装下载
jre - Java运行时环境（Java SE Runtime Environment），提供了运行Java应用程序所不许的软件环境等。

javac.exe:
  编译器：用于将高级java源代码翻译成字节码文件
java.exe:
  解释器：主要用于启动JVM对字节码文件进行解释并执行。

![image-20210310003312354](C:\Users\ethel\AppData\Roaming\Typora\typora-user-images\image-20210310003312354.png)



## 编写java程序的流程

新建文本文档，将文件扩展名改为.java
切换项目路径
javac.exe XXX.java
java.exe XXX.class

### 当前目录快速打开cmd
方法一：shift+右键-->在此处打开powershell
              -->在此处可打开Linux Shell 
方法二：文件夹地址栏输入-->cmd

## 入门级常见的错误和简化的编译运行
拼写（关键字的拼写，大小写区分)
对括号
分号结尾
非法标示符
半角标点
主方法定义

 ## 常用的快捷键和注释
### 简单常用快捷键
 ctrl + S 保存
 ctrl + C 复制
 ctrl + V 粘贴
 ctrl + A 全选
 ctrl + X 剪切
 ctrl + Z 撤销
 ctrl + F 搜索
 ctrl + shift 切换输入法
 shift 中英文、
 Windows + D 回到桌面
 Windows + E 打开计算机
 Windows + L 锁屏
 Windows + R 打开运行
 Windows + tab 切换任务
 Alt + tab 切换任务
 ctrl+alt+delete 任务管理器
### 注释
用于代码说明
// 单行
/* */ 段落
/** */ 多行或文本注释  多行注释不允许嵌套使用

## 环境变量配置
我的电脑-->系统属性-->环境变量--->path
JAVA_HOME 
bin 路径
lib 路径
path:%JAVA_HOME%\bin;
配置完重启DOS窗口

## 跨平台原理
Java字节码可以通过JVM翻译为具体平台能够执行的机器指令。由于Sun定义了JVM规范，而且不同的操作系统大多提供了JVM实现，才使得相同的一个字节码文件可以在不同的系统上运行，从而使Java赢得”一次编译，到处使用"的美名。



# 二、变量和数据类型
## 变量的基本概念
当需要在程序中记录单个数据内容时，则声明一个变量即可，而声明变量的本质就是在内存中申请一个存储单元，由于该存储单元中的数据内容可以发生改变，因此得名为“变量”。
由于存放的书俊诶荣大小不一样，导致所需存储单元的大小不一样，在Java语言中使用数据类型加以描述，为了便于下次访问还需要给该变量制定一个名字，用于记录该变量对应的存储单元。

![image-20210310224024657](C:\Users\ethel\AppData\Roaming\Typora\typora-user-images\image-20210310224024657.png)

## 变量的声明方式
 数据类型 变量名 = 初始值；
 其中 = 初始值可以省略，但不可以省略

```
public class VarTest{
     public static void main(String[] args){
     // 1、声明一个变量并初始化 数据类型 变量名 = 初始化；
     int age = 18;
     //打印变量数值
          System.out.println("main params"+args);
     }
 }
```
使用变量的注意事项：
1、声明
2、初始化
3、不能重复声明

## 标示符的命名法则
1.由数字、字母、下划线以及$ 等组成，其中数字不能开头（后面讲到）
2.不能使用Java语言的关键字，所谓关键字就是Java语言中用于表示特殊含义的单词。
关键字：
| abstract | char | double | for | int |
|:-|:-|:-|:-|:-|
| private | strictfp | throws | assert | boolean |
| class | else | goto | interface | protected |
| super | transient | enum | break | const |
| extends | if | long | public  | switch |
| try | byte | continue | final | implements |
| native | return  | synchronized | void  | case |
| default | finally | inport | new | short |
| this | volatile | catch | do  | float |
| instanceof | package | static | throw | while |
3.区分大小写，长度没有限制，但不宜过长
4.尽量做到见名知意，支持中文但不推荐使用
5.标示符可以给类、变量、属性、方法、包起名字

## 变量输入输出的案例
案例题目：提示用户从键盘输入自己的姓名和年龄信息并打印出来
```
package com.lg.test;

import java.util.Scanner;

public class VarIOTest {
    public static void main(String[] args) {
        System.out.println("please input your name and your age");
        Scanner scanner = new Scanner(System.in);
        String name = scanner.next();
        int age = scanner.nextInt();
        System.out.println("your name is :" + name + "\n" + "your age :" + age);
    }
}

```
### 官方库的使用
JDK中带有大量的API类，是有Java系统带来的工具库，这些工具数以万计！是Java官方程序员的技术积累。
使用这些类可以大大简化编程，提高开发效率。、
具体的API类功能，可以参阅Java的参考手册

## 数据类型的分类
在Java语言中数据类型主要分为两大类：
（1）基本数据类型：
>> byte、short、int、long、float、double、boolean、char 

(2) 引用数据类型
>> 数组、类、接口、枚举、标注


## 常用的禁止
在日常生活中采用十进制进行数据的描述，逢十进一，是兼职权重是：10^0 10^1 10^2 ……
在计算机的底层采用0和1组成的二进制序列进行数据的描述，逢二进一，二进制的权重是2^0 2^1 2^2
二进制中的最高位（最左边）用于代表符号位，若该位是0则表示非负数，若该位是1则表示负数。
八进制和十六进制其实都是二进制的缩写


## 进制之间的转换
### 十进制->二进制
方式一：除2取余法
使用十进制整数不断地除以2取出余数，知道商为0时将余数逆序排序。
方式二：拆分法
将是假进制证书拆分为若干个二进制权重的和，有该权重下面写1，否则写0
1  2  4  8  16  32  64  128 ……
45=>32+8+4+1
### 二进制->十进制
正二进制转换为十进制的方式
一、加权法
使用二进制中的每个数字乘以当前位的权重再累加起来

### 负十进制->二进制
负十进制转换为二进制的方式
先将是兼职的绝对值转换为二进制，然后进行安慰取反再加一
负数的需要补码：按位取反，再加1

### 负二进制->十进制
先减一再按位取反，合并为十进制整数后添加负号。


## 单个字节所能表示的整数范围
整数范围（重中之重）
在计算机中单个字节表示八位二进制位，其中最高位（最左边）代表符号位，使用0代表非负数，使用1代表负数，具体表示的整数范围如下：
非负数表示范围：0000 0000~0111 1111 => 0~127 => 0~ 2^7-`
负数表示范围：1000 0000 ~ 1111 1111 => -128 ~ -1 => -2^7 ~-2^0
单个字节表示的整数范围是： -2^7 ~52^7-1,也就是 -128 ~127

## 整数类型的概念
Java语言中描述整数数据的类型有：
byte short int long 荐int类型。
其中byte类型在内存空间中占一个字节，表示范围是：-2^7 ~ 2^7-1
其中short类型在内存空间中占2个字节，表示范围是：-2^15 ~2^15-1
其中int类型在内存空间中占4个字节，表示范围是：-2^31~2^31-1
其中long类型在内存空间中占8个字节，表示范围是：-2^63~2^63-1
在Java程序中直接写出的整数数据叫做直接量、字面值、常量，默认为int类型。若希望表达更大的直接量，则在直接量的后面加上l或L，推荐L。

## 浮点类型的概念

Java语言中用于描述小数数据的类型：float和double，推荐double类型。

其中float类型在内存空间占4个字符，叫做点精度浮点数，可以表示7为有效数字，范围：-3.403E38~3.403E38

其中double类型在内存空间占8个字节，叫做双精度浮点数，可以表示15位有效数字，范围：-1.798E308~1.798E308

商业金额使用：java.math.bigDecimal类型

 ## 布尔类型

Java语言中用于描述真假信息类型有boolearn，值为：True和False

布尔类型在内存空间中所占大小没有明确的规定，可以认为是一个字节。

## 字符类型

Java语言中用于描述单个字符的数据类型：char类型，如：'a'、'中'等。

其中char类型在内存空间中占2个字节并且没有符号位，表示的范围是：0~65535，由于现实生活中很少有数据能够被单个字符描述，因此以后的开发中更多的使用由多个字符串起来组成的字符串，使用String类型加以描述，如：'hello'/'奇点'等。

计算机的底层只识别0和1组成的二进制序列，对于字符’a'这样的图案来说不满足该规则，因此该数据无法直接在计算机中存储，但现实生活中存在这样的图案需要计算机存储，为了使得该数据能够存储起来就可以给该数据指定一个编号，然后将编号存储起来即可，该编号就叫做ASCII

Java字符类型采用Unicode字符集编码，Unicode是世界通用的定长字符集，所有的字符都是16位。

双引号本身有两个含义：
a/字符串开头和结尾标志
b/双引号自身
要求掌握的转义字符有：\"-"  \'-'  \\ -\   \t-制表符  \n-换行符

## 基本数据类型之间的转换
Java语言中基本数据类型之间的转换方式：自动类型转换和强制转换
其中自动类型转换主要指从小类型到大类型之间的转换。

其中强制转换主要是指从大类型到小类型之间的转换，语法格式：目标类型 变量名 = （目标类型）源类型变量名

![image-20210312004826080](C:\Users\ethel\AppData\Roaming\Typora\typora-user-images\image-20210312004826080.png)

强转有风险，转换需谨慎

#  三、运算符

##  算术运算符的概念和使用

+ 表示算法运算法
- 表示减法运算法
* 表示乘法运算符
/  表示除法运算符
% 表示取模/取余运算符

## 算术运算符的注意事项
1.当两个整数相除时结果只保留整数部分，丢弃小数部分
2.若希望保留小数处理方法：
>> 使用枪支类型转换将其中一个操作数转换为double类型再运算即可  
>> 让其中一个操作数乘以1.0即可
3. 0 不能做除数

## 字符串使用

```
package com.lg.test;

import java.util.Scanner;

public class ArithmeticTimeTest {
    public static void main(String[] args) {
        System.out.println("please a int second");
        Scanner sc = new Scanner(System.in);
        int num = sc.nextInt();
        int hour = num / 3600;
        int min = num% 3600/60;
        int sec = num%60;
//        +既可以做字符串也可以做连接符
//        只要+两边的操作数中有一个操作数是字符串类型，则该+就被当做连接符
        System.out.println(hour+min+sec); //8
        System.out.println(hour+min+sec+""); //8
        System.out.println(hour+min+""+sec); //26
        System.out.println(hour+""+min+sec); //116
        System.out.println(""+hour+min+sec); //116
        System.out.println(""+(hour+min+sec)); //8
    }
}

```

## 逻辑运算：
&& 表示逻辑与运算符，相当于“并且”，同真为真，一假为假
||表示逻辑或运算符，相当于“或者”，一真为真，同假为假
！表示逻辑非运算，相当于“取反”，真为假，假为真
逻辑运算符的操作数均为boolean表达式

### 逻辑运算符的短路特征
对于逻辑与运算符来说，若第一个表达式为假则结果为假，此时跳过第二个表达式
对于逻辑或运算符类说，若第一个表达式为真则结果为真，此时跳过第二个表达式

### 条件/三目运算符
条件表达式？表达式1：表达式2

## 移位运算符
<< 左移运算符，用于将数据的二进制位向左移动，右边使用0补充
\>> 右移运算符，用于将数据的二进制右移动，在左边使用运算符补位
\>>> 表示逻辑右移运算符，用于将数据的而兼职位向右移动，左边使用0补充

## 位运算符
& 按位与
|  按位或
~ 按位取反
^按位异或运算 同为0，不同为1

![image-20210313000122411](https://github.com/ethelbing/backup_typora_pic/master/imgs/image-20210313000122411.png)

![image-20210313000449257](https://github.com/ethelbing/backup_typora_pic/master/imgs/image-20210313000449257.png)

## 关系运算符
> 表示是否大于运算符 >= 表示是否大于等于运算符
< 表示是否小于运算符 <= 表示是否小于等于运算符
== 表示是否等于运算符 != 表示是否不等于运算符
