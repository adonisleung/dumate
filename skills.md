# Skill / 插件（Agent Skills）

> 面向 Claude Code、Codex、Cursor 等编码 agent 的 Skill 与插件仓库。
> 维护：每天 06:30 / 18:30 增量追加，已收录条目不再重复写入。
> Star 为采集当日数值（2026-11-28），仅作参考。

## 官方与高星

### anthropics/skills — 201,691 ★
Anthropic 官方 Agent Skills 仓库，生产级文档技能（docx / pdf / pptx / xlsx）开源，附 skill 规范与模板。

- 亮点：可直接当作 skill 写法参考；官方维护，兼容性最好。
- 链接：https://github.com/anthropics/skills
- 收录：2026-11-26
- 更新：2026-11-28

### obra/superpowers — 328,634 ★
agentic 技能框架与软件开发方法论。

- 亮点：`/brainstorm` → `/write-plan` → `/execute-plan` 三段式，强制先问清需求再动手。
- 链接：https://github.com/obra/superpowers
- 收录：2026-11-26
- 更新：2026-11-28

### VoltAgent/awesome-agent-skills — 37,601 ★
1000+ 精选技能目录，人工筛选并标注兼容 Claude Code / Codex / Cursor / Gemini CLI 等。

- 亮点：找技能比翻 GitHub topics 快，适合当索引用。
- 链接：https://github.com/VoltAgent/awesome-agent-skills
- 收录：2026-11-26
- 更新：2026-11-28

### heygen-com/hyperframes — 91,750 ★
HeyGen 官方开源的 AI 视频编辑器：改自己的素材，或用 Claude Code / Codex 从零重做一条视频。

- 亮点：写 HTML 再渲成 MP4，动效走 GSAP，成片可版本化；Apache-2.0，另有免费 Studio 桌面版。
- 链接：https://github.com/heygen-com/hyperframes
- 收录：2026-11-26
- 更新：2026-11-28

### alibaba/open-code-review — 56,991 ★
阿里开源的代码审查工具：确定性流水线 + LLM Agent 混合架构，精确到行级评论。

- 亮点：内置多语言规则集（NPE、线程安全、XSS、SQL 注入），兼容 OpenAI / Anthropic 接口，可挂 Claude Code、Codex、Cursor。
- 链接：https://github.com/alibaba/open-code-review
- 收录：2026-11-26
- 更新：2026-11-28

### obsidianmd/obsidian-skills — 54,460 ★
Obsidian 官方开源的 Agent Skills 集合：让 agent 读写 Obsidian 库，以及 Markdown、Bases、JSON Canvas 这些开放格式。

- 亮点：严格按 Agent Skills 规范写，Claude / ChatGPT / Codex / Cursor / Copilot / OpenCode 都能装；Obsidian 本身已是 Claude、ChatGPT、Cursor、Kiro 的官方插件；Claude Code 里 `claude plugin marketplace add obsidianmd/obsidian-skills` 两行装完，之后 `claude plugin update` 跟着官方升级。
- 链接：https://github.com/obsidianmd/obsidian-skills
- 收录：2026-11-28

### affaan-m/ECC — 312,097 ★
agent harness 性能优化系统：skills、instincts、memory、安全约束与研究优先的开发流程，一套装到 Claude Code / Codex / OpenCode / Cursor。

- 亮点：年初建仓、11 月已 31 万星，是 skills 类里星数最高的一档；以 `ecc@ecc` 插件形态安装，MIT 永久开源，Pro 是面向私有仓库的托管 GitHub App（19 美元/席位/月起）；11-23 仍有提交。
- 注意：README 反复强调只从官方渠道（GitHub 仓库、npm 包 ecc-universal / ecc-agentshield、GitHub App、ecc.tools）安装，第三方镜像可能被投毒；模块多，先按 guided setup 跑一遍再决定留哪些。
- 链接：https://github.com/affaan-m/ECC
- 收录：2026-11-28

### anthropics/claude-plugins-official — 48,507 ★
Anthropic 官方的 Claude 插件市场与自维护插件仓库，第三方插件的提交入口已统一到 claude.ai/directory/manage。

- 亮点：官方一手渠道，`/plugin install {plugin-name}@claude-plugins-official` 直接装；仓库分 `/plugins`（Anthropic 团队自研）与 `/external_plugins`（早期收录的第三方，以及 Discord、iMessage、Telegram 等通道插件）；`/plugins/example-plugin` 是官方给的插件写法参考实现，每个插件目录在 PR 时都会过检查。
- 注意：官方明确声明不审核插件内含的 MCP server 与文件行为，装前仍要看插件主页；`marketplace.json` 正在收缩为只列 Anthropic 自家插件，第三方走网页目录。
- 链接：https://github.com/anthropics/claude-plugins-official
- 收录：2026-11-28

### google-labs-code/stitch-skills — 13,705 ★
Google Stitch 的 Agent Skills 与插件集，按 Agent Skills 开放标准组织，把「设计稿 → 可运行前端」这一段落进编码 agent。

- 亮点：拆成 stitch-design / stitch-build / stitch-utilities 三个插件，按需要装；Codex、Antigravity、Gemini CLI、Claude Code、Cursor、OpenCode 均支持，Codex 可用 `codex plugin marketplace add ... --sparse` 只拉插件目录，clone 快；11-28 仍在提交。
- 注意：依赖 Stitch 服务与 Google 账号；OpenCode 走手动安装，不是 marketplace 一条命令。
- 链接：https://github.com/google-labs-code/stitch-skills
- 收录：2026-11-28

