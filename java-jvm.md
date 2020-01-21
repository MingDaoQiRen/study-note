# JAVA 虚拟机
JVM：java虚拟机
JVM是java平台无关性的关键
执行流程： 

java虚拟机解释、执行编译过程中生成的字节码文件，把字节码文件解释称具体平台上的机器指令
一次编译，到处运行

JDK，java语言的软件开发包
jdk里头很多相关的命令，编译和运行都需要
这些命令作为jdk中的组件

-javac -编译器，将源程序转成字节码
-java -运行编译后的java程序（.class文件）

JRE java runtime environment
包括java虚拟机（jvm）、java核心类库和支持文件
如果只需要运行java程序，下载并安装jre就可以了（面向用户）
如果开发java软件，需要jdk（面向开发者）
在jdk中带有jre

java平台：
javaSE（java标准版，一般用于开发桌面程序）
javaEE（java企业版，一般用于开发web程序）
javaME（java微型版，一般用于移动设备开发）
