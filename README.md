# wxchatroom
<!-- GFM-TOC -->
- [介绍](#介绍)
- [上手指南](#上手指南)
    - [安装要求](#安装要求)
    - [安装步骤](#安装步骤)
- [文件结构](#文件结构)
- [运行](#运行)
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
- 环境：Windows10		

## 安装要求
- 懂得安装node以及使用其自带的npm工具
- 懂得微信开发工具的使用，比如项目生成与调试	
- 需要安装的软件
	- node
	- 微信开发者工具
	- 浏览器

## 安装步骤
1. [安装：node](https://www.runoob.com/nodejs/nodejs-install-setup.html)
2. 使用控制台cmd，到WebSocketServer目录下输入以下命令：
```
npm install
```
3. [安装：微信开发者工具](https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html)
4. chrome浏览器

# 文件结构
[catalogue.txt](https://github.com/anlzou/wxchatroom/blob/master/catalogue.txt)

# 运行
1. 克隆代码到本地后，进入WebSocketServer目录执行node index.js。
2. 使用 “微信开发者工具” 将 pages/index 目录打开，运行调试即可。
3. 浏览器可以访问WebSocketServer/chat目录中index.html文件。
4. 运行demo图		
![app-登录界面](https://github.com/anlzou/wxchatroom/tree/master/image/app-登录界面.PNG)
![app-聊天界面](https://github.com/anlzou/wxchatroom/tree/master/image/app-聊天界面.PNG)
![web-登录界面](https://github.com/anlzou/wxchatroom/tree/master/image/web-登录界面.PNG)
![web-聊天界面](https://github.com/anlzou/wxchatroom/tree/master/image/web-聊天界面.PNG)

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
1. 功能开发
- [x] [修改web登录界面样式](http://sc.chinaz.com/jiaoben/161019322210.htm#down)
- [x] [修改app登录界面样式](https://blog.csdn.net/W_SSNY/article/details/80431695?depth_1-utm_source=distribute.pc_relevant.none-task&utm_source=distribute.pc_relevant.none-task)
- [x] 修改聊天界面的排版
- [x] 修改用户uid显示
- [x] 添加聊天时间
- [x] 修改目录结构
- [x] 替换图片
- [x] 修改相同用户名也可以登录问题
- [x] 头像
2. 待做
- [ ] 发送图片
- [ ] 添加密码
- [ ] 添加数据库
- [ ] 后台管理