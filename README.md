# RSVP-路由交换虚拟实验平台

**1.1** **项目背景**

近年来，MOOC、SPOC等形式的在线开放课程教学发展迅速，在线教学已经成为高等学校教学的重要组成部分。很多学校开设了网络工程类的在线开放课程，学生可以通过观看教学微视频和教学课件，完成在线测试和作业等方式进行课程的学习。目前，网络工程类在线开放课程存在重理论教学，缺乏在线实验教学平台的问题。本设计就是基于这个需求提出，目的是开发在线路由交换虚拟实验平台，学生可以在这个在线实验平台上构建虚拟的路由交换实验环境，完成路由交换类的实验任务。

**1.2** **面向用户**

本实验平台主要面向计算机网络专业的师生，服务于计算机网络类实验课程的教学。

**1.3** **主要功能需求**

（1）构建网络拓扑

教师和学生可以在这个在线实验平台上创建路由器、交换机、计算机等网络设备，选择相应端口连接双绞线、串口线等网络线缆，从而构建网络拓扑。

（2）仿真命令配置

模拟锐捷设备构建命令词库。通过命令来切换网络设备的各种模式，利用命令来打开关闭网络设备上的相应接口，配置接口的ip地址。最终，用户可以通过手动配置命令来实现网络设备之间的连通。

（3）自主学习实践

学生通过实验指导，自由创建不同的网络拓扑文件，自主完成实验。实践学习理论。

（4）小组协作

可以通过本平台创建小组或加入其它的小组，实时在线协作，共同完成实验内容。

**1.4**  **项目截图**

（1）输入网址进入首页，桥意味着路由连通。

![1580149958423](http://picture.zyuhn.top/myblog/githubpage的readme/20200128023239-618801.png)

（2）点击start按钮进入登陆页面，尚未注册用户，进入注册页面，输入用户名、电话、密码、再次确认密码。

![1580150073479](http://picture.zyuhn.top/myblog/githubpage的readme/20200128023434-841972.png)

（3）登陆成功后进入个人中心，个人中心分别有我的文件页面、与我协作、实验教程、实验工具、回收站。

![1580150124399](http://picture.zyuhn.top/myblog/githubpage的readme/20200128023525-841252.png)

（4）点击新建，创建拓扑实验。进入编辑器界面。从左侧设备区选择两个设备，拖拽到编辑区，选择线缆类型、左击编辑区一个设备选择相应端口，再左击另一个设备选择一个设备完成连线。

![1580150144930](http://picture.zyuhn.top/myblog/githubpage的readme/20200128023546-259505.png)

（5）使用工具编辑已经创建好的拓扑图，编辑器右侧可以查看网络设备的一些信息右击设备，显示菜单，打开命令窗口，输入正确命令配置一个路由器的fa0/0端口。

![1580150176622](http://picture.zyuhn.top/myblog/githubpage的readme/20200128023617-199575.png)

**1.5**  **项目演示**

[http://picture.zyuhn.top/rsvp.mp4](http://picture.zyuhn.top/rsvp.mp4)
