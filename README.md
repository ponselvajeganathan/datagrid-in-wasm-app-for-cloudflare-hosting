# Deploy Syncfusion Blazor WASM Application to Cloudflare

## Overview

This repository demonstrates a Syncfusion Blazor WebAssembly (WASM) application configured for deployment to Cloudflare Pages. The sample is organized around a Blazor WebAssembly project and includes deployment workflow assets that help publish the application to Cloudflare-hosted infrastructure. The repository is intended as a reference for developers who want to host a Syncfusion Blazor application, including DataGrid functionality, in a Cloudflare Pages environment while using a GitHub-based deployment workflow.

## Key Features

- Demonstrates a Syncfusion Blazor WebAssembly application configured for Cloudflare Pages hosting.
- Includes a dedicated project folder named `Deploy Syncfusion Blazor WASM application to Cloudflare`.
- Includes GitHub workflow configuration located under `.github/workflows`.
- Provides a deployment-ready repository structure for publishing a Blazor WASM application.
- Contains a Syncfusion Blazor application associated with a DataGrid hosting scenario as indicated by the repository name.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file contained within the `Deploy Syncfusion Blazor WASM application to Cloudflare` project folder.
3. Restore all NuGet packages.
4. Set the Blazor WebAssembly project as the startup project if required.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the `Deploy Syncfusion Blazor WASM application to Cloudflare` project directory.

```bash
dotnet restore
dotnet run
```

4. Open the local application URL displayed by the application after startup.

## Project Structure

- `Deploy Syncfusion Blazor WASM application to Cloudflare/` — contains the Blazor WebAssembly application configured for Cloudflare hosting.
- `.github/workflows/` — contains GitHub Actions workflow definitions used for automated deployment and CI processes.
- `Deploy Syncfusion Blazor WASM application to Cloudflare/Pages/*.razor` — hosts the Blazor page implementation used by the sample.
- `Deploy Syncfusion Blazor WASM application to Cloudflare/wwwroot/` — contains static assets, styles, and deployment resources consumed by the application.
- `Deploy Syncfusion Blazor WASM application to Cloudflare/.csproj` — defines the target framework, project configuration, and Syncfusion package references.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For official Syncfusion Blazor DataGrid documentation, see: https://help.syncfusion.com/grid-sdk/blazor/data-grid/getting-started

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.