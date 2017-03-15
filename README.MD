# Amazing dotNET Core #

前言留空，目前先行整理 asp.net core 之推荐资源。

以下条目将随时增加或移除。

[What's new in ASP.NET Core 1.1?](http://www.cnblogs.com/shanyou/p/6092372.html)

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
    + [使用 JavaScriptService 在 .NET Core 里实现 DES 加密算法](http://www.cnblogs.com/shanyou/p/6014352.html), *张善友<sup>MVP</sup>, 2016/11/1*
+ MySQL
    + [PomeloFoundation/Pomelo.Data.MySql](https://github.com/PomeloFoundation/Pomelo.Data.MySql)
+ System.Drawing
    + ZKWeb.System.Drawing
        + project homepage https://github.com/zkweb-framework/zkweb.system.drawing
        + nuget: https://www.nuget.com/packages/ZKWeb.System.Drawing
    + ImageProcessor
        + project homepage http://imageprocessor.org
        + project homepage https://github.com/JimBobSquarePants/ImageProcessor/
        + nuget: https://www.nuget.com/packages/ImageProcessor/
+ NPOI.Core
    + [Getting Started](http://www.cnblogs.com/savorboard/p/netcore-npoi.html)
    + Project homepage https://github.com/yuleyule66/Npoi.Core
    + NuGet: https://www.nuget.org/packages?q=Savorboard.NPOI
    + NPOI for nfx: https://github.com/tonyqus/npoi
+ RestSharp
    + [Getting Started](http://restsharp.org)
    + NuGet: http://www.nuget.org/packages/RestSharp
    + RestSharp for nfx: http://restsharp.org
+ SharpZibLib
    + Project homepage: https://github.com/icsharpcode/SharpZipLib
    + NuGet: http://www.nuget.org/packages/SharpZipLib.NETStandard/
    + SharpZibLib for nfx: http://www.nuget.org/packages/SharpZipLib/
+ QRCode
    + project home: https://github.com/zkweb-framework/QRCode
    + nuget: https://www.nuget.com/packages/ZKWeb.Fork.QRCode

## 2. Articles and books ##

### 2.1. Gettting Started ###
+ [What is .NET Core?](http://www.cnblogs.com/Wddpct/p/5694596.html)
+ [The architecture of .NET Core](http://www.cnblogs.com/vipyoumay/p/5613373.html)， *帅虫哥, 2016/6/24*
+ [The relationship between .NET Core, .NET Framework](http://www.cnblogs.com/vipyoumay/p/5603928.html) [and mono](http://www.cnblogs.com/shanyou/p/4295163.html)
+ [Without Visual Studio 2015, how we can build .NET Core project?](http://www.cnblogs.com/artech/p/scaffolding-net-core.html)， *蒋金楠<sup>MVP</sup>, 2016/06/29*
+ [通过几个 Hello World 感受 .NET Core 全新的开发体验](http://www.cnblogs.com/artech/p/net-core-hello-world.html)， *蒋金楠<sup>MVP</sup>, 2016/06/30*
+ [.NET Core On Mac - Building An ASP.NET Core App With Web API, EF, PostgreSQL And Running It On Docker](https://www.codeproject.com/Articles/1155738/NET-Core-On-Mac-Building-An-ASP-NET-Core-App-With), *Vincent Maverick Durano<sup>MVP</sup>, 2016/11/14*

### 2.2. Concepts ###

#### 2.2.3. Middleware ####
+ [Startup and Middleware](http://www.cnblogs.com/vipyoumay/p/5640645.html)， *帅虫哥，2016/07/04*

#### 2.2.4. Inversion of Control and Dependency Injection ####
+ [Wikipedia Entry for Inversion of Control](https://en.wikipedia.org/wiki/Inversion_of_control) *en*
+ [Wikipedia Entry for Dependency Injection](https://en.wikipedia.org/wiki/Dependency_injection) *en*
+ [控制反转（IOC）](http://www.cnblogs.com/artech/p/asp-net-core-di-ioc.html)， *蒋金楠<sup>MVP</sup>, 2016/04/04*
+ [依赖注入（DI）](http://www.cnblogs.com/artech/p/asp-net-core-di-di.html)， *蒋金楠<sup>MVP</sup>, 2016/04/04*
+ [服务的注册与提供](http://www.cnblogs.com/artech/p/asp-net-core-di-register.html)， *蒋金楠<sup>MVP</sup>, 2016/04/06*
+ [构造函数的选择与服务生命周期管理](http://www.cnblogs.com/artech/p/asp-net-core-di-life-time.html)， *蒋金楠<sup>MVP</sup>, 2016/04/10*
+ [ServiceProvider 实现的总体设计](http://www.cnblogs.com/artech/p/asp-net-core-di-service-provider-1.html)、[ServiceCallSite](http://www.cnblogs.com/artech/p/asp-net-core-di-service-provider-2.html)与[其他](http://www.cnblogs.com/artech/p/asp-net-core-di-service-provider-3.html)， *蒋金楠<sup>MVP</sup>, 2016/04/11~16*
+ [必备 .NET - 使用 .NET Core 实现依赖关系注入](https://msdn.microsoft.com/magazine/mt707634), *Mark Michaelis<sup>MVP</sup>, 2016/6*

### 2.3 ASP.NET Core ###

#### Getting Started ####
+ [ASP.NET Core: A More Realistic Starter Kit](https://www.simple-talk.com/dotnet/asp-net/asp-net-core-a-more-realistic-starter-kit/), *Dino Esposito, 2016/3/25*
+ [ASP.NET Core 项目解读](http://www.cnblogs.com/Wddpct/p/5713986.html), *白细胞, 2016/7/28*
+ [How to use HttpContext.Current](http://www.cnblogs.com/maxzhang1985/p/6186455.html), *max zhang, 2016/12/16*

#### Middleware ####
+ [ASP.NET Core 中间件之压缩、缓存](http://www.cnblogs.com/savorboard/p/aspnetcore-response-compression-caching.html)， *Savorboard, 2016/12/13*

#### Configuration ####
+ [必备 .NET - .NET Core 中的配置](https://msdn.microsoft.com/magazine/mt632279), *Mark Michaelis<sup>MVP</sup>, 2016/2*
+ [ASP.NET Core 的配置：读取配置信息](http://www.cnblogs.com/artech/p/asp-net-core-config-01.html), *蒋金楠<sup>MVP</sup>, 2016/4/17*
+ [ASP.NET Core 的配置：配置模型详解](http://www.cnblogs.com/artech/p/asp-net-core-config-02.html), *蒋金楠<sup>MVP</sup>, 2016/4/19*
+ [ASP.NET Core 的配置：将配置绑定为对象（上）](http://www.cnblogs.com/artech/p/asp-net-core-config-03.html), *蒋金楠<sup>MVP</sup>, 2016/4/20*
+ [ASP.NET Core 的配置：将配置绑定为对象（下）](http://www.cnblogs.com/artech/p/asp-net-core-config-04.html), *蒋金楠<sup>MVP</sup>, 2016/4/21*
+ [ASP.NET Core 的配置：多样性的配置来源（上）](http://www.cnblogs.com/artech/p/asp-net-core-config-4-1.html), *蒋金楠<sup>MVP</sup>, 2016/4/25*
+ [ASP.NET Core 的配置：多样性的配置来源（中）](http://www.cnblogs.com/artech/p/asp-net-core-config-4-2.html), *蒋金楠<sup>MVP</sup>, 2016/4/26*
+ [ASP.NET Core 的配置：多样性的配置来源（下）](http://www.cnblogs.com/artech/p/asp-net-core-config-4-3.html), *蒋金楠<sup>MVP</sup>, 2016/4/27*
+ [ASP.NET Core 的配置：配置的同步（上）](http://www.cnblogs.com/artech/p/asp-net-core-config-5-1.html), *蒋金楠<sup>MVP</sup>, 2016/5/9*
+ [ASP.NET Core 的配置：配置的同步（上）](http://www.cnblogs.com/artech/p/asp-net-core-config-5-2.html), *蒋金楠<sup>MVP</sup>, 2016/5/11*

#### Tag Helpers ####
+ [MVC Core 1.0 的 Tag Helper](https://dotblogs.com.tw/aspnetshare/2016/08/01/20160731-customtaghelperbasic)，*中华人民共和国台湾省匿名网友, 2016/8/1*
+ [MVC Core 1.0 的 Tag Helper（續）](https://dotblogs.com.tw/aspnetshare/2016/08/15/20160814-mvctaghelper-p2)，*中华人民共和国台湾省匿名网友, 2016/8/15*

#### Dependency Injection ####
+ [学习 ASP.NET Core，你必须了解无处不在的“依赖注入”](http://www.cnblogs.com/artech/p/dependency-injection-in-asp-net-core.html)， *蒋金楠<sup>MVP</sup>, 2016/07/04*
+ [避免在 ASP.NET Core 中使用服务定位器模式](http://www.cnblogs.com/redmoon/p/5205488.html), *朱永光<sup>MVP</sup>, 2016/2/21*
    + [Avoiding the Service Locator Pattern in ASP.NET Core](http://odetocode.com/blogs/scott/archives/2016/2/18/avoiding-the-service-locator-pattern-in-asp-net-core.aspx), *K. Scott Allen, 2016.2.18* *en*
    + [Service Locator is na Anti-Pattern](http://blog.ploeh.dk/2010/02/03/ServiceLocatorisanAnti-Pattern/),*Mark Seemann, 2010/2/3* *en*

#### Publishing and Deployment ####
+ [Jexus 发布与部署](http://www.cnblogs.com/savorboard/p/dot-net-linux-jexus.html)， *Savorboard, 2016/07/04*
    + [Jexus 5.8.2 为 Asp.Net Core 为生产环境提供平台支持](http://www.cnblogs.com/shanyou/p/jexus582.html), *张善友<sup>MVP</sup>, 2016/11/28*
+ [Nginx 发布与部署](http://www.cnblogs.com/savorboard/p/dotnet-core-publish-nginx.html)，*Savorboard, 2016/07/04*
+ [Docker 部署](http://www.cnblogs.com/savorboard/p/dotnetcore-docker.html)，*Savorboard, 2016/07/11*
+ [在传统 .NET Framework 上运行 ASP.NET Core 项目](http://www.cnblogs.com/shanyou/p/6036574.html), *张善友<sup>MVP</sup>, 2016/11/7*


### 2.4 Projects ###
+ [.NET Core 环境搭建和命令行 CLI 入门](http://www.cnblogs.com/shanyou/p/5636920.html), *张善友<sup>MVP</sup>, 2016/07/04*
+ [.NET Core 迁移到 MSBuild 指南（一）](http://dotnet.ren/2017/02/28/Core%E8%BF%81%E7%A7%BB%E5%88%B0MSBuild%E7%9A%84%E5%A4%9A%E5%B9%B3%E5%8F%B0%E7%BC%96%E8%AF%91%E9%97%AE%E9%A2%98/)、[（二）](http://dotnet.ren/2017/03/14/project-json-to-csproj/), *Yoyofx, 2017/03/14*
### 2.5 Skills and Tools using ###
#### ASP.NET Identity ####
+ [ASP.NET Core 之 Identity 入门（一）](http://www.cnblogs.com/savorboard/p/aspnetcore-identity.html)，*Savorboard, 2016/11/04*
+ [ASP.NET Core 之 Identity 入门（二）](http://www.cnblogs.com/savorboard/p/aspnetcore-identity2.html)，*Savorboard, 2016/11/11*
+ [ASP.NET Core 之 Identity 入门（三）](http://www.cnblogs.com/savorboard/p/aspnetcore-identity3.html)，*Savorboard, 2016/11/25*

#### Autofac ####
+ [Autofac in ASP.NET Core](http://docs.autofac.org/en/lastest/integration/aspnetcore.html) *en*

#### EntrtyFramework Core ####
+ [How EFCore creates DbContext instance?](http://www.cnblogs.com/CreateMyself/p/6224141.html), *JeffckyWang, 2016/12/27*
+ [Add/Attach/Update/Remove 方法使用详解](http://www.cnblogs.com/CreateMyself/p/6238455.html), *JeffckyWang, 2016/12/31*
+ [Raw SQL](http://www.cnblogs.com/CreateMyself/p/6254241.html), *JeffckyWang, 2017/1/6*

#### AngularJs 2 ####
+ [ASP.NET Core: Getting Started with AngularJS 2](https://www.codeproject.com/Articles/1105223/ASP-NET-Core-Getting-Started-with-AngularJS), *Vincent Maverick Durano<sup>MVP</sup>, 2016/6/30* *en*
+ [ASP.NET Core and Angular 2 Code Venture - Part 1](https://www.codeproject.com/articles/1124864/asp-net-core-and-angular-code-venture-part), *Vincent Maverick Durano<sup>MVP</sup>, 2016/10/13* *en*

#### WebSocket #####
+ [WebSocket in ASP.NET Core](http://www.cnblogs.com/maxzhang1985/p/6208165.html)，*max zhang, 2016/12/21*

...

#### 2.5.9 NuGet ####
+ [使用 NuGet 打包类库](http://www.cnblogs.com/shanyou/p/5814683.html), *张善友<sup>MVP</sup>, 2016/08/29*
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
