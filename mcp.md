# MCP 服务器与工具

> 官方 MCP server、高星实用 server，以及 MCP 调试 / 评测 / 索引工具。
> 维护：每天 07:00 / 19:00 增量追加；Star 为采集当日数值（2026-11-26）。

## 官方 server

### microsoft/playwright-mcp — 40,160 ★
微软官方浏览器自动化 MCP，让 agent 真实操作网页而不是"想象网页"。

- 适用：抓取、表单填写、页面回归验证。
- 链接：https://github.com/microsoft/playwright-mcp
- 收录：2026-11-26
- 更新：2026-11-26

### awslabs/mcp — 9,958 ★
AWS 官方 MCP servers 集合，覆盖文档、成本、基础设施等。

- 状态：持续更新（当日有提交）。
- 链接：https://github.com/awslabs/mcp
- 收录：2026-11-26
- 更新：2026-11-26

### ChromeDevTools/chrome-devtools-mcp — 59,420 ★
Chrome DevTools 团队的官方 MCP：把 Performance 面板、网络请求、控制台、堆快照暴露给编码 agent。

- 亮点：性能剖析和页面回归从"看截图猜"变成可读的 trace 与请求记录；调试真实浏览器而不是模拟环境。
- 链接：https://github.com/ChromeDevTools/chrome-devtools-mcp
- 收录：2026-11-26

### github/github-mcp-server — 34,773 ★
GitHub 官方 MCP server，仓库、Issue、PR、代码搜索全流程。

- 亮点：官方维护，工具按 toolsets 分组，可开只读模式收紧权限；本仓库的每日写入即用它完成。
- 链接：https://github.com/github/github-mcp-server
- 收录：2026-11-26

### modelcontextprotocol/python-sdk — 24,976 ★
MCP 官方 Python SDK，写 server / client 的参考实现。

- 亮点：`FastMCP` 装饰器直接定义工具，跟规范最快；自己写 server 先看这里再找第三方。
- 链接：https://github.com/modelcontextprotocol/python-sdk
- 收录：2026-11-26

## 垂直领域

### mrexodia/ida-pro-mcp — 13,588 ★
把 IDA Pro 接进大模型，逆向分析、二进制审计问答式完成。

- 适用：安全研究、逆向工程。
- 链接：https://github.com/mrexodia/ida-pro-mcp
- 收录：2026-11-26
- 更新：2026-11-26

### tadata-org/fastapi_mcp — 12,031 ★
把 FastAPI 端点一键暴露为 MCP tools，自带鉴权。

- 注意：末次提交 2025-11，已一年未更新，选型需评估兼容性。
- 链接：https://github.com/tadata-org/fastapi_mcp
- 收录：2026-11-26

## 调试、评测与索引

### MCPJam/inspector — 2,348 ★
MCP 服务器、MCP app、ChatGPT app 的对话 / 调试 / 评测平台。

- 亮点：安装前可核对工具定义与调用链，避免装上"不知道会做什么"的 server。
- 链接：https://github.com/MCPJam/inspector
- 收录：2026-11-26

### tolkonepiu/best-of-mcp-servers — 176 ★
400 个 MCP servers 按质量分排名，分 34 类，每周更新。

- 亮点：适合当选型索引，而不是逐个翻仓库。
- 链接：https://github.com/tolkonepiu/best-of-mcp-servers
- 收录：2026-11-26
