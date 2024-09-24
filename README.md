# sip-server-gb28181
sip-server-gb28181

### 预备知识
 - [ ]《GBT 28181-2016 公共安全视频监控联网系统信息传输、交换、控制技术要求》
 - [ ] sip ： 使用开源库exosip2
 - [ ] XML ：使用开源库tinyxml
 - [ ] json ：使用开源库nlohmann
 - [ ] http ：使用开源库httplib
 - [ ] C++11

### 开发及运行环境

win10 + VS2020
centos7 + gcc8.2


### 依赖库 
 1. ####  exosip2介绍
|库名  | 功能 |
|--|--|
| Osip2 | 一个开源的SIP协议栈，使用C编写，主要提供解析SIP和SDP消息的API和事物处理的状态机 |
| Exosip2| 是对Osip2协议栈的封装和调用，作为Osip2的一个扩展协议集，使得Osip2更容易被使用|
 2.  ####  编译
 - [centos7.3 编译exosip2 -5.1.0](https://blog.csdn.net/machh/article/details/103276138)
 - [VS2015下编译libeXosip2.5.1](https://blog.csdn.net/machh/article/details/103159346)

 ### GB28181相关 
 - [一个基于GB28181的流媒体平台架构图](https://machh.blog.csdn.net/article/details/112173985)
 - [GB28181国标错误码](https://machh.blog.csdn.net/article/details/91049415)
 - [GB28181系列之--设备注册](https://blog.csdn.net/machh/article/details/103601345)
 - [GB28181系列之--请求实时视频](https://machh.blog.csdn.net/article/details/103586751)
 - [GB28181系列之--录像回放](https://machh.blog.csdn.net/article/details/109063600)
 


