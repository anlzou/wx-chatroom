# wxchatroom
<!-- GFM-TOC -->
- [介绍](#介绍)
- [上手指南](#上手指南)
    - [安装要求](#安装要求)
    - [安装步骤](#安装步骤)
- [文件结构](#文件结构)
- [部署](#部署)
- [使用到的框架](#使用到的框架)
- [贡献者](#贡献者)
- [版本控制](#版本控制)
- [作者](#作者)
- [版权说明](#版权说明)
- [鸣谢](#鸣谢)
- [更新日志](#更新日志)
<!-- GFM-TOC -->

# 介绍
非常简单的socket.io聊天室，同时支持微信小程序终端，和浏览器客户端。
# 上手指南
环境：Windows10		
demo图	
![app-登录界面](https://github.com/anlzou/wxchatroom/tree/master/image/app-登录界面.PNG)
![app-聊天界面](https://github.com/anlzou/wxchatroom/tree/master/image/app-聊天界面.PNG)
![web-登录界面](https://github.com/anlzou/wxchatroom/tree/master/image/web-登录界面.PNG)
![web-聊天界面](https://github.com/anlzou/wxchatroom/tree/master/image/web-聊天界面.PNG)


## 安装要求
- 懂得安装node以及使用其自带的npm工具
- 懂得微信开发工具的使用，比如项目生成与调试	
- 需要安装的软件
	- node
	- 微信开发者工具
	- 浏览器

## 安装步骤
一步一步地说明怎么去搭建环境，怎么让项目跑起来。首先你需要：
1. [安装：node](https://www.runoob.com/nodejs/nodejs-install-setup.html)
1. [安装：微信开发者工具](https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html)
1. chrome浏览器

# 文件结构
[catalogue.txt](https://github.com/anlzou/wxchatroom/blob/master/catalogue.txt)

# 部署
1. 克隆代码到本地后，进入WebSocketServer目录执行node index.js。
2. 使用 “微信开发者工具” 将 weapp_demo 目录打开，运行调试即可。
3. 浏览器可以访问WebSocketServer/chat目录中index.html文件。

# 使用到的框架
1. socket.io - 通信框架

# 贡献者
> 请阅读 *CONTRIBUTING.md* 查阅为该项目做出贡献的开发者。

# 版本控制
*git*

# 作者
anlzou      
*您也可以在贡献者名单中参看所有参与该项目的开发者。*

# 版权说明
> 该项目签署了xxx 授权许可，详情请参阅 *LICENSE.md*

# 鸣谢
参考[wx-socket.io](https://github.com/w469849848/wx-socket.io)

# 更新日志
## V1.0.0 版本，2020-3-2
1. 新功能：
2. 新功能：
3. 修改：