# Blazor: Build Interactive Web UIs with .NET

Blazor is a modern framework for building interactive web applications using C# and .NET, instead of JavaScript. You can run Blazor apps in the browser (WebAssembly), on the server, or as hybrid apps.

---

## Why Use Blazor?
- Build rich, interactive UIs with C# and Razor components
- Share code and libraries between client and server
- Leverage .NET's security, performance, and tooling
- Choose from multiple hosting models: WebAssembly, Server, or Hybrid

---

## Getting Started with Blazor

For the latest steps and best practices, always check the [official Blazor documentation](https://learn.microsoft.com/en-us/aspnet/core/blazor/).

### 1. Prerequisites
- Install the [.NET SDK](https://dotnet.microsoft.com/download) (see our [dotnet-installation guide](../dotnet-installation/dotnet-installation.md))
- (Optional) [Visual Studio](https://visualstudio.microsoft.com/) or [Visual Studio Code](https://code.visualstudio.com/) for a full-featured development experience

### 2. Create a New Blazor App

You can create Blazor projects using the .NET CLI or Visual Studio:

**Using the .NET CLI:**
```powershell
# For a Blazor Web App (recommended for most new projects)
dotnet new blazor -o MyBlazorApp
# For a standalone Blazor WebAssembly app
dotnet new blazorwasm -o MyBlazorWasmApp
# For a Blazor Server app
dotnet new blazorserver -o MyBlazorServerApp
```

**Using Visual Studio:**
1. Open Visual Studio and select "Create a new project".
2. Search for "Blazor" and choose the template that fits your needs (Blazor Web App, Blazor WebAssembly, or Blazor Server).
3. Follow the prompts to configure your project.

For more details, see the [Blazor tooling guide](https://learn.microsoft.com/en-us/aspnet/core/blazor/tooling).

### 3. Run Your App
```powershell
cd MyBlazorApp  # or MyBlazorWasmApp or MyBlazorServerApp
dotnet run
```
Then open the provided URL in your browser.

---

## Learn More and Tutorials
- [Build your first Blazor app (official tutorial)](https://dotnet.microsoft.com/learn/aspnet/blazor-tutorial/intro)
- [Blazor Learning Path (Microsoft Learn)](https://learn.microsoft.com/en-us/training/paths/build-web-apps-with-blazor/)
- [Blazor documentation](https://learn.microsoft.com/en-us/aspnet/core/blazor/)

---

## Next Steps
- Explore more Blazor features: components, routing, forms, data binding, and authentication.
- For advanced scenarios, see the [Blazor tutorials](https://learn.microsoft.com/en-us/aspnet/core/blazor/tutorials/).
