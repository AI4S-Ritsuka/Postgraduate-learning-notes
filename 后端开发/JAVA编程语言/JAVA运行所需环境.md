**后端开发——JAVA编程语言学习 2**

**JVM与跨平台**

```
1. JVM: JAVA虚拟机，Java程序运行的假想计算机
2. 跨平台运行：Java程序想要在不同的操作系统上运行（Windos Linux ...）就需要安装不同版本的JVM（即一个程序适应于多个操作系统）
```

![](https://github.com/AI4S-Ritsuka/Postgraduate-learning-notes/blob/main/assets-java/Screenshot%202024-09-20%20154804.png)

**JDK与JRE**

```
1. JDK：Java开发工具包，其中包含了JRE
   javac：编译工具
   java：运行工具
   jdb：调试工具
   ......
2. JRE：Java运行环境，包含JVM以及后续开发所用到的核心类库
JDK > JRE > JVM
```

* 从JDK9开始，不再为JRE设置单独目录，使用模块化功能，令用户可以根据自己的需求来定义使用的Runtime，而不需要每次都用百MB的JRE，可以提高运行效率。

**JDK下载与安装**

网页连接：https://www.oracle.com/java/technologies/downloads/

安装路径不要有中文和空格！！！（开发相关的都须遵守）

检验安装成功：进入JDK的bin目录下，打开DOS命令窗口，分别输入`java`（运行命令），`javac`（编译命令）

看到如下窗口代表安装完成：

![](https://github.com/AI4S-Ritsuka/Postgraduate-learning-notes/blob/main/assets-java/Screenshot%202024-09-20%20161737.png)

![](https://github.com/AI4S-Ritsuka/Postgraduate-learning-notes/blob/main/assets-java/Screenshot%202024-09-20%20161754.png)

**环境变量的配置**

一般JDK会自动配置环境变量，但若没有，就会发现java有关命令只会在之前的bin目录里生效，所以为了解决这个问题，需要配置环境变量，两种方法分别如图所示

![](https://github.com/AI4S-Ritsuka/Postgraduate-learning-notes/blob/main/assets-java/Screenshot%202024-09-20%20163041.png)

![](https://github.com/AI4S-Ritsuka/Postgraduate-learning-notes/blob/main/assets-java/Screenshot%202024-09-20%20163720.png)

* 若发现电脑重启后环境变量失效的解决办法：

  1. 点到环境变量中，直接点确定，不作其他任何操作
  2. 将bin路径粘到Path里（配置法2）

  学习了IDEA后就不会有这个问题