# Building APIs with ASP.NET Core

ASP.NET Core makes it easy to build RESTful APIs for web, mobile, and desktop clients. You can choose between two main approaches: controller-based APIs and minimal APIs.

---

## Why Build APIs with ASP.NET Core?
- High performance and cross-platform
- Secure by default
- Open-source and well-documented
- Flexible: choose between controllers or minimal APIs

---

## API Approaches: Controllers vs Minimal APIs

**Controller-based APIs:**
- Use classes called controllers that inherit from `ControllerBase`.
- Great for complex APIs, large projects, or when you need features like model binding, validation, filters, and conventions.
- Follows the MVC (Model-View-Controller) pattern.
- Example: `WeatherForecastController : ControllerBase`
- [Learn more about controller-based APIs](https://learn.microsoft.com/en-us/aspnet/core/web-api/)

**Minimal APIs:**
- Define endpoints directly in your `Program.cs` file using concise lambda expressions.
- Ideal for small, simple APIs or microservices.
- Less ceremony, faster to get started, but fewer advanced features out of the box.
- Example: `app.MapGet("/weather", () => ...);`
- [Learn more about minimal APIs](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/minimal-apis/overview)

---

## Getting Started
For the latest steps, always check the [official ASP.NET Core Web API documentation](https://learn.microsoft.com/en-us/aspnet/core/web-api/).

### 1. Prerequisites
- .NET SDK (see [dotnet-installation guide](../dotnet-installation/dotnet-installation.md))

### 2. Create a New API Project

**Controller-based API:**
```powershell
dotnet new webapi -o MyApi
```
This creates a project with a sample controller and ready-to-use structure.

**Minimal API:**
```powershell
dotnet new web -o MyMinimalApi
```
This creates a project where you can define endpoints directly in `Program.cs`.

### 3. Run Your API
```powershell
cd MyApi  # or MyMinimalApi
dotnet run
```
Your API will be available at `https://localhost:5001` by default.

---

## Learn More
- [Official ASP.NET Core Web API documentation](https://learn.microsoft.com/en-us/aspnet/core/web-api/)
- [Minimal APIs overview](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/minimal-apis/overview)
- [Tutorial: Create a controller-based web API](https://learn.microsoft.com/en-us/aspnet/core/tutorials/first-web-api)
- [Tutorial: Create a minimal API](https://learn.microsoft.com/en-us/aspnet/core/tutorials/min-web-api)
