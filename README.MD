# Amazing dotNET Core #

前言留空，目前先行整理 asp.net core 之推荐资源。

以下条目将随时增加或移除。

## NuGet Mirror ##
+ cnblogs NuGet Mirror
    + project homepage http://www.cnblogs.com/Zajanmy/p/6206548.html
    + usage `https://nuget.cnblogs.com/v3/index.json`
+ Lzzy Mirror (thank you, Kation san)
    + project homepage http://nuget.lzzy.net
    + github https://github.com/Kation/NugetProxy
    + usage `http://nuget.lzzy.net/api/v2/`

## NuGet Tools ##
+ NuGet Package Explorer
    + project homepage http://nugetpackageexplorer.github.io/
    + github https://github.com/NuGetPackageExplorer/NuGetPackageExplorer
    + download https://npe.codeplex.com/downloads/get/clickOnce/NuGetPackageExplorer.application

## 1. Useful .NET Core Library ##

+ EntityFramework Core
    + [PomeloFoundation/Lolita](https://github.com/PomeloFoundation/Lolita)<br />*A light-weight extension which provides bulk update and delete operations for Entity Framework Core.*
    + [PomeloFoundation/Pomelo.EntityFrameworkCore.MySql](https://github.com/PomeloFoundation/Pomelo.EntityFrameworkCore.MySql)<br />*Entity Framework Core provider for MySql built on top of mysql-net/MySqlConnector*
    + [PomeloFoundation/Pomelo.EntityFrameworkCore.MyCat](https://github.com/PomeloFoundation/Pomelo.EntityFrameworkCore.MyCat)<br />*Pomelo.EntityFrameworkCore.MyCat is an Entity Framework Core provider and optimized for MyCat (An open source MySQL cluster proxy which based on Cobar)*
+ JavaScriptServices
    + [Getting Started](http://www.cnblogs.com/savorboard/p/dotnet-javascript-services.html)
    + Project homepage https://github.com/aspnet/JavaScriptServices
+ MySQL
    + [PomeloFoundation/Pomelo.Data.MySql](https://github.com/PomeloFoundation/Pomelo.Data.MySql)
+ NPOI.Core
    + [Getting Started](http://www.cnblogs.com/savorboard/p/netcore-npoi.html)
    + Project homepage https://github.com/yuleyule66/Npoi.Core
    + NuGet: https://www.nuget.org/packages?q=Savorboard.NPOI
    + NPOI for nfx: https://github.com/tonyqus/npoi


## 2. Articles and books ##

### 2.1. Gettting Started ###
+ [简析 .NET Core 以及与 .NET Framework 的关系](http://www.cnblogs.com/vipyoumay/p/5603928.html)， *帅虫哥, 2016/6/21*
+ [简析 .NET Core 构成体系](http://www.cnblogs.com/vipyoumay/p/5613373.html)， *帅虫哥, 2016/6/24*
+ [如果没有 Visual Studio 2015，我们如何创建 .NET Core 项目 ？](http://www.cnblogs.com/蒋金楠/p/scaffolding-net-core.html)， *蒋金楠<sup>MVP</sup>, 2016/06/29*
+ [通过几个 Hello World 感受 .NET Core 全新的开发体验](http://www.cnblogs.com/蒋金楠/p/net-core-hello-world.html)， *蒋金楠<sup>MVP</sup>, 2016/06/30*
+ [.NET Core On Mac - Building An ASP.NET Core App With Web API, EF, PostgreSQL And Running It On Docker](https://www.codeproject.com/Articles/1155738/NET-Core-On-Mac-Building-An-ASP-NET-Core-App-With), *Vincent Maverick Durano<sup>MVP</sup>, 2016/11/14*

### 2.2. Concepts ###

#### 2.2.3. Middleware ####
+ [Startup 和 Middleware](http://www.cnblogs.com/vipyoumay/p/5640645.html)， *帅虫哥，2016/07/04*

#### 2.2.4. Inversion of Control and Dependency Injection ####
+ [Wikipedia Entry for Inversion of Control](https://en.wikipedia.org/wiki/Inversion_of_control) *en*
+ [Wikipedia Entry for Dependency Injection](https://en.wikipedia.org/wiki/Dependency_injection) *en*
+ [控制反转（IOC）](http://www.cnblogs.com/蒋金楠/p/asp-net-core-di-ioc.html)， *蒋金楠<sup>MVP</sup>, 2016/04/04*
+ [依赖注入（DI）](http://www.cnblogs.com/蒋金楠/p/asp-net-core-di-di.html)， *蒋金楠<sup>MVP</sup>, 2016/04/04*
+ [服务的注册与提供](http://www.cnblogs.com/蒋金楠/p/asp-net-core-di-register.html)， *蒋金楠<sup>MVP</sup>, 2016/04/06*
+ [构造函数的选择与服务生命周期管理](http://www.cnblogs.com/蒋金楠/p/asp-net-core-di-life-time.html)， *蒋金楠<sup>MVP</sup>, 2016/04/10*
+ [ServiceProvider 实现的总体设计](http://www.cnblogs.com/蒋金楠/p/asp-net-core-di-service-provider-1.html)、[ServiceCallSite](http://www.cnblogs.com/蒋金楠/p/asp-net-core-di-service-provider-2.html)与[其他](http://www.cnblogs.com/蒋金楠/p/asp-net-core-di-service-provider-3.html)， *蒋金楠<sup>MVP</sup>, 2016/04/11~16*

### 2.3 ASP.NET Core ###

#### 2.3.1 Getting Started ####
+ [ASP.NET Core: A More Realistic Starter Kit](https://www.simple-talk.com/dotnet/asp-net/asp-net-core-a-more-realistic-starter-kit/), *Dino Esposito, 2016/3/25*
+ [如何使用 HttpContext.Current](http://www.cnblogs.com/maxzhang1985/p/6186455.html), *max zhang, 2016/12/16*


#### 2.3.3 Middleware ####
+ [ASP.NET Core 中间件之压缩、缓存](http://www.cnblogs.com/savorboard/p/aspnetcore-response-compression-caching.html)， *Savorboard, 2016/12/13*

#### 2.3.4 Dependency Injection ####
+ [学习 ASP.NET Core，你必须了解无处不在的“依赖注入”](http://www.cnblogs.com/蒋金楠/p/dependency-injection-in-asp-net-core.html)， *蒋金楠<sup>MVP</sup>, 2016/07/04*

#### 2.3.5 Asp.Net Core x Front-End ####

##### 2.3.5.1 AngularJs 2 #####
+ [ASP.NET Core: Getting Started with AngularJS 2](https://www.codeproject.com/Articles/1105223/ASP-NET-Core-Getting-Started-with-AngularJS), *Vincent Maverick Durano<sup>MVP</sup>, 2016/6/30* *en*
+ [ASP.NET Core and Angular 2 Code Venture - Part 1](https://www.codeproject.com/articles/1124864/asp-net-core-and-angular-code-venture-part), *Vincent Maverick Durano<sup>MVP</sup>, 2016/10/13* *en*

#### 2.3.7 Publishing and Deployment ####
+ [Jexus 发布与部署](http://www.cnblogs.com/savorboard/p/dot-net-linux-jexus.html)，*Savorboard, 2016/07/04*
+ [Nginx 发布与部署](http://www.cnblogs.com/savorboard/p/dotnet-core-publish-nginx.html)，*Savorboard, 2016/07/04*
+ [Docker 部署](http://www.cnblogs.com/savorboard/p/dotnetcore-docker.html)，*Savorboard, 2016/07/11*


### 2.4 Projects ###
+ [.NET Core 环境搭建和命令行 CLI 入门](http://www.cnblogs.com/shanyou/p/5636920.html)，*张善友<sup>MVP</sup>, 2016/07/04*
+ [project.json、project.lock.json、*.xproj  以及 global.json](http://www.cnblogs.com/shanyou/p/5693453.html)，*张善友<sup>MVP</sup>, 2016/07/22*
+ [project.json 引用](https://docs.microsoft.com/zh-cn/dotnet/articles/core/tools/project-json)
+ [global.json 引用](https://docs.microsoft.com/zh-cn/dotnet/articles/core/tools/global-json)

### 2.5 Skills and Tools using ###
#### 2.5.1 ASP.NET Identity ####
+ [ASP.NET Core 之 Identity 入门（一）](http://www.cnblogs.com/savorboard/p/aspnetcore-identity.html)，*Savorboard, 2016/11/04*
+ [ASP.NET Core 之 Identity 入门（二）](http://www.cnblogs.com/savorboard/p/aspnetcore-identity2.html)，*Savorboard, 2016/11/11*
+ [ASP.NET Core 之 Identity 入门（三）](http://www.cnblogs.com/savorboard/p/aspnetcore-identity3.html)，*Savorboard, 2016/11/25*

#### 2.5.2 WebSocket #####
+ [WebSocket in ASP.NET Core](http://www.cnblogs.com/maxzhang1985/p/6208165.html)，*max zhang, 2016/12/21*

...

### 2.7. CLR ###
+ [Book of the Runtime](https://github.com/dotnet/coreclr/blob/master/Documentation/botr/README.md) (ebook) *en*
    + [Introduction to the Common Language Runtime](https://github.com/dotnet/coreclr/blob/master/Documentation/botr/intro-to-clr.md) *en*
    + [Garbage Collection Design](https://github.com/dotnet/coreclr/blob/master/Documentation/botr/garbage-collection.md) *en*
    + [RyuJIT Overview](https://github.com/dotnet/coreclr/blob/master/Documentation/botr/ryujit-overview.md) *en*
    + [Type System](https://github.com/dotnet/coreclr/blob/master/Documentation/botr/type-system.md) *en*
+ [公共语言运行时 (CLR)](https://msdn.microsoft.com/library/8bs2ecf4.aspx)

* * *

## Feedback ##

0. dotNET Core Studying Group QQ 群：436035237
1. CODE:8192 程序员的生活01 QQ 群：56682236
