# MCP 服务器与工具

> 官方 MCP server、高星实用 server，以及 MCP 调试 / 评测 / 索引工具。
> 维护：每天 06:30 / 18:30 增量追加；Star 为采集当日数值（2026-11-28）。

## 官方 server

### microsoft/playwright-mcp — 40,219 ★
微软官方浏览器自动化 MCP，让 agent 真实操作网页而不是"想象网页"。

- 适用：抓取、表单填写、页面回归验证。
- 链接：https://github.com/microsoft/playwright-mcp
- 收录：2026-11-26
- 更新：2026-11-28

### awslabs/mcp — 9,961 ★
AWS 官方 MCP servers 集合，覆盖文档、成本、基础设施等。

- 状态：持续更新（当日有提交）。
- 链接：https://github.com/awslabs/mcp
- 收录：2026-11-26
- 更新：2026-11-28

### ChromeDevTools/chrome-devtools-mcp — 59,617 ★
Chrome DevTools 团队的官方 MCP：把 Performance 面板、网络请求、控制台、堆快照暴露给编码 agent。

- 亮点：性能剖析和页面回归从"看截图猜"变成可读的 trace 与请求记录；调试真实浏览器而不是模拟环境。
- 链接：https://github.com/ChromeDevTools/chrome-devtools-mcp
- 收录：2026-11-26
- 更新：2026-11-28

### github/github-mcp-server — 34,807 ★
GitHub 官方 MCP server，仓库、Issue、PR、代码搜索全流程。

- 亮点：官方维护，工具按 toolsets 分组，可开只读模式收紧权限；本仓库的每日写入即用它完成。
- 链接：https://github.com/github/github-mcp-server
- 收录：2026-11-26
- 更新：2026-11-28

### modelcontextprotocol/python-sdk — 24,993 ★
MCP 官方 Python SDK，写 server / client 的参考实现。

- 亮点：`FastMCP` 装饰器直接定义工具，跟规范最快；自己写 server 先看这里再找第三方。
- 链接：https://github.com/modelcontextprotocol/python-sdk
- 收录：2026-11-26
- 更新：2026-11-28

### modelcontextprotocol/servers — 92,302 ★
MCP 官方参考 servers 仓库：filesystem、git、fetch、memory、time 等基础 server 的规范实现。

- 亮点：写自己的 server 前先读这里的实现——工具定义、错误处理、传输层都贴着规范走；官方维护，11-25 仍有提交。
- 链接：https://github.com/modelcontextprotocol/servers
- 收录：2026-11-27
- 更新：2026-11-28

### 例外：Skills over MCP（官方大发布，2026-11-24）— 官方公告
Anthropic 在 MCP 两周年（11-24）宣布 Skills over MCP 进入公测：MCP server 可以随工具一起发布 skills，Claude 按需加载；同期 Tasks 与 Elicitation 转正式可用，File Uploads 即将推出。

- 亮点：连接器从「给一张工具清单」变成「自带操作手册」，skill 随 server 更新、用户无需单独安装；Elicitation 让删库、扣费这类操作前必须停下来确认——GitHub 的做法是要求手敲仓库全名。
- 注意：公测对 Pro / Max / Ultra 默认开启，Team 需管理员打开；第三方目录连接器的 skill 会被扫描，自建 server 不扫描，官方建议只加可信 server。
- 链接：https://claude.com/resources/articles/skills-over-mcp-tasks-and-more
- 收录：2026-11-27
- 放宽理由：官方一手公告（claude.com，2026-11-24），属 MCP 协议层面的大版本能力上线，按 v7 规则「官方大发布」放宽 1 条，当日合计 12 条。

## 垂直领域

### mrexodia/ida-pro-mcp — 13,603 ★
把 IDA Pro 接进大模型，逆向分析、二进制审计问答式完成。

- 适用：安全研究、逆向工程。
- 链接：https://github.com/mrexodia/ida-pro-mcp
- 收录：2026-11-26
- 更新：2026-11-28

### tadata-org/fastapi_mcp — 12,031 ★
把 FastAPI 端点一键暴露为 MCP tools，自带鉴权。

