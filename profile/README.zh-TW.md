<p align="center">
  <img src="assets/Fast.png" alt="Fast Community" width="128" />
</p>

[简体中文](./README.zh-CN.md) · [繁體中文](./README.zh-TW.md) · [English](./README.md)

# Fast Community

> 讓開發變得簡單，讓開發者專注業務。

[官方網站](http://fastdotnet.com) · [統一文件](http://docs.fastdotnet.cn/zh-CN) · [Fast.NET](https://github.com/Fast-Dotnet/Fast.NET) · [Fast.Admin](https://github.com/Fast-Dotnet/Fast.Admin)

## 關於我們

Fast Community 是一個圍繞 .NET 與 Vue 生態建設的開源技術社群，持續維護後端基礎設施 SDK、前端 SDK、業務元件庫、工程化工具、後台管理系統和統一文件。

我們從實際專案需求出發，將重複出現的基礎能力沉澱為邊界清晰、可按需採用的工具、元件與 SDK，並透過一致的開發規範、介面約定和前後端協作方式，降低專案建置、團隊協作與長期維護成本。

Fast 系列不要求專案一次性採用完整技術棧，而是提供可以獨立選擇、逐步整合的開發基礎。開發者可以從一個工具包、一個請求 SDK 或一組業務元件開始，也可以結合 Fast.NET 與 Fast.Admin 建構完整應用。

## 專案生態

### 後端基礎設施

#### [Fast.NET](https://github.com/Fast-Dotnet/Fast.NET)

面向現代 .NET 應用的模組化基礎設施 SDK，提供應用初始化、相依性注入、快取、日誌、事件處理、身分驗證、資料存取、物件對映、序列化、動態 API、統一回應及介面文件等能力。

各模組透過獨立 NuGet 套件發布，可以根據專案需要按需組合，無需引入完整技術棧。

### UI 元件庫

| 專案 | 介紹 |
| --- | --- |
| [Fast.Element.Plus](https://github.com/Fast-Dotnet/Fast.Element.Plus) | 基於 Vue 3 與 Element Plus 的業務元件 SDK，提供表格、表單、選擇器、對話框、指令與組合能力 |
| [Fast.Element.Plus.Icons](https://github.com/Fast-Dotnet/Fast.Element.Plus.Icons) | 面向 Vue 3 的 SVG 圖示元件庫，支援按需匯入、型別提示與可複核的原始碼生成 |

Fast.Element.Plus 面向管理後台和業務系統場景，重點沉澱業務互動、元件組合和開發約定，不是對 Element Plus 的直接替代。

### 前端 SDK 與工程化工具

| 專案 | 介紹 |
| --- | --- |
| [Fast.Axios](https://github.com/Fast-Dotnet/Fast.Axios) | 基於 Axios 的請求 SDK，提供 Fast.NET 回應處理、專案擴充點及 uni-app 適配 |
| [Fast.Utils](https://github.com/Fast-Dotnet/Fast.Utils) | 面向瀏覽器、WebView、Vue 3 與 uni-app 的 TypeScript 工具庫，提供儲存、非同步與常用資料處理能力 |
| [Fast.Vite.Plugins](https://github.com/Fast-Dotnet/Fast.Vite.Plugins) | 面向 Web 專案的 Vite 外掛集合，涵蓋程式碼生成、資源處理、建置資訊與發布檢查 |
| [Fast.ESLint.Config](https://github.com/Fast-Dotnet/Fast.ESLint.Config) | 面向 Vue 3、uni-app 與 TypeScript 專案的型別化 ESLint Flat Config，提供可組合設定與規則文件 |
| [Fast.ESLint.Config.Legacy](https://github.com/Fast-Dotnet/Fast.ESLint.Config.Legacy) | 面向 ESLint 8 專案的 Legacy 設定，提供 Vue、TypeScript 等能力組合與相容設定 |

### 後台管理系統

#### [Fast.Admin](https://github.com/Fast-Dotnet/Fast.Admin)

基於 Fast.NET、ASP.NET Core、Vue 3、TypeScript、Vite 與 Element Plus 建構的前後端分離後台管理系統。

專案提供租戶、組織、部門、員工、角色、選單與介面權限管理，以及系統設定、資料字典、日誌、系統監控、任務排程和檔案管理等功能。具體功能、客戶端支援範圍及部署要求以專案儲存庫說明為準。

## 文件中心

Fast 系列文件已統一維護在 [docs.fastdotnet.cn](http://docs.fastdotnet.cn/zh-CN)，集中提供前端 SDK、元件庫、工程化工具和 Fast.NET 的中英文指南、API 說明與範例。

| 分類 | 相關專案 |
| --- | --- |
| 後端基礎設施 | Fast.NET |
| UI 元件庫 | Fast.Element.Plus、Fast.Element.Plus.Icons |
| 前端 SDK | Fast.Axios、Fast.Utils |
| 工程化工具 | Fast.Vite.Plugins、Fast.ESLint.Config、Fast.ESLint.Config.Legacy |

各專案仍保留獨立的安裝、快速開始、變更記錄與協作入口。具體相容範圍、發布版本和授權條款以對應儲存庫說明為準。

## 我們的理念

- **聚焦業務**：將重複的基礎工作沉澱為通用能力，讓開發者將精力投入業務實作
- **按需採用**：重視模組邊界與複用能力，根據專案需要選擇 SDK、元件或管理系統
- **保持一致**：透過統一的編碼規範、介面約定和元件互動，降低團隊協作與維護成本
- **可靠演進**：重視相容性、型別安全、測試、文件和發布品質，避免無依據的破壞性變更
- **持續完善**：結合真實專案和社群回饋，持續改進程式碼、文件、範例與開發體驗

## 參與貢獻

歡迎透過對應儲存庫參與 Fast 系列專案建設：

- 使用 Issues 回報問題、提出建議或分享實務經驗
- 使用 Pull Requests 修復問題、完善功能、補充測試、文件與範例
- 提交問題時盡量提供專案版本、執行環境、重現步驟和必要的錯誤資訊
- 提交程式碼前閱讀對應儲存庫的貢獻說明，並完成與修改範圍相關的檢查

如果希望長期參與專案協作或交流技術方向，可以寄送郵件至 [2875616188@qq.com](mailto:2875616188@qq.com)，並註明關注的專案與參與方向。

## 程式碼託管

- Gitee 是 Fast 系列專案的主要程式碼託管與社群協作平台
- GitHub 組織 [Fast-Dotnet](https://github.com/Fast-Dotnet) 提供同步開源鏡像，並為國際開發者提供英文專案入口
- 原始碼、發行版、文件和相容性資訊以各專案儲存庫的實際內容為準

## 支援專案

如果 Fast 系列專案對你有所幫助，歡迎透過 Star、分享專案、回報問題或貢獻程式碼支援社群發展。也歡迎分享基於 Fast 系列專案建構的應用與實務經驗，幫助更多開發者了解專案的實際使用方式。

## 聯絡我們

| 管道 | 地址 |
| --- | --- |
| 官方網站 | [fastdotnet.com](http://fastdotnet.com) |
| 統一文件 | [docs.fastdotnet.cn](http://docs.fastdotnet.cn/zh-CN) |
| GitHub 鏡像 | [Fast-Dotnet](https://github.com/Fast-Dotnet) |
| Gitee 組織 | [FastDotnet](https://gitee.com/FastDotnet) |
| 聯絡信箱 | [2875616188@qq.com](mailto:2875616188@qq.com) |

## 開源說明

各專案的使用、修改與散布要求，以對應儲存庫的 LICENSE、著作權聲明及相關說明為準。
