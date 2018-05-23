# JenkinsTester
>目录<br>
>[一、环境](1#)<br>
>[二、安装](2#)

<h1 id="1">一、环境</h1>
**操作系统**: centos7_x64

**jre**:[http://download.oracle.com/otn-pub/java/jdk/8u171-b11/512cd62ec5174c3487ac17c61aaa89e8/server-jre-8u171-linux-x64.tar.gz](http://download.oracle.com/otn-pub/java/jdk/8u171-b11/512cd62ec5174c3487ac17c61aaa89e8/server-jre-8u171-linux-x64.tar.gz)

**.net版本** dotnet-sdk-2.1<br>
安装:[https://www.microsoft.com/net/learn/get-started/linux/centos](https://www.microsoft.com/net/learn/get-started/linux/centos)

<h1 id="2">二、安装</h1>
**参考文档**<br>
[https://jenkins.io/doc/pipeline/tour/getting-started/](https://jenkins.io/doc/pipeline/tour/getting-started/)

**安装**

	wget http://mirrors.jenkins.io/war-stable/latest/jenkins.war

**运行**

	java -jar jenkins.war --httpPort=8080

至此，可以在8080端口访问jenkins的管理界面。在浏览器访问后，按提示完成初始化操作。插件的话，如果不是很熟悉，按推荐的安装即可，后续可以按需要安装其他插件。安装完插件后，选择性的添加一个管理用户，进入最终的管理页面。

![](https://i.imgur.com/MkBgazX.png)



 
