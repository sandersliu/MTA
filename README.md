#MTA

An unofficial MTA SDK Cocoapods repository..

Source website: [http://mta.qq.com/](http://mta.qq.com/)


腾讯MTA项目组太TM懒了吧？连个Cocoapods都不肯做一下！连个在线文档都不肯做，真TM服了...

#Usage

Edit your podfile: `pod 'MTA'`

Read more usage: [http://imgcache.xg.qq.com/mta/document/iOS_quick_start.zip](http://imgcache.xg.qq.com/mta/document/iOS_quick_start.zip)

#Release notes

##2016

###01.13

1. 修复崩溃报告部分符号丢失的问题

##2015

###12.24

1. 提高网络测速稳定性
2. debug模式下，终端输出写入本地log

###11.11

1. 增加用户反馈接口
2. 提高SDK稳定性

###10.15

1. 更新：优化联调环境

###10.12

1. 针对iOS9增加bitcode支持

###08.26

1. 设备位置信息上报
2. 设备位置信息查询

###08.18

1. 基础统计SDK文档更新对引用框架的描述

###08.06

1. 新增SocialLBS SDK

###07.06

1. 增加云Talk SDK，包括以下功能 : 单聊、群聊，文字、图片、语音聊天。

###05.25

1. 解决如果app的bundle id命名不正确,会导致crash的bug
2. 文档更新：增加了对集成SDK细节的补充。

###01.26

1. 支持crash日志半符号化，显示更多函数信息

##2014

###09.25

1. 补齐1.4.0缺失的两个错误统计的字段(剩余内存，剩余空间)

###09.15

1. 支持arm64架构编译
2. 解决极端情况下出现重复上报的问题

###09.09

1. 增加错误上报的详情信息。(进程名，剩余内存，剩余空间)
07.15
1. 支持部分接口指定appkey上报
2. 支持部分接口实时上报
3. 支持服务器端下发配置来禁用MTA
4. 增加reportAccount接口(reportQQ增强版)

###03.11

1. 修复1.2.6引入的bug，该bug导致指标"活跃用户数"不准确

###02.13

1. 调整IDFA的采集策略，取消上报

###01.16

1. 优化加密解密算法
2. 增加设备唯一标识和wifi信息
3. 优化MTA-DEMO小部分代码

##2013

###12.25

1. 新增用户文档，MTA高级游戏模型开发指南

###11.28

1. 启动上报优化，修复缓存在本地下次上报的bug

###11.21

1. 解决json库的函数冲突

###11.05

1. 新增网速监控

###08.14

1. 修改上报策略接口名，防止名字冲突
2. 缓存MTA初始化未完成时调用其它接口的上报事件
3. reportAppMonitorStat接口内存泄露问题

###07.23

1. 增加所有API的SDK初始化判断
2. 只嵌入初始化调用时，产生一次sessionenv

###07.10

1. 修复内存泄漏问题

###07.03

1. ui字段统一上报openudid
2. 增加ifa， ifv字段上报
3. 应用版本号上报改为CFBunderShortVersionString取值

###06.17

1. 新增游戏统计接口
2. 限制上报长度

###05.17

1. 优化接口，本地crash上报

###05.08

1. 兼容性检测与保护

###04.11

1. 接口监控功能
2. 单个session产生消息的次数限制

###03.26

1. 新增页面来源字段“rf”
2. 优化上报策略

###02.22

1. 新增SDK与服务器的错误应答
2. 修复新用户升级的问题

###01.22

1. 支持SDK休眠配置更新

###01.14

1. iOS6 用IFA字段填充ui字段

###01.08

1. 增加携带Key-Value参数的自定义事件

###01.04

1. 上传统计数据支持加密
2. 增加Demo，文档

##2012

###12.25

1. 初始化版本
