1. JVM 虚拟机，是java平台无关性的关键   
![image](https://github.com/shengda567/java-engineer/blob/master/JVM%20retionale.jpg)
把字节码文件解释成平台上的机器指令执行，因为计算机只能执行，0，1这样的二进制的指令。之后就能实现一次编译，到处执行了。
2. JDK JAVA软件开发工具包： 
两个组件：javac 编译器，将源程序转换成字节码。
java- 运行编译后的java程序（.class后缀）。

3. JRE(运行环境)：包括JVM, java核心类库和支持文件。
如果 只需要运行java程序，安装JRE即可。
如果要开发java软件，需要下载JDK(面向开发人员)。
JDK中附带JRE.
如图： 
![image](https://github.com/shengda567/java-engineer/blob/master/JDK_JRE_JVM.jpg)

4. JAVA平台：
JavaSE 主要是用于开发桌面程序。 
JavaEE : 主要是用于开发web程序。 
JavaME: 用于移动设备开发。

命令行程序（用记事本写一个java程序）
class HelloImooc{
  public static void main(String[] agrg){
      System.out.println("Hello, imooc")
  }
}
需要存成'HelloImooc.java'

5.如何在cdm中执行
![image](https://github.com/shengda567/java-engineer/blob/master/cdm%E4%B8%AD%E7%BC%96%E8%AF%91%E6%89%A7%E8%A1%8C.jpg)