### github/awesome-copilot — 41,646 ★
GitHub 官方组织维护的 Copilot 定制合集：agents、instructions、skills、hooks、workflows、plugins，内容由社区贡献。

- 亮点：官网 awesome-copilot.github.com 支持全文检索与筛选，另有机器可读的 `llms.txt`，agent 可直接取清单；skills 以自包含文件夹交付（说明 + 随附资源），与 Agent Skills 结构一致，能当跨生态的写法参照；11-27 仍有提交。
- 注意：社区投稿，条目质量参差，选中的 skill 仍要读一遍再装。
- 链接：https://github.com/github/awesome-copilot
- 收录：2026-11-28

## 单点能力 skill

### morluto/rea — 481,582 ★
把逆向分析装进 agent：本地读取原生二进制、Electron / JS、.NET 程序集与网站，讲清某个功能是怎么实现的。

- 亮点：`npx rea-agents setup` 自动注册 MCP 连接与调查 skill；可复用已有的 Hopper / Ghidra / IDA，分析全程在本地，结论附证据与局限。
- 注意：面向逆向与安全研究，先确认被测对象的授权范围。
- 链接：https://github.com/morluto/rea
- 收录：2026-11-26
- 更新：2026-11-28

### kajisho5/ffmpeg-skill — 12,097 ★
给编码 agent 用的本地视频编辑器，42 个 FFmpeg 工具封装成机器可读契约，附 MCP server。

- 亮点：切割、字幕、转码可用一句话调用，输出可验证。
- 链接：https://github.com/kajisho5/ffmpeg-skill
- 收录：2026-11-26
- 更新：2026-11-28

### Agents365-ai/drawio-skill — 10,968 ★
自然语言、代码、Terraform / K8s / SQL / OpenAPI 转可编辑 drawio 架构图。

- 亮点：支持增量同步、漂移对比，可导出 HTML / PPTX / Mermaid，架构图能进 CI。
- 链接：https://github.com/Agents365-ai/drawio-skill
- 收录：2026-11-26
- 更新：2026-11-28

### op7418/guizang-social-card-skill — 8,292 ★
小红书图文与公众号封面成套产出。

- 亮点：28 种版式、10 套主题，单文件 HTML 直接渲染 PNG，做图不靠试提示词。
- 链接：https://github.com/op7418/guizang-social-card-skill
- 收录：2026-11-26
- 更新：2026-11-28

### heydamir/unslop — 22,813 ★
把「一眼 AI 感」的界面重做成有设计感的成品：喂进 Claude 一段 vibecoded UI，它按设计规范改写。

- 亮点：10 月底建仓，一个月涨到 2.2 万星，说明「去 AI 味 UI」是刚需；README 给的是诊断清单和改造步骤，适合当设计审稿的第二双眼睛。
- 链接：https://github.com/heydamir/unslop
- 收录：2026-11-27
- 更新：2026-11-28

### patch-gg/pixelfx — 9,699 ★
244 种像素艺术特效，每种都是一小段可读代码，另附一个 Claude Code skill 让 agent 直接调用。

- 亮点：不是滤镜参数堆砌，效果以代码为单位，可复用也可改；做像素风、复古游戏美术时省掉手搓 shader。
- 链接：https://github.com/patch-gg/pixelfx
- 收录：2026-11-27
- 更新：2026-11-28

### mromidev/claude-animated-shorts — 5,265 ★
免费 Claude skill：用 three.js 在 3D 世界里驱动 2D 角色，产出短视频动画。

- 注意：末次提交 2026-11-01，属于「能跑但迭代放缓」，用前先翻 issues 看已知问题。
- 链接：https://github.com/mromidev/claude-animated-shorts
- 收录：2026-11-27
- 更新：2026-11-28

### DietrichGebert/ponytail — 200,392 ★
让 agent 像「屋里最懒的资深工程师」那样思考：先看仓库里已经有什么，能不写的代码就不写。

- 亮点：Ponytail 5 在 Claude Code 实测（39 个任务、含真实 FastAPI + React 仓库，Opus 5.5，各跑 5 次）代码量 -53%、耗时 -41%、成本 -26%、token -45%，而 98% 的风险逻辑仍带测试（不用它时 68%）；`/ponytail-review` 按改动审查、`/ponytail-audit` 全库审查，都只报「变差」的项并给出怎么修、不修会怎样；Claude Code 2.1.290+ 可在 prompt 上方挂一条用量/成本/复用率/测试状态条。
- 注意：它的「懒」有明确边界——校验、错误处理、安全、无障碍不在删减范围内；适合代码膨胀、过度设计的项目，不适合从零起步的脚手架。
- 链接：https://github.com/DietrichGebert/ponytail
- 收录：2026-11-28

## 候选待观察

### athola/claude-night-market — 356 ★
23 个 Claude Code 插件集合：TDD 强制钩子、git / PR 工作流、spec-driven 开发。

- 状态：更新活跃但体量小，暂列候选。
- 链接：https://github.com/athola/claude-night-market
- 收录：2026-11-26
