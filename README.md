# ASP.NET Core MVC Course

Course project for the ASP.NET Core MVC track. Two web applications built step by step while working through the framework's building blocks.

## Tech Stack

- ASP.NET Core MVC
- Entity Framework Core (SQL Server, code-first migrations)
- Razor views, Bootstrap
- AutoMapper

## Projects

| Project | Purpose |
|---|---|
| `MyAspNetCoreApp.Web` | Main course application: controllers, views, EF Core, filters, cookies, AJAX |
| `MiddlewareExample.Web` | Focused sample for custom middleware (IP whitelist) |

## Topics Covered

- Controllers, actions, routing and view rendering
- Model binding, view models and validation
- Tag helpers, partial views and layouts
- Action / result / resource / exception filters
- EF Core: DbContext, migrations, querying, relations
- Configuration and the options pattern (`AppSettingController`)
- Cookies, session and AJAX requests
- Custom middleware and the request pipeline

## Getting Started

```bash
git clone https://github.com/Fcakiroglu16/aspnetcore-mvc-course.git
cd aspnetcore-mvc-course/MyAspNetCoreApp.Web

# update the connection string in appsettings.json first
dotnet ef database update
dotnet run
```

## Requirements

- .NET SDK
- SQL Server (LocalDB is enough)
