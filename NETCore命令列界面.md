# .NET CLI (dotnet) 命令.查看所有使用参数

命令 | 描述 
---|---|
dotnet restore|还原解决方案中所有项目的NuGet包。
dotnet build|生成.NET Core应用程序
dotnet run|从源运行应用程序
dotnet publish -c Release –o &#60;Folder&#62;|发布 .NET 依赖于框架或独立应用程序。
dotnet test|使用测试运行程序运行测试。
dotnet add package &#60;Name&#62;|添加指定NuGet 包。
dotnet new --list|根据指定的模板，创建新的项目、配置文件或解决方案。
dotnet new --install &#60;PackageName&#62;|从指定的NuGet包名安装一个新模板。例如,dotnet new --install "NetEscapades.Templates::*".
dotnet new &#60;Template&#62; –o &#60;Folder&#62; -n &#60;NewName&#62;|从指定的模板创建一个项目，指定放置项的文件夹和项目名称。
dotnet ef --help|Entity Framework Core 命令行工具。
dotnet ef migrations add &#60;Name&#62;|使用指定的名称向项目添加新的EF核心迁移。
dotnet ef database update|更新数据库




