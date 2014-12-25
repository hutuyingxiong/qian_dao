门禁／签到系统
==========
###此系统是为我学校的创新实验室做的一个门禁系统###


**初衷很简单：**

1. 每个人都可随时来到实验室，忙自己的事情，不必等待掌握钥匙的同学

2. 之前掌握钥匙的同学有时间忙自己的事情，不需要每当有同学需要进入实验室的时候，都要来开门

>既然要做系统，肯定要正儿八经的了


**实现的功能：**



- **门禁功能：**校园一卡通作为钥匙，成为进入实验室的通行证，并且每次记录进门时间，增加实验室安全系数
- **签到功能：**每次进入／离开实验室，进行刷卡考勤，便于以后统计出勤时间加学分．
- **环境监测：**拓展功能，可记录实验室各项环境数据，未来会增加短信报警功能（如火灾等其他可监测意外事件）．


**系统框架示意图：**
![系统示意图](http://ww4.sinaimg.cn/large/005yyi5Jjw1en7ccjlcdlj30q80i6tam.jpg)

**相关技术：**
- [Workerman](https://github.com/walkor/workerman) 服务器端框架　感谢[@Walkor](https://github.com/walkor)(此框架给我省了好多的力气，这也是我开源此项目的原因，并且以后更多的项目也要开源)


**使用说明：**

- arduino 文件夹放的是arduino的一些程序源码

- library 文件夹是放的arduino中用到的库文件

- server 文件夹放的是workerman的一些为这个项目修改过的文件

- pc 文件夹中放的是pc端管理软件源码（分工合作，团队伙伴正在写，暂未上传）

- sql 文件夹中放的是MySql数据库结构表（暂未上传）


**支持和协作**  

- 开源项目欢迎大家使用和移植。

- 欢迎大家来一起完善项目，增强其安全性和实用性。

**关于我**

我的博客


[Leon's Blog](http://leon.wxitsky.com)

[Leon's Lofter](http://leon-0516.lofter.com)
