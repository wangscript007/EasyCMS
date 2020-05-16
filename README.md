# Altas.Framework 又名：EasyCms
&emsp;&emsp;Atlass 后台管理系统 基于Asp.net Core的后台快速开发框架，可用于快速开发企业后台管理系统，企业站，微信公众号和小程序后台。
## 发展目标
&emsp;&emsp;原来目标是实现一个适合自己公司项目的基础开发框架，发现没有什么动力，不如实现一个产品化的项目就叫做EasyCms吧。  
 &emsp;&emsp;由于本人近两年一直在为政府部门做CMS系统，所以目标是实现一个完善的cms系统。  
 **目标客户为：大部分企业建站需求，政府部门，事业单位使用的CMS管理系统**
## 技术介绍
+ 基于Aspnet core3.1  
+ ORM使用FreeSql,默认使用mysql数据库
+ 后台模板使用H+，如果有赞助的话，后期买个admui替换掉。
+ 静态页面生成模板引擎：[VTemplate.Engine](https://github.com/jasonyush/VTemplate.Engine)
+ 定时任务采用hangfire
## 演示地址：
 http://182.43.178.216:9090/admin  
 用户名：test，密码：123123  
 本地超级管理员 admin 123123
## 依赖环境
asp.net core3.1, redis,mysql
## 功能列表（只列出CMS模块的）
+ [x] 栏目管理
+ [x] 文章管理
+ [x] 模板管理
+ [ ] 模板匹配
+ [x] 静态页面生成（开源版本不直接提供完全生成静态页面html,需要自己做调整，生成静态页面功能已经实现，只是没有直接保存为静态页面html,稍作调整即可实现完全静态访问）
+ [ ] 后台管理ip访问限制
+ [ ] 前台ip访问限制
+ [ ] 站点总访问量，在线人数统计
+ [ ] 栏目权限，文章数据权限
+ [ ] 通讯录
+ [ ] 会议管理
+ [ ] 意见反馈
+ [ ] 前台用户中心(这个功能感觉不是很必要，除非需要实现普通用户投稿)
## [更新日志(详细)](Update.md) 
## 2020-05-16
1. 内容管理
2. 栏目管理
3. 模板管理
## 2020-05-11
 1. 升级到asp.net core 3.1  
 2. 重写定时任务   
 3. 架构拆分，部分重构  
 4. orm框架更新为Freesql  
 5. 页面按钮全部更改为权限控制  
 6. 日志框架更新为serilog,增加异常写数据库  
 7. 重构RequestHelper类库  
 8. 开启日常更新，增加CMS功能  