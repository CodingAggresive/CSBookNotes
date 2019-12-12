**What is Use of Private Constructor in C# ?**



.NET Core vs .NET Framework
Reference :
https://stackify.com/net-core-vs-net-framework/

Microsoft maintains both runtimes for building applications with .NET, and they share many of the same APIs. This shared API is what is called the .NETStandard.

![](https://stackify.com/wp-content/uploads/2017/07/dot-net-core-dot-net-framework-shared-api-12581.png)
Developers use the .NET framework to create Windows desktop applications and server based applications. This includes ASP.NET web applications. .NET Core is used to create server applications that run on Windows, Linux and Mac. It does not currently support creating desktop applications with a user interface. Developers can write applications and libraries in VB.NET, C# and F# in both runtimes.

.NET Framework
.NET Core
desktop
windows
NA
Server Application
Windows (including ASP.Net Web application)
Windows,Linux,Mac


Developer should use .NET Core in all cases except:
1. Windows Desktop System like Winodws Forms and WPF.
2. When features missing in .NET Core Framework but exist in .NET Framework.





