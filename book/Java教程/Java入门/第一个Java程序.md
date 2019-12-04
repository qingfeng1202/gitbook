## 第一个Java程序
安装完JDK,我们来编写第一个java程序<br>
- 打开文本编辑器，输入以下代码：
```java
public class Hello{
    public static void main(String[] args){
        System.out.println("Hello, World!");
    }
}
```
- 保存为：Hello.java(文件的扩展名为java，不是txt)<br>
<img src="..\..\..\img\Java教程\Java入门\hellojava.png" /><br>

- 使用javac可以将.java源码编译成.class字节码<br>
<img src="..\..\..\img\Java教程\Java入门\class.png" /><br>

- 使用java可以运行一个已编译的Java程序，参数是类名<br>
<img src="..\..\..\img\Java教程\Java入门\执行.png" /><br>

#### 代码说明
<img src="..\..\..\img\Java教程\Java入门\代码说明.png" /><br>
- Java对大小写敏感，如果出现了大小写拼写错误，程序将无法运行 
- public class Hello {...} 被称为class（类）,Hello为类目，class用来定义一个类，public为表示这个类是公开的
- 方法是可执行的代码块，一个方法除了方法名，还有用()括起来的方法参数
- public static void main(String[] args){...} 这是main方法，是Java应用程序的入口方法，它有固定的书写格式，main为方法名，它有一个参数，参数类型是String[]，参数名是args，public、static用来修饰方法，这里表示它是一个公开的静态方法，void是方法的返回类型，而花括号{}中间的就是方法的代码
- System.out.println("Hello, World!"); 可执行的代码，每一行代码用;结束
- Java源码的缩进不是必须的，但是用缩进后，格式好看，很容易看出代码块的开始和结束，缩进一般是4个空格或者一个tab