## Luat

Luat = Lua +  AT  

Luat 是合宙（AirM2M）推出的物联网开源架构，依托于通信模块做简易快捷的开发.

其中， Air202/Air208/Air201是一款GPRS模块,Air800是GPRS+GPS+BEIDOU模块。

开源社区：wiki.openluat.com

GitHub：https://github.com/openLuat/Luat_Air202-Air800-Air201

开发套件：https://luat.taobao.com 或 https://openluat.taobao.com



## Luat架构简介


底层软件（也叫基础软件，位于/core）用C语言开发完成，支撑Lua的运行。

上层软件用Lua脚本语言来开发实现，目前有两套架构，分别位于script和script_LuaTask。 


## script和script_LuaTask

script和script_LuaTask是两版上层脚本开发架构：
> 1、script是第一版，整个应用开发仅支持单线程

> 2、script_LuaTask是第二版，基于Lua的协程实现了多线程的支持，相比于第一版script来说，用户编程变得简洁，在此郑重感谢Luat开源技术支持群（QQ群号：201848376）里的“稀饭放姜”大神，正是这位大神，才促成了LuaTask版本的面世

Luat团队会一直同步维护这两个版本，建议新项目使用script_LuaTask版本开发。

## 在线文档

- 如果你想了解script_LuaTask中实现了哪些功能，请点击：
- <<[script_LuaTask lib参考手册](https://htmlpreview.github.io/?https://github.com/zhutianhua/Luat/script_LuaTask/blob/master/doc/lib/index.html)>>
- <<[script_LuaTask demo参考手册](https://htmlpreview.github.io/?https://github.com/zhutianhua/Luat/script_LuaTask/blob/master/doc/demo/index.html)>>

## 下载地址

- 如果你想下载这个项目,请点击：[下载地址](https://github.com/zhutianhua/Luat/archive/master.zip)
