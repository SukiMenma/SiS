# SiS
[![Build status](https://ci.appveyor.com/api/projects/status/5m4fip2k59kurfcn?svg=true)](https://ci.appveyor.com/project/Tnze/sis)  
MC服务器综合管理插件，主要提供白名单管理和状态查询(ping)功能。
支持onebot协议采用正向websocket

用法与配置请查看[Wiki](https://github.com/miaoscraft/SiS/wiki)

## 功能
本插件适用于包括原版服务端在内的各种MC服务端。
1. 白名单  
群员可以自助获得白名单，游戏名经Mojang服务器验证后通过RCON发送到游戏服务器进行添加。  
玩家主动或被动退群时，将被自动从白名单中移除。
2. Ping  
可在群内ping游戏服务器，查看延迟以及在线玩家。  
~~我们经常拿来判断是自己网络不好还是服务器崩了~~。
3. 自定义指令  
在配置文件中预先写好指令，然后在Q群内调用。  
拥有简单明了的权限系统用于保证命令不被恶意执行。

## 鸣谢
感谢他们⬇️对SiS的付出

[Tnze](https://github.com/Tnze)（开发者）  
[fcc](https://github.com/Amazefcc233)（测试，提示语优化，文案，社区发布，装可爱）  
[柏喵](https://github.com/MscBaiMeow)（提示语优化，迁移到simplebot）  
[Miaoscraft](https://miaoscraft.cn)（感谢相遇）  

## 依赖
感谢下列项目，没有它们SiS不将诞生

- Go语言 https://golang.org
- MC协议文档 https://wiki.vg
- go-mc库 https://github.com/Tnze/go-mc
- SimpleBot机器人 https://github.com/BaiMeow/SimpleBot
- onebot协议 https://github.com/botuniverse/onebot
- SQLite驱动 https://github.com/mattn/go-sqlite3
- MySQL驱动 https://github.com/go-sql-driver/mysql
- Toml配置文件 https://github.com/BurntSushi/toml