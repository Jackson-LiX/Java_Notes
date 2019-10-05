#  JDK JRE 与 JVM三者之间的区别
**JVM(Java Virtual Machine)**: Java 虚拟机，负责识别 .class文件中的字节码指令并将其解释给操作系统。JVM是Java跨平台的核心。  
**JRE(Java Runtime Environment)**: Java 运行时环境，主要包含JVM的标准实现和java的一些基本类库。  
**JDK(Java Development Kit)**: Java 开发工具包， 是整个Java开发的核心，包含了JRE与其他的一些工具（javac.exe,  java.exe, jar.exe）。  

所以这三者之间的关系是： JDK > JRE > JVM  
JDK包含JRE, JRE包含JVM， 如果只是想运行Java程序安装JRE就够了， 但是想要使用Java开发就需要安装JDK。
