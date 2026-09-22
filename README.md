# DSH

DeepSeek Harness（DSH）的社区资源导航。这里汇总入门教程、相关产品，以及社区开源项目，方便查找客户端、插件和工具。

开源项目按用途分类，涵盖创作与办公、市场、界面与上下文、Agent 与工作流、客户端、浏览器与视觉、安全、记忆、搜索接入和插件开发。每一类按 GitHub stars 从高到低排列，并附上中文简介。

#### 教程
- [deepseek harness中文详细学习教程](https://github.com/ht426/deepseek-harness-tutorial)
- [DeepSeek Harness 的入门第一课](https://github.com/pingfanfan/hello-dsh/blob/main/README.zh.md)
- [DeepSeek Harness 官方教程](https://deepseek-harness.github.io/deepseek-harness/develop/basic/)
- [DeepSeek Harness 白皮书 · dsh-handbook](https://electricitysheep.github.io/dsh-handbook/#/)

#### 产品
- [Jingyun DSH 客户端](https://jingyun.studio/zh/jingyun-dsh)

#### 开源

按 GitHub stars 降序（2026-09-22）。分类按该类最高 stars 排列，类内同样降序。简介为仓库当前介绍的中文。

##### 创作、图像与办公
- [archify](https://github.com/tt-a1i/archify) ★69674 — 用于绘制美观、可核对的架构图、工作流、时序图、数据流与生命周期图的 Agent 技能，输出带动态效果、可清晰导出的独立 HTML。
- [dsh-image-gen](https://github.com/shanliuling/dsh-image-gen) ★448 — DeepSeek Harness 的 AI 图像工作室：在对话中生成、编辑和对比图片，含 500+ 提示词、图库、多模型工作流与 ComfyUI。
- [oh-story-dsh](https://github.com/zenstory-ai/oh-story-dsh) ★396 — DeepSeek 写网文/小说的工作流插件：DeepSeek Harness 社区插件，内置小说、短剧、游戏、视频解说四个工作台。
- [dsh-univer-office](https://github.com/dream-num/dsh-univer-office) ★382 — 为 DeepSeek Harness 提供真正的办公环境。Univer Office 插件把表格、文档、幻灯片、画布、关系表等放进同一运行时，支持关联数据、校验、版本化变更，以及面向多 Agent 协作的隔离工作区。
- [dsh-oil-creator](https://github.com/oil-oil/dsh-oil-creator) ★191 — 面向 DeepSeek Harness 的 AI 辅助本地创作者工作台。
- [DSH-Creator](https://github.com/Jackywxsz/DSH-Creator) ★101 — Jacky Creator：面向内容创作者的 DeepSeek Harness 本地内容与运营工作台。
- [dsh-imagegen](https://github.com/dickpy/dsh-imagegen) ★84 — DeepSeek Harness Web 界面的 AI 图像生成插件：通过 OpenAI 兼容接口进行文生图与图生图，并支持跨设备共享历史记录。
- [dsh-comfyui](https://github.com/fandc520/dsh-comfyui) ★80 — 一个基于 DeepSeek Harness 的 ComfyUI 插件。
- [dsh-short-video-studio](https://github.com/fengyungithub/dsh-short-video-studio) ★9 — 基于 DeepSeek Harness 和 ComfyUI 的 AI 视频创作工作台。

##### 市场与生态
- [dsh-web](https://github.com/zhu1090093659/dsh-web) ★7935 — DeepSeek Harness Web 插件聚合生态 · 万物皆插件，通过创意工坊分发。
- [dsh-market](https://github.com/dsh-market/dsh-market) ★4377 — DeepSeek Harness 内置的可视化插件市场，支持浏览、搜索与一键安装 · [dshmarket.com](https://dshmarket.com/zh/)
- [dshfind](https://github.com/hikariming/dshfind) ★264 — DSH（DeepSeek Harness）原理学习、插件市场与最佳实践。
- [dsh-skin-market](https://github.com/kingOfSoySauce/dsh-skin-market) ★156 — DeepSeek Harness 皮肤市场，已收录 200+ 款皮肤，含评分与人工审核、社区收录入口；支持在线浏览，也可用插件管理本地皮肤。

##### 界面与上下文
- [DSH-better-sidebar](https://github.com/omdsh-dev/DSH-better-sidebar) ★3713 — 开放的侧边栏底座，支持三方扩展注册新侧边栏页面。内置文件渲染编辑、终端、侧边对话、Git 与子代理页面。
- [dsh-context](https://github.com/bowenliang123/dsh-context) ★1482 — 一站式 DeepSeek Harness 上下文可视化插件，提供 Context 面板、浏览器、侧边栏与 Context 命令，透视上下文的组成、演进、压缩与剪枝。
- [dsh-at-file](https://github.com/FSMargoo/dsh-at-file) ★512 — 为 DeepSeek Harness 提供 Codex 风格的 @file 引用：在输入框搜索工作区文件，并把路径附加到提示词。
- [dsh-genui](https://github.com/omdsh-dev/dsh-genui) ★473 — DeepSeek Harness 的生成式界面：通过 dsh-ui 代码块在助手回复中内嵌交互组件，包括布局、图表、绘图、表单、测验、Mermaid 与 3D 场景，并把操作回传给模型。附带宿主插件、浏览器渲染端与 genui 技能。
- [dsh-skill-mcp-panel](https://github.com/Fishquito7/dsh-skill-mcp-panel) ★144 — DSH Web 界面插件：技能与 MCP 管理工具。
- [dsh-raw-html-v2](https://github.com/plolpl789/dsh-raw-html-v2) ★52 — 面向 DeepSeek Harness 的 VCP 视觉联觉插件 v2（官方 Slot API）：原始 HTML 卡片、流式渲染，支持 KaTeX、Mermaid、SVG 与内置字体。
- [dsh-message-edit](https://github.com/Moeblack/dsh-message-edit) ★49 — DSH 插件：分支式消息编辑、重掷、重试与版本时间线。

##### Agent 与工作流
- [dsh-agent-teams](https://github.com/NanmiCoder/dsh-agent-teams) ★1766 — DeepSeek Harness 的 Agent Teams 插件。
- [dsh-plugin-agent-workflow](https://github.com/xuanyuanzhifeng/dsh-plugin-agent-workflow) ★167 — DeepSeek Harness 的 Agent 工作流插件。
- [dsh-automation](https://github.com/titanwings/dsh-automation) ★99 — DSH 自动化插件：让编码任务按计划在全新 Agent 会话中运行，并由用户或 Agent 创建和管理定时任务。
- [dsh-Visual-Workflow](https://github.com/GZX2211/dsh-Visual-Workflow) ★30 — 专为 DeepSeek Harness Web 界面打造的可视化多 Agent 工作流编排插件。公开测试版已上线，正式版将随 DSH 正式版发布。目前已对齐候选版 dsh v0.1.5-rc.2，不适配 Alpha 版。待官方 Team 功能稳定后，会引入「协作组」节点。

##### 客户端与运行时
- [dsh-pocket](https://github.com/shaobeichen/dsh-pocket) ★1290 — 把 DeepSeek Harness 装进你的口袋：电脑上跑 dsh web，手机扫码即同步访问（局域网 + 公网，实时同屏）。
- [dshcode](https://github.com/whitelonng/dshcode) ★714 — DeepSeek Harness 的社区桌面伴侣：面向 macOS 与 Windows 的一键 Electron 应用。
- [jingyun-dsh](https://github.com/jingyunstudio/jingyun-dsh) ★564 — 基于 Jingyun Studio 与 DeepSeek Harness 打造的一站式 AI 商业化桌面客户端，可将智能体、技能与工作流转化为可交易商品。覆盖登录注册、会员、订阅支付、云端资产与多端同步，让开发者把智能体封装成独立商业产品。
- [oh-dsh](https://github.com/hust-open-atom-club/oh-dsh) ★321 — 一套 DSH 运行时，提供桌面、Web 与 TUI 三种开发体验。
- [dsh-mobile](https://github.com/saya-ch/dsh-mobile) ★295 — DeepSeek Harness 的 Android 应用与安全远程访问插件，支持局域网和远程连接，以及可高度自定义的移动界面与扩展能力。
- [DSH-X](https://github.com/yyh-001/DSH-X) ★289 — DeepSeek Harness 轻量 Windows 启动器。选一个版本，启动 dsh web。
- [dsh-code](https://github.com/UNLINEARITY/dsh-code) ★37 — 面向 DeepSeek Harness 的 Claude Code 风格 TUI。结合 DSH 的核心机制，以及 Codex CLI、Claude Code、Pi agent 等交互方式。对齐官方上游最新 RC，支持特殊模式、插件、模型管理、子代理管理与切换模型动画。自 1.0.0 起由项目自身迭代，不依赖外部 Agent 或 CLI 完成开发。

##### 浏览器与视觉
- [dsh-vision-router](https://github.com/ysr666/dsh-vision-router) ★1113 — 为纯文本 DeepSeek Harness Agent 提供视觉能力：内置免 Key 的视觉链路，以及像素级工具（问答、定位、裁剪、像素对比、取色、OCR、SVG 描摹、抠图、截图）。一行命令安装，无需 Python。
- [dsh-vision-toolkit](https://github.com/Anionex/dsh-vision-toolkit) ★884 — 为纯文本模型设计的视觉工具箱：一行安装、粘贴图片直接识别、多图问答、长截图 OCR，以及把截图还原为前端界面。
- [dsh-browser](https://github.com/omdsh-dev/dsh-browser) ★714 — Chrome 侧边栏扩展，让 DeepSeek Harness 直接操控浏览器，无需视觉能力。
- [dsh-ego-browser](https://github.com/Fisfzy/dsh-ego-browser) ★187 — 把面向 AI Agent 的 ego-lite 浏览器接入 DeepSeek Harness，提供 13 个结构化工具（文本语义快照、语义定位点击、表单填充、截图、CDP 控制、任务空间隔离）。内置运行时，Linux 与 Chrome 开箱即用。

##### 安全与逆向
- [dsh-pentest](https://github.com/howmp/dsh-pentest) ★529 — 面向 DeepSeek Harness 的渗透测试模式。
- [dsh-reverse-skill](https://github.com/dhicoc/dsh-reverse-skill) ★162 — 把完整的逆向技能包（87 个 SKILL.md）做成 DeepSeek Harness 插件，覆盖逆向工程、授权渗透测试与安全研究。
- [deepspider](https://github.com/ma-pony/deepspider) ★20 — AI 原生智能爬虫与 JavaScript 逆向工程平台，基于 DSH、Patchright/CDP 与独立语义运行时，从浏览器证据恢复参数生成逻辑，并交付可验证的求解器。

##### 记忆
- [dsh-mnemon](https://github.com/omdsh-dev/dsh-mnemon) ★395 — 面向 DeepSeek Harness 的可组合、基于视图的记忆。来源与策略可插拔，开箱提供三层记忆。
- [dsh-memory-evolve](https://github.com/csyangwen/dsh-memory-evolve) ★327 — 为 DeepSeek Harness 带来跨会话长期记忆与后台自我进化的纯插件：五轨记忆、Git 分支感知、回合内自我审查、技能自我进化与技能管理器、四轨待办、调度、会话广播与搜索、提示词管理器、临时便签。零核心修改、零运行时依赖。
- [dsh-memory](https://github.com/FuRongJun-1999/dsh-memory) ★236 — 白箱 AGI 架构探索：元认知（自我认知循环）、持续学习（知识飞轮）、世界模型（条件空间与语义时空图）、自我改进，以及零 LLM 白箱管线与可审计的信任护栏。
- [dsh-meow-memory](https://github.com/Phant0Meow/dsh-meow-memory) ★113 — DeepSeek Harness 的跨会话记忆插件：七层 SQLite 存储（灵魂、用户、项目、事实、教训、主题、规则），BM25 检索，并按窗口进行梦境整理。

##### 搜索、数据与接入
- [dsh-free-search](https://github.com/DDDMUC/dsh-free-search) ★231 — 面向 DeepSeek Harness 的免费网页搜索，后端为 DuckDuckGo，无需 API Key。
- [dsh-data-agent](https://github.com/omdsh-dev/dsh-data-agent) ★198 — 把 DSH 接到数据库，用对话做数据分析，并给出可执行的业务洞察。
- [dsh-deepseek-web-login](https://github.com/cv-superding/dsh-deepseek-web-login) ★121 — 非官方 DSH 插件：把 chat.deepseek.com 的网页模型当作模型提供方，支持浏览器登录捕获、工作量证明求解、SSE 流式输出，以及基于提示的工具调用。
- [dsh-qqbot](https://github.com/tencent-connect/dsh-qqbot) ★106 — 让 QQ Bot 接入 DeepSeek Harness 的官方插件。

##### 插件开发
- [dsh-plugin-upgrade-skill](https://github.com/oh-my-dsh/dsh-plugin-upgrade-skill) ★137 — 帮助插件随 dsh 版本自动升级的技能。
