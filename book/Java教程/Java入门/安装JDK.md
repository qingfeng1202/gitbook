### 安装JDK
Java程序必须运行在JVM之上

#### JDK下载
JDK下载地址：
```
https://www.oracle.com/technetwork/java/javase/downloads/index.html
```

<img src="..\..\..\img\Java教程\Java入门\jdk下载1.png" />

<img src="..\..\..\img\Java教程\Java入门\jdk下载2.png" />

#### JDK安装
安装过程中会出现两次 安装提示 。第一次是安装 jdk ，第二次是安装 jre 。建议两个都安装在同一个java文件夹中的不同文件夹中。（不能都安装在java文件夹的根目录下，jdk和jre安装在同一文件夹会出错）

<img src="..\..\..\img\Java教程\Java入门\jdk安装1.png" />

#### 配置环境变量
##### 安装完JDK后需要配置环境变量
```
计算机 → 属性 → 高级系统设置 → 高级 → 环境变量
```
<img src="..\..\..\img\Java教程\Java入门\jdk配置环境变量1.png" />

##### 配置JAVA_HOME
```
系统变量 → 新建 JAVA_HOME 变量 → 变量值填写jdk的安装目录
```

##### 配置Path<br>
```bash
系统变量 → 寻找 Path 变量 → 编辑 → 在变量值最后输入

%JAVA_HOME%\bin;%JAVA_HOME%\jre\bin;  
# 注意原来Path的变量值末尾有没有;号，如果没有，先输入；号再输入上面的代码
```
<img src="..\..\..\img\Java教程\Java入门\配置path.png" /><br>

##### 配置CLASSPATH<br>
```bash
系统变量 → 新建 CLASSPATH 变量 → 变量值填写 

.;%JAVA_HOME%\lib;%JAVA_HOME%\lib\tools.jar  
# 注意最前面有一点
```
<img src="..\..\..\img\Java教程\Java入门\配置classpath.png" /><br>

##### 检验是否配置成功<br>
运行cmd 输入 
```bash
java -version  
#java 和 -version 之间有空格
```
<img src="..\..\..\img\Java教程\Java入门\检验JDK.png" /><br>
