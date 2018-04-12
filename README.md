# Web 开发简介

# 开发路线图

里面有很多概念，建议多看几遍，见过的单词都搜索下，了解个大概。
https://github.com/kamranahmedse/developer-roadmap


对于一些基础概念知乎上有个帖子有个初步介绍（https://www.zhihu.com/question/22689579/answer/22318058），需要的可以看个一两遍。


# 典型架构

LAMP = Linux + Apache + MySQL + PHP（P还可能是Python或Perl。有时候L会改成W=Windows。），也就是服务器上的操作系统是 Linux，Web Server 用 Apache，数据库用 MySQL，服务器脚本用 PHP，这些都是开源技术，网站起步时用起来的成本会比较低，所以是普通网站里非常常见的架构（虽然对于发展得很大的网站会遇到很多瓶颈），Facebook就是这种，淘宝也曾经是。J2EE，Java 世界的架构，通常是企业用的（银行、大型公司,.etc），比较常见地还会搭配一种 UNIX 做操作系统，Apache 做 Web Server，Tomcat 转换 JSP 到 Java 给服务器程序用（其实它也自带 Web Server），Oracle 数据库等等。不一定拿来建站，常常用来提供企业里的各种需要用到网络的业务。我们学校教务系统就是用J2EE做的=。= 淘宝现在也是从LAMP转型到了这个。http://ASP.NET，微软家的架构，通常会搭配 Windows Server 操作系统，SQL Server 数据库，IIS 做 Web Server。StackOverflow和京东（曾经）就是这个架构。神奇的MEAN架构，MongoDB做数据库，Express做 Web Framework，Angular 做前端的 JavaScript 框架，Node.js 用于编写 Web Server。神奇之处在于这几个东西的语言都是 JavaScript （MongoDB的实现不是，但与外界沟通用的语言是）。因为是比较新的架构，还有待时间的考验，不过被很多人（尤其是靠 JavaScript 吃饭的前端程序猿们）热切关注。一般来说重点不在技术而且在乎成本的新网站比较喜欢用 LAMP，重视安全稳定和速度的企业和机构喜欢 J2EE，想省事的网站喜欢 http://ASP.NET，比较 Geek 的网站和创业公司喜欢折腾各种 Python、Ruby、Node.js世界的东西，Google 这样现成的技术都解决不了需求的超大型网站就自己折腾解决方案。
（作者：张秋怡，链接：https://www.zhihu.com/question/22689579/answer/22318058）

## 主流架构WAMP(LAMP)
Windows下的Apache+Mysql/MariaDB+Perl/PHP/Python，一组常用来搭建动态网站或者服务器的开源软件，本身都是各自独立的程序，但是因为常被放在一起使用，拥有了越来越高的兼容度，共同组成了一个强大的Web应用程序平台。随着开源潮流的蓬勃发展，开放源代码的LAMP已经与J2EE和.Net商业软件形成三足鼎立之势，并且该软件开发的项目在软件方面的投资成本较低，因此受到整个IT界的关注。LAMP是基于Linux，Apache，MySQL/MariaDB和PHP的开放资源网络开发平台，PHP是一种有时候用Perl或Python可代替的编程语言。这个术语来自欧洲，在那里这些程序常用来作为一种标准开发环境。名字来源于每个程序的第一个字母。每个程序在所有权里都符合开放源代码标准：Linux是开放系统；Apache是最通用的网络服务器；mySQL是带有基于网络管理附加工具的关系数据库；PHP是流行的对象脚本语言，它包含了多数其它语言的优秀特征来使得它的网络开发更加有效。开发者在Windows操作系统下使用这些Linux环境里的工具称为使用WAMP。

### 安装
可以分别下载，再组合。
不过现在有一个傻瓜式的单独安装包。

官网下载链接（网页能访问，但是点击下载没反应，也是醉了）：
http://www.wampserver.com/ 


2.5 非官网下载链接：
http://pc.xzstatic.com/2016/12/wampserver_X86_2.5.1455519048.exe

3.1.0 非官网下载链接：
http://down-www.7down.net/pcdown/soft/xiazai/wampserver310_x64.rar

安装教程
https://jingyan.baidu.com/article/4b52d702cb7792fc5c774bed.html


## 主流架构J2EE
J2EE是一套全然不同于传统应用开发的技术架构，包含许多组件，主要可简化且规范应用系统的开发与部署，进而提高可移植性、安全与再用价值。
J2EE核心是一组技术规范与指南，其中所包含的各类组件、服务架构及技术层次，均有共同的标准及规格，让各种依循J2EE架构的不同平台之间，存在良好的兼容性，解决过去企业后端使用的信息产品彼此之间无法兼容，企业内部或外部难以互通的窘境。
J2EE组件和“标准的” Java类的不同点在于：它被装配在一个J2EE应用中，具有固定的格式并遵守J2EE规范，由J2EE服务器对其进行管理。J2EE规范是这样定义J2EE组件的：客户端应用程序和applet是运行在客户端的组件；Java Servlet和Java Server Pages (JSP) 是运行在服务器端的Web组件；Enterprise Java Bean (EJB )组件是运行在服务器端的业务组件。

## 主流架构Asp.NET

## 新兴架构MEAN

