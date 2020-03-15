Repository này là phần back-end của hệ thống.
Ngôn ngữ lập trình và công nghệ
Ngôn ngữ lập trình: C#
Framework: ASP.NET Core
Hệ quản trị CSDL: MySQL
Môi trường phát triển
ASP.NET Core 2.2
C# 6.0
Microsoft Visual Studio Enterprise 2017
Cài đặt
Cài đặt ASP.NET Core, phiên bản 2.2.
Cài đặt hệ quản trị CSDL MySQL trên máy tính với XAMPP hoặc MySQL Workbench.
Clone repository mffms-api về máy thông qua dòng lệnh sau:
> git clone https://github.com/KutieKat/mffms-api
Mở project bằng Visual Studio, chọn Tools > NuGet Package Manager > Package Manager Console, lần lượt thực thi các dòng lệnh sau:
> dotnet ef migrations add InitialCreate
> dotnet ef database update
Chạy MySQL với XAMPP hoặc MySQL Workbench.
Sau khi quá trình hoàn tất, nhấn tổ hợp phím Ctrl + F5 để chạy server tại địa chỉ http://localhost:5000.
Thư viện
AutoMapper
MySql.Data.EntityFrameworkCore
Swashbuckle.AspNetCore