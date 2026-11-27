# Skill / 插件（Agent Skills）

> 面向 Claude Code、Codex、Cursor 等编码 agent 的 Skill 与插件仓库。
> 维护：每天 06:30 / 18:30 增量追加，已收录条目不再重复写入。
> Star 为采集当日数值（2026-11-27），仅作参考。

## 官方与高星

### anthropics/skills — 201,255 ★
Anthropic 官方 Agent Skills 仓库，生产级文档技能（docx / pdf / pptx / xlsx）开源，附 skill 规范与模板。

- 亮点：可直接当作 skill 写法参考；官方维护，兼容性最好。
- 链接：https://github.com/anthropics/skills
- 收录：2026-11-26
- 更新：2026-11-27

### obra/superpowers — 327,861 ★
agentic 技能框架与软件开发方法论。

- 亮点：`/brainstorm` → `/write-plan` → `/execute-plan` 三段式，强制先问清需求再动手。
- 链接：https://github.com/obra/superpowers
- 收录：2026-11-26
- 更新：2026-11-27

### VoltAgent/awesome-agent-skills — 37,580 ★
1000+ 精选技能目录，人工筛选并标注兼容 Claude Code / Codex / Cursor / Gemini CLI 等。

- 亮点：找技能比翻 GitHub topics 快，适合当索引用。
- 链接：https://github.com/VoltAgent/awesome-agent-skills
- 收录：2026-11-26
- 更新：2026-11-27

### heygen-com/hyperframes — 91,170 ★
HeyGen 官方开源的 AI 视频编辑器：改自己的素材，或用 Claude Code / Codex 从零重做一条视频。

- 亮点：写 HTML 再渲成 MP4，动效走 GSAP，成片可版本化；Apache-2.0，另有免费 Studio 桌面版。
- 链接：https://github.com/heygen-com/hyperframes
- 收录：2026-11-26
- 更新：2026-11-27

### alibaba/open-code-review — 56,776 ★
阿里开源的代码审查工具：确定性流水线 + LLM Agent 混合架构，精确到行级评论。

- 亮点：内置多语言规则集（NPE、线程安全、XSS、SQL 注入），兼容 OpenAI / Anthropic 接口，可挂 Claude Code、Codex、Cursor。
- 链接：https://github.com/alibaba/open-code-review
- 收录：2026-11-26
- 更新：2026-11-27

## 单点能力 skill

### morluto/rea — 480,420 ★
把逆向分析装进 agent：本地读取原生二进制、Electron / JS、.NET 程序集与网站，讲清某个功能是怎么实现的。

- 亮点：`npx rea-agents setup` 自动注册 MCP 连接与调查 skill；可复用已有的 Hopper / Ghidra / IDA，分析全程在本地，结论附证据与局限。
- 注意：面向逆向与安全研究，先确认被测对象的授权范围。
- 链接：https://github.com/morluto/rea
- 收录：2026-11-26
- 更新：2026-11-27

### kajisho5/ffmpeg-skill — 11,708 ★
给编码 agent 用的本地视频编辑器，42 个 FFmpeg 工具封装成机器可读契约，附 MCP server。

- 亮点：切割、字幕、转码可用一句话调用，输出可验证。
- 链接：https://github.com/kajisho5/ffmpeg-skill
- 收录：2026-11-26
- 更新：2026-11-27

### Agents365-ai/drawio-skill — 10,965 ★
自然语言、代码、Terraform / K8s / SQL / OpenAPI 转可编辑 drawio 架构图。

- 亮点：支持增量同步、漂移对比，可导出 HTML / PPTX / Mermaid，架构图能进 CI。
- 链接：https://github.com/Agents365-ai/drawio-skill
- 收录：2026-11-26
- 更新：2026-11-27

### op7418/guizang-social-card-skill — 8,284 ★
小红书图文与公众号封面成套产出。

- 亮点：28 种版式、10 套主题，单文件 HTML 直接渲染 PNG，做图不靠试提示词。
- 链接：https://github.com/op7418/guizang-social-card-skill
- 收录：2026-11-26
- 更新：2026-11-27

### heydamir/unslop — 22,383 ★
把「一眼 AI 感」的界面重做成有设计感的成品：喂进 Claude 一段 vibecoded UI，它按设计规范改写。

- 亮点：10 月底建仓，一个月涨到 2.2 万星，说明「去 AI 味 UI」是刚需；README 给的是诊断清单和改造步骤，适合当设计审稿的第二双眼睛。
- 链接：https://github.com/heydamir/unslop
- 收录：2026-11-27
- 更新：2026-11-27

### patch-gg/pixelfx — 9,573 ★
244 种像素艺术特效，每种都是一小段可读代码，另附一个 Claude Code skill 让 agent 直接调用。

- 亮点：不是滤镜参数堆砌，效果以代码为单位，可复用也可改；做像素风、复古游戏美术时省掉手搓 shader。
- 链接：https://github.com/patch-gg/pixelfx
- 收录：2026-11-27
- 更新：2026-11-27

### mromidev/claude-animated-shorts — 5,139 ★
免费 Claude skill：用 three.js 在 3D 世界里驱动 2D 角色，产出短视频动画。

- 注意：末次提交 2026-11-01，属于「能跑但迭代放缓」，用前先翻 issues 看已知问题。
- 链接：https://github.com/mromidev/claude-animated-shorts
- 收录：2026-11-27
- 更新：2026-11-27

## 候选待观察

### athola/claude-night-market — 356 ★
23 个 Claude Code 插件集合：TDD 强制钩子、git / PR 工作流、spec-driven 开发。

- 状态：更新活跃但体量小，暂列候选。
- 链接：https://github.com/athola/claude-night-market
- 收录：2026-11-26
