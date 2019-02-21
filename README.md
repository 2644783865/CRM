# CRM
ASP.net Core 2.2+WebAPI+Dapper+MySql+vue.js(MVVM)+Element ui+identityServer4
============================================================================
用VS2017创建ASP.net Core2.2+WebAPI项目
-------------------------------------
* 下载安装：[VisualStudioS2017 社区版](https://visualstudio.microsoft.com/zh-hans/downloads/)
* 下载安装：[.NET Core 2.2](https://dotnet.microsoft.com/download)
* 启动程序：VS2017，选择文件-新建-项目
* 主菜单选择：Web->ASP.NET Core Web 应用程序
* 对话框选择：.NET Core->ASP.NET Core 2.2->API
此时程序已经可以运行，将在浏览器上显示
```
["value1","value2"]
```
增加DAL层并安装MySQL和Dapper
---------------------------
* 启动程序：VS2017，打开CRM解决方案
* 鼠标右击：解决方案资源管理器->解决方案"CRM"
* 弹出菜单中选择：添加->新建项目->已安装->Visual C#->.NET Core->类库(.NET Core)，输入名称：DAL
* 鼠标右击项目：DAL->管理NuGet程序包->浏览
* 输入：“Dapper”，选择搜索结果中的第一个项目进行安装
* 下载安装：[MySQL Community Server](https://dev.mysql.com/downloads/)
