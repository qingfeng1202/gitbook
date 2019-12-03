## IDE
IDE是集成开发环境：Integrated Development Environment的缩写,集成了代码编写功能、分析功能、编译功能、调试功能等一体化的开发软件服务套<br>
#### 优点：
- 编辑器的自动提示，可以大大提高敲代码的速度
- 代码修改后可以自动重新编译，并直接运行
- 可以方便地进行断点调试
### 主流用于Java开发的IDE
#### Eclipse
Eclipse是由IBM开发并捐赠给开源社区的一个IDE，是一个开放源代码的、基于Java的可扩展开发平台，它只是一个框架和一组服务，用于通过插件组件构建开发环境，Eclipse 附带了一个标准的插件集，包括Java开发工具（Java Development Kit，JDK）
#### IntelliJ Idea
IntelliJ Idea是由JetBrains公司开发的一个功能强大的IDE，分为社区版和收费版

##### 本课程使用Eclipse作为开发工具原因在于
- 完全免费
- 满足Java开发需求
- 在现实开发项目中，使用率高

### 安装Eclipse
Eclipse官网下载地址：<a href='https://www.eclipse.org/downloads/'>https://www.eclipse.org/downloads/</a>
<img src="..\..\..\img\Java教程\Java入门\eclipse下载1.png" /><br>
<img src="..\..\..\img\Java教程\Java入门\eclipse下载2.png" /><br>
<img src="..\..\..\img\Java教程\Java入门\eclipse下载3.png" /><br>
注：Eclipse是绿色版的，直接解压就可以使用（eclipse.exe）
### 使用Eclipse
<img src="..\..\..\img\Java教程\Java入门\eclipse使用1.png" /><br>
注：
- 工作空间路径可以自定义，但是路径中不要带有空格或者中文
- user this as the default and do not ask again  这个是设置当前工作空间为默认工作空间，下次再使用eclipse时，不再询问
- 工作空间路径不存在时，eclipse会主动创建路径
- 第一次进入eclipse时有个欢迎界面（Welcome），直接关掉即可
#### Eclipse一些初始配置
- 配置JDK
Window → Preferences → Java → Installed JREs → Add → Standard VM Next → Directory → 选择jdk安装路径 → Finish → 勾选jdk → Apply
<img src="..\..\..\img\Java教程\Java入门\eclipse配置1.png" /><br>
<img src="..\..\..\img\Java教程\Java入门\eclipse配置2.png" /><br>
<img src="..\..\..\img\Java教程\Java入门\eclipse配置3.png" /><br>
<img src="..\..\..\img\Java教程\Java入门\eclipse配置4.png" /><br>
<img src="..\..\..\img\Java教程\Java入门\eclipse配置5.png" /><br>
- 配置工作空间编码格式
Window → Preferences → General → Workspace → Other → UTF-8 → Apply
<img src="..\..\..\img\Java教程\Java入门\eclipse配置6.png" /><br>
- 配置字体大小
Window → Preferences → General → Appearance → Colors and Fonts → Text Font
<img src="..\..\..\img\Java教程\Java入门\eclipse配置7.png" /><br>
### 使用Eclipse创建第一个项目
File → New → Java Project
<img src="..\..\..\img\Java教程\Java入门\eclipse创建第一个项目.png" /><br>
<img src="..\..\..\img\Java教程\Java入门\eclipse创建项目.png" /><br>
#### 新建Java文件并运行
展开HelloWorld工程，选中源码目录src，点击右键，在弹出菜单中选择 New  → Class
<img src="..\..\..\img\Java教程\Java入门\新建java文件.png" /><br>
<img src="..\..\..\img\Java教程\Java入门\新建java文件2.png" /><br>
##### 填上代码
```java
public class HelloWorld {

	public static void main(String[] args) {
		System.out.println("Hello World!");
	}

}
```
##### 运行代码
选中java文件，点击右键，选择 Run As, 点击 Java Application
<img src="..\..\..\img\Java教程\Java入门\运行java代码.png" /><br>

<img src="..\..\..\img\Java教程\Java入门\eclipse第一个项目.png" /><br>