# Demo Identity And Entity Framework Core with JWT Web service API ASP.NET Core

TOOL ==> NUGET PACKAGE ==> NUGET PACKAGE CONSOLE ==> command line install nuget packages


Install-Package Microsoft.AspNetCore.Authentication.JwtBearer

Install-Package Microsoft.AspNetCore.Identity.EntityFrameworkCore
Install-Package Microsoft.AspNetCore.Identity

Install-Package Microsoft.EntityFrameworkCore.SqlServer
Install-Package Microsoft.EntityFrameworkCore.Tools
Install-Package Microsoft.EntityFrameworkCore


Uninstall-Package Swashbuckle.AspNetCore


//Lệnh tạo migration 
add-migration initial
//tạo bảng trong database
update-database