- 注意：末次提交 2025-11，已一年未更新，选型需评估兼容性。
- 链接：https://github.com/tadata-org/fastapi_mcp
- 收录：2026-11-26

### upstash/context7 — 65,556 ★
给 AI agent 提供最新版本文档的 MCP：按库名取对应版本的文档片段，避免模型照训练记忆写过期 API。

- 亮点：文档型 MCP 里星数最高的一档，11-26 仍有提交；接进 Claude Code / Cursor 后，「这个 API 早改了你不知道」的状况明显减少。
- 链接：https://github.com/upstash/context7
- 收录：2026-11-27
- 更新：2026-11-28

### oraios/serena — 31,758 ★
把 IDE 的语义检索能力做成 MCP toolkit：按符号查找引用、精确替换，而不是整文件读写。

- 亮点：基于 LSP 「先定位符号再改」，改大仓库比 grep 加全文重写省 token，也更少改错上下文；多语言 server 覆盖主流语言。
- 链接：https://github.com/oraios/serena
- 收录：2026-11-27
- 更新：2026-11-28

### redhat-et/ripwire — 2,573 ★
红帽新兴技术团队（redhat-et）开源的 C++23 代码上下文工具，CLI + MCP server：先给 agent 一张调用图，再让它读仓库。

- 亮点：确定性的调用图回答「改这里会碰到哪里、该跑哪些测试」；动笔时给出爆炸半径、13 类质量指标只报变差项、漏改的联动与字段读写；零运行时依赖、Apache-2.0，11-27 仍在提交；作者附的现场报告称在约 20 个 agent 并发的大型 C++/Metal 仓库里研究阶段省掉约一半 token、单次查询 10–25×。
- 注意：星数只有 2.5k，胜在官方团队维护 + 活跃度高；C++ 项目，装前确认构建环境。
- 链接：https://github.com/redhat-et/ripwire
- 收录：2026-11-28

### D4Vinci/Scrapling — 106,365 ★
Python 抓取框架 + MCP server + Agent Skill 三件套：静态页、JS 渲染、反爬、并发爬虫、导出收在一个库里。

- 亮点：自适应元素追踪（页面改版后仍能按结构定位同类元素）、后台 API 捕获、会话复用、代理轮换、断点续爬与 AutoThrottle；agent 侧可直接用 MCP 浏览取数，也能把整站收成干净 Markdown（JSON/JSONL/CSV/XML 导出）。
- 注意：抓取前确认目标站点条款与 robots 限制。
- 链接：https://github.com/D4Vinci/Scrapling
- 收录：2026-11-28

### DeusData/codebase-memory-mcp — 49,260 ★
本地代码智能 MCP：把代码、文档、配置、基础设施连成一张持久知识图谱，17 个 MCP 工具、164 种语言与格式。

- 亮点：纯 C 后端，索引与查询不需要托管服务和 API key；Hybrid LSP 做类型解析，能追跨服务调用、把部署回溯到源码、评估一次改动会波及哪里；安装器覆盖 46 种客户端集成，附 CBM Lens（3D 代码图谱与架构图，beta）；有 arXiv 论文、SLSA 3 与 OpenSSF 评分背书。
- 注意：首次索引大仓库需要时间与内存，CBM Lens 的浏览器 AI 需手动启用下载模型。
- 链接：https://github.com/DeusData/codebase-memory-mcp
- 收录：2026-11-28

## 调试、评测与索引

### MCPJam/inspector — 2,351 ★
MCP 服务器、MCP app、ChatGPT app 的对话 / 调试 / 评测平台。

- 亮点：安装前可核对工具定义与调用链，避免装上"不知道会做什么"的 server。
- 链接：https://github.com/MCPJam/inspector
- 收录：2026-11-26
- 更新：2026-11-28

### tolkonepiu/best-of-mcp-servers — 184 ★
400 个 MCP servers 按质量分排名，分 34 类，每周更新。

- 亮点：适合当选型索引，而不是逐个翻仓库。
- 链接：https://github.com/tolkonepiu/best-of-mcp-servers
- 收录：2026-11-26
- 更新：2026-11-28
