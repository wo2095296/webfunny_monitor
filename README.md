 ### 前言
   怎样定位前端线上问题，一直以来，都是很头疼的问题，因为它发生于用户的一系列操作之后。错误的原因可能源于机型，网络环境，复杂的操作行为等等，在我们想要去解决的时候很难复现出来，自然也就无法解决。 当然，这些问题并非不能克服，让我们来一起看看如何去监控并定位线上的问题吧。
   

 ### 部署
![total gzip size](https://img.badgesize.io/https://www.webfunny.cn/resource/monitor.fetch.min.js?compression=gzip&label=total%20gzip%20size)
   
只需要简单几步就可以搭建一套属于自己的前端监控系统，欢迎关注和Star。


[【Demo效果】](http://www.webfunny.cn/demo/home.html) | [【部署教程】](https://github.com/a597873885/webfunny_monitor/blob/master/DES.md) |【微信号】webfunny_2020
   
   
---------------------------------------------------------

### 主体功能
1. 实时掌握项目的健康状态，PV/UV、报错、用户分布。

2. 精细化分析每一个报错问题，支持sourceMap源码定位。

3. 深入分析每一个用户，记录下每个用户的所有行为。

4. 分析页面和接口性能，加载耗时，成功率。

5. 强大的调试功能，让你从繁杂的调试工具中解脱出来。


### 目录结构
         ./schema  数据库建表结构
         ./views/ 前端展示代码
         ./config  数据库配置目录
         ./logs  运行报错日志目录
         ./config.js 接口配置文件


