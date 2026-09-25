<p align="center">
  <img src="assets/Fast.png" alt="Fast Community" width="128" />
</p>

[简体中文](./README.zh-CN.md) · [繁體中文](./README.zh-TW.md) · [English](./README.md)

# Fast Community

> 让开发变得简单，让开发者专注业务。

[官方网站](http://fastdotnet.com) · [统一文档](http://docs.fastdotnet.cn/zh-CN) · [Fast.NET](https://github.com/Fast-Dotnet/Fast.NET) · [Fast.Admin](https://github.com/Fast-Dotnet/Fast.Admin)

## 关于我们

Fast Community 是一个围绕 .NET 与 Vue 生态建设的开源技术社区，持续维护后端基础设施 SDK、前端 SDK、业务组件库、工程化工具、后台管理系统和统一文档。

我们从实际项目需求出发，将重复出现的基础能力沉淀为边界清晰、可按需采用的工具、组件与 SDK，并通过一致的开发规范、接口约定和前后端协作方式，降低项目搭建、团队协作与长期维护成本。

Fast 系列不是要求项目一次性采用完整技术栈，而是提供可以独立选择、逐步集成的开发基础。开发者可以从一个工具包、一个请求 SDK 或一组业务组件开始，也可以结合 Fast.NET 与 Fast.Admin 构建完整应用。

## 项目生态

### 后端基础设施

#### [Fast.NET](https://github.com/Fast-Dotnet/Fast.NET)

面向现代 .NET 应用的模块化基础设施 SDK，提供应用初始化、依赖注入、缓存、日志、事件处理、身份认证、数据访问、对象映射、序列化、动态 API、统一响应及接口文档等能力。

各模块通过独立 NuGet 包发布，可以根据项目需要按需组合，无需引入完整技术栈。

### UI 组件库

| 项目 | 介绍 |
| --- | --- |
| [Fast.Element.Plus](https://github.com/Fast-Dotnet/Fast.Element.Plus) | 基于 Vue 3 与 Element Plus 的业务组件 SDK，提供表格、表单、选择器、弹窗、指令与组合能力 |
| [Fast.Element.Plus.Icons](https://github.com/Fast-Dotnet/Fast.Element.Plus.Icons) | 面向 Vue 3 的 SVG 图标组件库，支持按需导入、类型提示与可复核的源码生成 |

Fast.Element.Plus 面向管理后台和业务系统场景，重点沉淀业务交互、组件组合和开发约定，不是对 Element Plus 的直接替代。

### 前端 SDK 与工程化工具

| 项目 | 介绍 |
| --- | --- |
| [Fast.Axios](https://github.com/Fast-Dotnet/Fast.Axios) | 基于 Axios 的请求 SDK，提供 Fast.NET 响应处理、项目扩展点及 uni-app 适配 |
| [Fast.Utils](https://github.com/Fast-Dotnet/Fast.Utils) | 面向浏览器、WebView、Vue 3 与 uni-app 的 TypeScript 工具库，提供存储、异步与常用数据处理能力 |
| [Fast.Vite.Plugins](https://github.com/Fast-Dotnet/Fast.Vite.Plugins) | 面向 Web 项目的 Vite 插件集合，覆盖代码生成、资源处理、构建信息与发布检查 |
| [Fast.ESLint.Config](https://github.com/Fast-Dotnet/Fast.ESLint.Config) | 面向 Vue 3、uni-app 与 TypeScript 项目的类型化 ESLint Flat Config，提供可组合配置与规则文档 |
| [Fast.ESLint.Config.Legacy](https://github.com/Fast-Dotnet/Fast.ESLint.Config.Legacy) | 面向 ESLint 8 项目的 Legacy 配置，提供 Vue、TypeScript 等能力组合与兼容配置 |

### 后台管理系统

#### [Fast.Admin](https://github.com/Fast-Dotnet/Fast.Admin)

基于 Fast.NET、ASP.NET Core、Vue 3、TypeScript、Vite 与 Element Plus 构建的前后端分离后台管理系统。

项目提供租户、组织、部门、员工、角色、菜单与接口权限管理，以及系统配置、数据字典、日志、系统监控、任务调度和文件管理等功能。具体功能、客户端支持范围及部署要求以项目仓库说明为准。

## 文档中心

Fast 系列文档已统一维护在 [docs.fastdotnet.cn](http://docs.fastdotnet.cn/zh-CN)，集中提供前端 SDK、组件库、工程化工具和 Fast.NET 的中英文指南、API 说明与示例。

| 分类 | 相关项目 |
| --- | --- |
| 后端基础设施 | Fast.NET |
| UI 组件库 | Fast.Element.Plus、Fast.Element.Plus.Icons |
| 前端 SDK | Fast.Axios、Fast.Utils |
| 工程化工具 | Fast.Vite.Plugins、Fast.ESLint.Config、Fast.ESLint.Config.Legacy |

各项目仍保留独立的安装、快速开始、变更记录与协作入口。具体兼容范围、发布版本和许可证以对应仓库说明为准。

## 我们的理念

- **聚焦业务**：将重复的基础工作沉淀为通用能力，让开发者将精力投入业务实现
- **按需采用**：重视模块边界与复用能力，根据项目需要选择 SDK、组件或管理系统
- **保持一致**：通过统一的编码规范、接口约定和组件交互，降低团队协作与维护成本
- **可靠演进**：重视兼容性、类型安全、测试、文档和发布质量，避免无依据的破坏性变更
- **持续完善**：结合真实项目和社区反馈，持续改进代码、文档、示例与开发体验

## 参与贡献

欢迎通过对应仓库参与 Fast 系列项目建设：

- 使用 Issues 反馈问题、提出建议或分享实践经验
- 使用 Pull Requests 修复问题、完善功能、补充测试、文档与示例
- 提交问题时尽量提供项目版本、运行环境、复现步骤和必要的错误信息
- 提交代码前阅读对应仓库的贡献说明，并完成与修改范围相关的检查

如果希望长期参与项目协作或交流技术方向，可以发送邮件至 [2875616188@qq.com](mailto:2875616188@qq.com)，并注明关注的项目与参与方向。

## 代码托管

- Gitee 是 Fast 系列项目的主要代码托管与社区协作平台
- GitHub 组织 [Fast-Dotnet](https://github.com/Fast-Dotnet) 提供同步开源镜像，并为国际开发者提供英文项目入口
- 源码、发行版、文档和兼容性信息以各项目仓库的实际内容为准

## 支持项目

如果 Fast 系列项目对你有所帮助，欢迎通过 Star、分享项目、反馈问题或贡献代码支持社区发展。也欢迎分享基于 Fast 系列项目构建的应用与实践经验，帮助更多开发者了解项目的实际使用方式。

## 联系我们

| 渠道 | 地址 |
| --- | --- |
| 官方网站 | [fastdotnet.com](http://fastdotnet.com) |
| 统一文档 | [docs.fastdotnet.cn](http://docs.fastdotnet.cn/zh-CN) |
| GitHub 镜像 | [Fast-Dotnet](https://github.com/Fast-Dotnet) |
| Gitee 组织 | [FastDotnet](https://gitee.com/FastDotnet) |
| 联系邮箱 | [2875616188@qq.com](mailto:2875616188@qq.com) |

## 开源说明

各项目的使用、修改与分发要求，以对应仓库的 LICENSE、版权声明及相关说明为准。
