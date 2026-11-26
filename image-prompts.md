# 生图 Prompt：库与模板

> 图像生成提示词库（Nano Banana Pro / GPT Image / Midjourney / Flux / Seedream 等）与可直接复用的模板。
> 维护：每天 07:00 / 19:00 增量追加；Star 为采集当日数值（2026-11-26）。

## 提示词库

### YouMind-OpenLab/awesome-nano-banana-pro-prompts — 13,873 ★
目前最大的 Nano Banana Pro 提示词库，1 万+ 条、16 种语言、带预览图，当日有提交。

- 链接：https://github.com/YouMind-OpenLab/awesome-nano-banana-pro-prompts
- 收录：2026-11-26
- 更新：2026-11-26

### YouMind-OpenLab/awesome-gpt-image-2 — 10,337 ★
2000+ 条 GPT Image 2 提示词，每日更新，带预览与多语言版本。

- 链接：https://github.com/YouMind-OpenLab/awesome-gpt-image-2
- 收录：2026-11-26

### ZeroLu/awesome-nanobanana-pro — 10,422 ★
Nano Banana Pro 精选提示词与成图案例集，按「写实与美学 / 创意实验」等章节组织，每条附上原文 prompt 与出处。

- 亮点：模板都是可直接套的完整句式，不是效果图堆砌；同一作者另有 Seedance 视频提示词库，图文一条线。
- 链接：https://github.com/ZeroLu/awesome-nanobanana-pro
- 收录：2026-11-26

### TanShilongMario/PromptFill — 1,957 ★
给 AI 绘图用的可视化「填空」提示词工作台：把长 prompt 拆成槽位，构建、管理、迭代。

- 亮点：中文界面，适合把一次性灵感沉淀成可复用结构；支持 GPT / Midjourney / Nano Banana。
- 链接：https://github.com/TanShilongMario/PromptFill
- 收录：2026-11-26

### VigoZhao/AI-Visual-Prompt-Cookbook — 902 ★
把提示词做成 JSON 风格包，抄一份 style 即可保持整组图统一调性。

- 适用：批量出系列图、电商套图。
- 链接：https://github.com/VigoZhao/AI-Visual-Prompt-Cookbook
- 收录：2026-11-26

### Jermic/awesome-aiart-pics-prompts — 628 ★
3000+ Gemini Nano Banana Pro 提示词与生成案例，中英双语，覆盖摄影、设计、艺术、营销。

- 注意：末次提交 2026-08，更新放缓。
- 链接：https://github.com/Jermic/awesome-aiart-pics-prompts
- 收录：2026-11-26

### langgptai/Awesome-Multimodal-Prompts — 288 ★
GPT-4V 与 DALL·E 3 多模态提示词合集，偏能力演示与用法参考。

- 链接：https://github.com/langgptai/Awesome-Multimodal-Prompts
- 收录：2026-11-26

### gpt-img-2/ai-image-prompt-cookbook — 114 ★
纯中文提示词库，专攻女装、童装、电商主图、产品摄影、小红书封面、广告海报。

- 注意：末次提交 2026-07，内容偏电商模板。
- 链接：https://github.com/gpt-img-2/ai-image-prompt-cookbook
- 收录：2026-11-26

### junxiaopang/all-image-prompts — 64 ★
聚合 Gemini、Midjourney、GPT、Flux、Grok、Seedream 多模型提示词，含在线预览。

- 链接：https://github.com/junxiaopang/all-image-prompts
- 收录：2026-11-26

## 可复用模板

### 模板 1：自拍 → 职业商务照（Nano Banana Pro，人脸保持一致）

> Keep the facial features of the person in the uploaded image exactly consistent. Dress them in a professional navy blue business suit with a white shirt. Background: clean, solid dark gray studio photography backdrop with a subtle gradient, slightly lighter behind the subject and darker towards the edges. Photography Style: Shot on a Sony A7III with an 85mm f/1.4 lens, creating a flattering portrait compression. Lighting: classic three-point lighting setup. Render natural skin texture with visible pores, not an airbrushed look. Add natural catchlights to the eyes. Final image: ultra-realistic, 8k professional headshot.

- 改造点：替换 `navy blue business suit` 与 `dark gray backdrop` 换气质；`visible pores, not an airbrushed look` 是防止磨皮过度的关键句。
- 来源：awesome-nanobanana-pro 第 1.5 节，经 CSDN 转述（二手引用）。

### 模板 2：四槽公式（主体 → 风格 → 环境 → 技术参数）

> 一家街角复古咖啡店，红砖外墙挂着暖色串灯，玻璃窗内咖啡师正低头拉花，窗外是黄昏时的薄雨，窗内暖黄灯光与街面冷色形成对比，45 度侧视机位，中焦镜头，胶片颗粒感，8K 细节

- 用法：四槽结构固定，换主体即可批量套用；只写"好看的咖啡店"出来就是图库图，差别在光从哪来、机位在哪。
- 来源：CSDN 公开文章示例。

### 模板 3：年代感用设备参数，不用形容词

| 想要的年代感 | 写进 prompt 的参数 | 出来的效果 |
| --- | --- | --- |
| 90 年代闪光灯 | 1990s-style camera, direct front flash, 35mm lens | 硬闪、暗背景、怀旧光晕 |
| 胶片电影感 | Kodak Portra 400, Golden Hour, film grain, soft focus, bokeh | 暖调颗粒、虚化城市灯光 |
| 日本学生随拍 | low-quality disposable camera, clumsy snapshot, 3:2 | 低质、歪斜、生活感 |
| 千禧年数码机 | early-2000s digital camera aesthetic, harsh flash, muted cool tones | 高光过曝、屏幕颗粒 |

### 模板 4：七层结构

交付目标 → 主体与场景材质 → 机位光线 → 画面文字 → 比例色彩 → 风格参考 → 负面约束。

- 用法：先写用途再挑模板，比刷图后反推省事。
- 来源：istarry 公开文章。

### 模板 5：杂志封面板式

高级时尚封面：参考图定人 → 黑白人像 + 米白背景 → 低机位、下颅线清晰 → 超大衬线标题压住头顶 → 侧栏文字 + 发行日期 → 高分辨率竖版比例。

- 完整中文 prompt 见来源（awesome-gpt-image-2-prompts 中文镜像）。
- 来源：https://github.com/liuxin2533/awesome-image-prompts

### 模板 6：漂浮奢侈品产品图（Nano Banana Pro，填空式，原文可直用）

> Product:
> [BRAND] [PRODUCT NAME] - [bottle shape], [label description], [liquid color]
>
> Scene:
> Luxury product shot floating on dark water with [flower type] in [colors] arranged around it.
> [Lighting style - e.g., "golden hour glow" / "bright fresh light"] creates reflections and ripples across the water.
>
> Mood & Style:
> [Adjectives - e.g., "ethereal and luxurious" / "fresh and clean"], high-end commercial photography, [camera angle], shallow depth of field with soft bokeh background

- 适用模型：Nano Banana Pro（同结构也可用于 GPT Image 2 / Midjourney）。
- 用法：三组方括号先填品牌 / 瓶型 / 液体色，再选光位与形容词；水面包围物换成花、冰块、水果就能跨品类复用（香水、酒、护肤品）。
- 来源：ZeroLu/awesome-nanobanana-pro 第 1.17 节（原作者 AmirMušić，@AmirMushich 的 X 帖子）。
- 收录：2026-11-26
