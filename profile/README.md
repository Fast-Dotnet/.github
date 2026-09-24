<p align="center">
  <img src="assets/fast.png" alt="Fast Community" width="128" />
</p>

[English](./README.md) · [简体中文](./README.zh-CN.md) · [繁體中文](./README.zh-TW.md)

# Fast Community

> Making development simpler, so developers can focus on the business.

[Website](http://fastdotnet.com) · [Documentation](http://docs.fastdotnet.cn/en-US) · [Fast.NET](https://github.com/Fast-Dotnet/Fast.NET) · [Fast.Admin](https://github.com/Fast-Dotnet/Fast.Admin)

## About Us

Fast Community is an open-source technology community built around the .NET and Vue ecosystems. We maintain backend infrastructure SDKs, frontend SDKs, business component libraries, engineering tools, an administration system, and unified documentation.

We start from real project requirements and turn recurring infrastructure needs into tools, components, and SDKs with clear boundaries that can be adopted independently. Consistent engineering conventions, API contracts, and frontend-backend collaboration patterns help reduce project setup, team coordination, and long-term maintenance costs.

Fast does not require applications to adopt an entire technology stack at once. Developers can start with a utility library, an HTTP SDK, or a set of business components, then progressively integrate Fast.NET and Fast.Admin when a complete application foundation is needed.

## Ecosystem

### Backend Infrastructure

#### [Fast.NET](https://github.com/Fast-Dotnet/Fast.NET)

A modular infrastructure SDK for modern .NET applications, covering application initialization, dependency injection, caching, logging, event handling, authentication, data access, object mapping, serialization, dynamic APIs, unified responses, and API documentation.

Modules are published as independent NuGet packages and can be combined as needed without adopting the entire stack.

### UI Components

| Project | Description |
| --- | --- |
| [Fast.Element.Plus](https://github.com/Fast-Dotnet/Fast.Element.Plus) | Business component SDK for Vue 3 and Element Plus, including tables, forms, selectors, dialogs, directives, and composables |
| [Fast.Element.Plus.Icons](https://github.com/Fast-Dotnet/Fast.Element.Plus.Icons) | SVG icon components for Vue 3 with named imports, type support, and reviewable source generation |

Fast.Element.Plus targets administration interfaces and business applications. It captures reusable business interactions, component composition, and engineering conventions rather than replacing Element Plus.

### Frontend SDKs and Tooling

| Project | Description |
| --- | --- |
| [Fast.Axios](https://github.com/Fast-Dotnet/Fast.Axios) | Axios-based SDK with Fast.NET response handling, application extension points, and uni-app adaptation |
| [Fast.Utils](https://github.com/Fast-Dotnet/Fast.Utils) | TypeScript utilities for browsers, WebViews, Vue 3, and uni-app, including storage, async, and data helpers |
| [Fast.Vite.Plugins](https://github.com/Fast-Dotnet/Fast.Vite.Plugins) | Vite plugins for Web projects, covering code generation, asset processing, build metadata, and release checks |
| [Fast.ESLint.Config](https://github.com/Fast-Dotnet/Fast.ESLint.Config) | Typed ESLint Flat Config for Vue 3, uni-app, and TypeScript, with composable configurations and rule documentation |
| [Fast.ESLint.Config.Legacy](https://github.com/Fast-Dotnet/Fast.ESLint.Config.Legacy) | Legacy ESLint 8 configuration with composable Vue, TypeScript, and related tooling support |

### Administration System

#### [Fast.Admin](https://github.com/Fast-Dotnet/Fast.Admin)

A frontend-backend administration system built with Fast.NET, ASP.NET Core, Vue 3, TypeScript, Vite, and Element Plus.

It includes tenant, organization, department, employee, role, menu, and API permission management, together with system settings, dictionaries, logs, monitoring, job scheduling, and file management. Refer to the repository for the current feature set, supported clients, and deployment requirements.

## Documentation

Fast documentation is maintained at [docs.fastdotnet.cn](http://docs.fastdotnet.cn/en-US), providing bilingual guides, API references, and examples for the frontend SDKs, component libraries, engineering tools, and Fast.NET.

| Category | Projects |
| --- | --- |
| Backend infrastructure | Fast.NET |
| UI components | Fast.Element.Plus, Fast.Element.Plus.Icons |
| Frontend SDKs | Fast.Axios, Fast.Utils |
| Engineering tools | Fast.Vite.Plugins, Fast.ESLint.Config, Fast.ESLint.Config.Legacy |

Each project keeps its own installation guide, quick start, changelog, and collaboration entry points. Refer to the corresponding repository for compatibility, release, and licensing details.

## Principles

- **Focus on the business**: turn recurring infrastructure work into reusable capabilities so developers can focus on product requirements
- **Adopt incrementally**: keep module boundaries clear and choose only the SDKs, components, or systems a project needs
- **Stay consistent**: reduce collaboration and maintenance costs through shared engineering conventions, API contracts, and interaction patterns
- **Evolve reliably**: value compatibility, type safety, testing, documentation, and release quality while avoiding unjustified breaking changes
- **Improve continuously**: refine code, documentation, examples, and developer experience through real projects and community feedback

## Contributing

Contributions are welcome across the Fast ecosystem:

- Use Issues to report problems, propose improvements, or share practical experience
- Use Pull Requests to fix defects, improve features, and add tests, documentation, or examples
- Include the project version, runtime environment, reproduction steps, and relevant errors when reporting an issue
- Read the repository contribution guide and run the checks relevant to your changes before submitting code

For long-term collaboration or technical discussion, email [2875616188@qq.com](mailto:2875616188@qq.com) and mention the project and contribution area you are interested in.

## Repository Hosting

- Gitee is the primary source hosting and community collaboration platform for Fast projects
- GitHub organization [Fast-Dotnet](https://github.com/Fast-Dotnet) provides synchronized open-source mirrors and English entry points for international developers
- Source code, releases, documentation, and compatibility information are governed by the current content of each repository

## Support the Projects

If Fast helps your work, consider starring or sharing the projects, reporting issues, or contributing code. Applications and practical experience built with the Fast ecosystem are also welcome and help other developers understand how the projects are used.

## Contact

| Channel | Address |
| --- | --- |
| Website | [fastdotnet.com](http://fastdotnet.com) |
| Documentation | [docs.fastdotnet.cn](http://docs.fastdotnet.cn/en-US) |
| GitHub mirrors | [Fast-Dotnet](https://github.com/Fast-Dotnet) |
| Gitee organization | [FastDotnet](https://gitee.com/FastDotnet) |
| Email | [2875616188@qq.com](mailto:2875616188@qq.com) |

## Licensing

Use, modification, and distribution of each project are governed by the LICENSE, copyright notices, and related terms in its respective repository.
