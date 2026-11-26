# 国内社区与工具

> 小红书、腾讯 SkillHub、即刻 / V2EX / 掘金上讨论较多的 AI 工具、skill 玩法与平台形态。
> 说明：小红书站内需登录且反爬，本文件条目为公开文章或聚合页转述，均附原文链接；Star / 热度为采集当日数值。

## Skill 榜单与平台

### skills.sh 安装榜
榜首 find-skills 累计约 451 万次安装，其后为 grill-me（反复追问把需求问清）、tdd、handoff（写交接文件给下一个会话）、triage（分流问题）。

- 观察：头部全是"少让 AI 添乱"的基础能力，不是神技。
- 来源：https://post.smzdm.com/p/apqrdpo0/
- 收录：2026-11-26

### SkillsMP（420 万 Agent Skills 索引）
公开可搜索的技能索引，条目指回原始仓库与 SKILL.md，提供 REST API 与 MCP server，网页搜索免费无需登录。

- 用途：按关键词 / 类别 / 职业检索候选，再读源文件判断可信度。
- 来源：https://www.163.com/dy/article/LCITK9LP05561FZV.html
- 收录：2026-11-26

### 腾讯 SkillHub · 热点内容 skill
从热点到可发布的成套内容：3 个切入角度、3:4 图文卡片、9:16 口播成片、配乐与字幕。

- 链接：https://skillhub.cloud.tencent.com/skills/beatra-ai/hot-topic-content-maker
- 收录：2026-11-26

### 腾讯 CodeBuddy Code 2.0 · Skills 机制
腾讯版 Claude Code 从 2.0 起支持 Skills：目录里放 SKILL.md（触发条件与步骤）、提示词模板、脚本，模型按描述自动 match 后执行。作者用它在终端跑通"主题 → 封面文案 → 调图像模型 → 重命名归档"的小红书封面链路。

- 亮点：Skills 本身不绑模型通道，迁到自己的统一入口只需改 Base URL / Key / Model 三件套。
- 来源：https://blog.csdn.net/weixin_42613017/article/details/171299914
- 收录：2026-11-26

### 腾讯云 WorkBuddy：技能、专家、专家团怎么配
官方文档口径的梳理：技能 = 怎么做，专家 = 谁来做 / 按什么标准，专家团 = 谁分工怎么协作；结论是"先想任务、再去装、用哪个开哪个"。

- 观察：一次装二三十个技能会变慢，同类技能互相试错，简单任务也绕远路；适合给团队定安装纪律。
- 来源：https://cloud.tencent.com/developer/article/2792204
- 收录：2026-11-26

## 小红书相关工具

### 红鸦 AI「小红书图文批量生成与发布」
给主题或商品照片，返回标题、正文、封面与内页成图，可同步到平台编辑器。

- 来源：https://blog.csdn.net/weixin_44685055/article/details/171154645
- 收录：2026-11-26

### 运营 Agent 工厂 · xhs-skill
按关键词抓小红书笔记正文与评论，按互动量排序取头部，结果可直接落飞书表格。

- 来源：https://www.myzaker.com/article/6b07063b8e9f093221172e0b
- 收录：2026-11-26

### 小红书「搭搭」（内测）
把个人生活经验做成可分享、可付费的 Agent，值得关注平台侧 Agent 形态。

- 来源：https://www.woshipm.com/?p=6496381
- 收录：2026-11-26

### 小红书八类运营 Skill 清单（选题 → 分发）
按八个环节拆分的开源 skill 清单：content-strategist（选题策略）、dbskill（标题体检 / AI 味检测）、xhs-writer-skill（卖点 → 正文 → 标签）、trending（热搜）、space-image-studio（一句话出封面，4 类 × 12 风格）、html-anything（转单文件 HTML 分发）、xhs-ai-workflow（全链路）。

- 注意：清单只是索引，实际效果取决于内容判断与平台规则，工具不替代运营决策；同时段有创作者反馈无差别套模板、伪造体验容易被限流。
- 来源：http://m.baoshan.sh-tyd.com/xxynews/202611/239_article67393.shtml
- 收录：2026-11-26

### xiaohongshu-mcp（xpzouying） — 17,345 ★
小红书 MCP server：13 个工具覆盖发布图文 / 视频、取笔记与互动数据，另有浏览器插件版 x-mcp 免部署。

- 亮点：国内平台里少见的「能真的发出去」的 MCP，OpenClaw / Claude Code 都能接；插件版直接在 Chrome / Edge 本地跑，绕开服务器 IP 风控。
- 注意：平台反爬与账号风控仍在，批量操作前先用小号验证。
- 链接：https://github.com/xpzouying/xiaohongshu-mcp
- 收录：2026-11-27

### 掘金《在AGI时代到来前，把我的 mcp，skill，prompt 分享给你们》
按「Skill 管能力底座 / Prompt 管表达 / MCP 管连接」三层组织的实操合集，13 个常用工具，含小红书封面 prompt 与「文生图提示词架构师」完整角色设定。

- 亮点：小红书封面 prompt 明确约束「50–100 个英文单词、必含色彩与光影描述」，输出能直接贴进生图工具；文生图架构师那条要求中英双版本 + 意图澄清，比堆形容词稳。
- 来源：https://article.juejin.cn/post/7709818243503636534（2026-11-20）
- 收录：2026-11-27
