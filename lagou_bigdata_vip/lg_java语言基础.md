# 一、初试计算机和Java语言

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








