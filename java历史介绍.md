# 计算机：  硬件 + 软件
## 主要硬件：
- cpu：cpu是一个计算机的运算核心以及控制核心。 
- 内存：存储数据的，软件在运行过程中所需要的数据会先加载到内存 中，然后cpu获取 的数据都是直接从内存中获取
，	并不是直接从硬盘中获取的。  优点： 存取速度快。  缺点： 一旦断电或者是程序退出，内存中的数据会马上丢失。
- 硬盘(机械硬盘， 固态硬盘)： 优点：可以永久性保持数据，即使断电或者是程序退出，保存在硬盘中的数据是不会丢失的。 缺点： 存取的速度慢。

## 软件：
### 系统软件: 
比如： windows 、 linux , mac os , unix .....

### 应用软件: 应用软件必须要在系统软件的基础上才能使用的。
比如： QQ 、 360 、 飞Q 、 红蜘蛛。。。。	

软件的本质是什么（软件出现的主要目的是什么）？ 提高人类与计算机的交互效率， 

人与计算机的交互方式：

图形化的交互方式：操作简单， 功能强大。 
dos命令(命令行)的交互方式： 需要记忆大量的命令，功能弱小。
dos命令的交互方式需要一个控制台窗口：	
打开控制台的方式：
	方式一:  开始--------> 所有程序----------> 附件 ------------> 命令提示符窗口 
	方式二： 开始--------> 在输入框内输入"cmd"命令回车即可
常见的dos命令：
盘：        		:进入指定的盘的根目录。
dir        		:列出当前控制台所在的路径下的所有文件以及文件夹。
	cd  路径    		:进入到指定的路径下。 
cd  /       		:返回当前路径下的根目录。
cd  ..      		: 返回上一级目录。
md  文件夹的名称        : 创建一个文件夹。只会创建一个文件夹。不会创建文件 的。
rd  文件夹的名称        ： 删除一个指定名字的文件夹。 注意： rd命令不能用于删除非空的文件夹。 


echo 数据>文件          ： 创建一个文件并且写入数据。
type 文件名             ： 查看指定文件的数据。
del  文件名             ： 删除指定文件名的文件。  注意： del命令后面如果跟的 是一个文件夹的名称，那么就是删除该文件夹中所有文件，


*                       ：通配符，通配符可以匹配任何的文件名。。
	cls                     :清屏（清除以前执行过的命令）
tab                     : 内容补全。
上下方向键              ： 找回之前敲过的命令。
exit                    ：关闭当前窗口。


计算机语言： 与计算机交互的语言。 

从历史的角度：	
机器语言： 1 10  0010101	

汇编语言： 通过大量的单词代替了计算机的指令      1 1 add	
高级计算机语言    java \ c  \c++ \ javascript \ php \c# \ object o

## java的发展历史：
1995诞生 ， java是一门面向互联网的计算机语言。  雏形
java语言的重要特性之----------------> 跨平台   平台： 操作系统。 
跨平台： 一次编译，到处运行。


java的环境搭建： 

JRE： java运行环境。   JRE  = java 虚拟机  +  核心类库(辅助java虚拟机运行的文件) 

JDK: java开发工具集.   JDK =  java开发工具 + jre. 

JDK 的安装路径不准出现中文或者是空格。 

jdk的目录介绍：
  bin ：  存放的就是java开发工具的可执行文件。
  db:     sum公司自带的一个数据库。
  include:  存储的是本地方法的文件。 
  jre:     java虚拟机的文件夹
  lib :    核心类库文件。 
  src :    源代码文件。  java语言是开源的。


目前要使用到的java开发工具： 

javac.exe ： 启动java编译器对java源文件进行编译。 

使用格式：
	javac java源文件.
	
java.exe ：  启动java虚拟机解释并执行指定的class文件。

使用格式：
	java  class文件  注意： 不需要后缀名。 
 
编写java文件的步骤：
第一步： 新建一个txt文件，然后把后缀名改成java即可。
第二步： java中的代码都必须要写在类上，java中的代码是以类作为单位 的。      
	类的定义格式：	
		
		class 类名{
			大括号中的代码就是一个类的范围。在该打括号中即可写java代码。

		}
第三步： 要编写一个主方法。  主方法是一个程序的主入口，代码就是从主方法上开始执行的。
	
	主方法的写法是固定的：
			
		public static void main(String[] args){

		}	
第四步： 启动javac.exe该工具编译 java源文件。
问题： 每次编译的时候都需要写上java源文件的完整路径信息。 烦！！！
目前如果我可以让javac这个工具在任何路径下都可以找到，那么该问题是否解决了？		
解决方案： 把javac所在的路径保存到path的环境变量上。







在控制台窗口执行可执行文件的原理：
在控制台上编写一个可执行文件的命令，首先windows会在控制台当前所在的窗口下去搜索是否存在该可执行文件，
如果存在，那么马上执行该文件，如果不存在当前路径下，然后还会去到系统 的path环境变量下去搜索path环境变量
所保存的路径下是否存在该文件。

path环境变量的打开方式：	
	  右击
计算机--------------> 属性 ------------->高级系统设置  ----------->高级  -----------> 环境变量 -----> path环境变量





任务： 
1. 每个dos命令练习到3次以上。
2. 总结为什么配置path的环境变量信息。
3. 要编写好第一个例子。 















































