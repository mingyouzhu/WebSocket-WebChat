#### 模块介绍：  
利用bootstrap实现聊天主界面开发。通过WebSocket协议实现浏览器的大厅聊天以及一对一聊天。    

#### 整个项目包含：
1、WebChat： ASP.NET的MVC模式实现聊天网站（https://github.com/KevinBetterQ/WebSocket-WebChat
）  
2、WebSocket-Server： C#实现的WebSocket的服务器端  （https://github.com/KevinBetterQ/WebSocket-Server
）  
3、AndChat： Android客户端实现代码  （https://github.com/KevinBetterQ/WebSocket-AndChat
）  

具体参考：http://blog.csdn.net/kevinbetterq/article/details/76861899  


#### 开发环境：
Visual Studio 2013 + Android Studio

## 整个项目介绍
### 1需求分析
#### 1.1基本功能需求
1.基于 Websocket协议，使用C#语言写一个B/S聊天小程序  
2.实现用户的注册登录，并进行数据库有效管理  
3.使用一种设计模式
#### 1.2各模块功能需求
1、WebSocket客户端  
利用bootstrap实现聊天主界面开发。通过WebSocket协议实现浏览器的大厅聊天以及一对一聊天。  
2、c#服务器模块  
利用C#语言自己实现了一个WebSocket的服务器，对协议进行解析，并对聊天信息的发送进行管理。  
3、Android手机端  
利用WebView控件实现Android端的聊天。同时利用JavaScript与Java的交互编程实现手机端的用户管理。  
4、用户注册登录模块  
网站采用MVC设计模式，实现用户的注册与登录功能，并进行数据库操作。

### 2设计说明
#### 2.1系统结构
![image](http://img.blog.csdn.net/20170807215944054?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvS2V2aW5CZXR0ZXJR/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center)
#### 2.2模块介绍
![image](http://img.blog.csdn.net/20170807215936029?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvS2V2aW5CZXR0ZXJR/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center)
