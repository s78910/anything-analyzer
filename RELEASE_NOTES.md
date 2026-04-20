# Anything Analyzer v3.4.0

## 新功能

- **AI 请求日志查看器** — 新增 AI Request Log 模块，记录所有 LLM API 调用的完整 HTTP 请求/响应数据，帮助调试 AI 分析和追问过程中的网络问题
  - 在 Report 工具栏点击「📋 AI 请求日志」即可进入日志视图
  - 左右分栏布局：左侧为日志列表（支持类型过滤和搜索），右侧为详情面板
  - 详情面板提供 Request Body / Response Body / Headers / Meta 四个子 Tab
  - 支持 Session 级别和全局级别两种查看模式
  - API Key 自动脱敏，敏感信息不会明文存储
  - 记录请求耗时、Token 用量、HTTP 状态码和错误信息

## Bug 修复

- **修复追问不遵循 apiType 配置** — 当用户全局设置 `apiType: "responses"`（OpenAI Responses API）时，追问（含 tool calling）仍错误使用 `/chat/completions` 端点。现已正确路由，新增 `agenticLoopResponses` 方法支持 Responses API 的工具调用协议

## 下载

| 平台 | 文件 |
|------|------|
| Windows | `Anything-Analyzer-Setup-3.4.0.exe` |
| macOS (Apple Silicon) | `Anything-Analyzer-3.4.0-arm64.dmg` |
| macOS (Intel) | `Anything-Analyzer-3.4.0-x64.dmg` |
| Linux | `Anything-Analyzer-3.4.0.AppImage` |
