# Hybrid Dashboard

A comprehensive sample demonstrating cross-platform [dashboard](https://www.syncfusion.com/blazor-components/blazor-dashboard) development using .NET MAUI Blazor Hybrid technology. Build once and deploy to native mobile apps (iOS, Android, macOS), desktop (Windows), and web using shared Razor components and a unified codebase.

## Overview

**Hybrid Dashboard** demonstrates how to build a sophisticated business dashboard that runs on multiple platforms using .NET MAUI Blazor Hybrid. The application features interactive charts, data grids, and summary cards—all powered by components and shared across platforms through a Razor Class Library.
- **Shared UI Components**: Razor Class Library (`HybridDashboard.Shared`) contains all dashboard UI components
- **Platform-Specific Services**: Dependency injection pattern for platform-specific implementations
- **Multi-target Support**: Single codebase targeting Android, iOS, macOS, Windows, and web
- **Code Reuse**: Maximize code sharing across native and web targets

## Features

- **Multi-Platform Support** - Run on Android, iOS, macOS, Windows, and web with minimal platform-specific code
- **Interactive Dashboards** - Rich data visualization with charts, grids, and summary cards using components
- **Responsive Design** - Adaptive layouts that work perfectly on any screen size
- **Shared Components** - Razor components written once and shared across all platforms
- **Extensible Architecture** - Platform-specific services via dependency injection
- **Real-time Data** - Dashboard with sample business data (revenue, orders, products, customers)

## Prerequisites

- [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet/8.0) or later
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
- [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/building-cross-platform-apps-with-net-maui-blazor-hybrid.git
cd building-cross-platform-apps-with-net-maui-blazor-hybrid
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```
## References

- [Blazor Documentation](https://blazor.syncfusion.com/documentation/introduction)
- [Blazor Dashboard Documentation](https://blazor.syncfusion.com/documentation/dashboard-layout/getting-started-with-web-app)
- [Online Dashboard Demo](https://blazor.syncfusion.com/demos/dashboard-layout/overview?theme=fluent2)


