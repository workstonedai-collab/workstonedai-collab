# Workstone

北外 2027 届区域国别研究硕士在读，GKN 团队成员，正在寻找工作与合作机会。我从研究和信息服务出发，与 AI Agent 协作开发研究工具和产品，关注信息从哪里来、任务能否完成，以及结果是否方便使用。

I am a master's student in country and area studies at Beijing Foreign Studies University, graduating in 2027, and a member of Global Knowledge Network (GKN). I work with AI agents to develop research tools and products, with attention to sources, task completion and how people use the results. I am open to job opportunities and collaboration.

这里记录个人参与的开源项目与社区贡献。项目来自不同阶段的尝试：有可独立使用的工具，也有自托管 Alpha 和离线流程示例；具体支持范围与验证情况见各仓库。

This profile brings together open-source projects I work on and contributions to tools we use. They include standalone utilities, self-hosted alpha applications and offline workflow examples. Each repository documents its scope and verification.

[主要项目 / Projects](#start-here--从这里开始) · [工具与示例 / Tools and examples](#more-tools--更多工具) · [社区贡献 / Contributions](#open-source-contributions--开源贡献) · [我与 GKN / About](#about-me--global-knowledge-network) · [工作与合作 / Contact](#work--collaboration--工作与合作)

## Start here / 从这里开始

| 项目 / Project | 做什么 / What it does | 开始使用 / Explore |
| --- | --- | --- |
| **[Market Entry Agent](https://github.com/workstonedai-collab/market-entry-agent)** · 企业出海与营商环境研究 | 结合企业背景、目标市场与经营约束，研究进入路径和待验证条件。自托管 Alpha。 / Research market-entry options and operating conditions against a company's context. Self-hosted alpha. | [公开示例 / Examples](https://github.com/workstonedai-collab/market-entry-agent/tree/main/examples) · [发布 / Releases](https://github.com/workstonedai-collab/market-entry-agent/releases) |
| **[GeoRisk Agent](https://github.com/workstonedai-collab/georisk-agent)** · 地缘政治风险研究 | 围绕人员、资产、航线和业务读取来源，保存风险简报与观察清单。与 Market Entry Agent 共用基座和证据格式。 / Research geopolitical developments against business exposure. Shares a core and evidence format with Market Entry Agent. | [公开示例 / Examples](https://github.com/workstonedai-collab/georisk-agent/tree/main/examples) · [发布 / Releases](https://github.com/workstonedai-collab/georisk-agent/releases) |
| **[Social Media Read for Agent](https://github.com/workstonedai-collab/social-media-read-for-agent)** · 国内社媒读取 | 为本地 Agent 接入小红书、微博、知乎和微信公众号的搜索与阅读；支持图片 OCR 和有限评论，说明实际读取范围。只读预览版。 / Read supported Chinese social platforms from a local agent, with image OCR and bounded comment samples. Read-only preview. | [安装 / Setup](https://github.com/workstonedai-collab/social-media-read-for-agent/blob/main/docs/installation.md) · [虚构演示 / Fictional demo](https://github.com/workstonedai-collab/social-media-read-for-agent/blob/main/docs/assets/offline-demo.jpg) |
| **[Global Knowledge Crawl Pipeline](https://github.com/workstonedai-collab/global-knowledge-crawl-pipeline)** · 全球信息采集程序 | 将网页、订阅源与关键词搜索整理成信息表，支持自选 API 富化、增量更新与来源回执。 / Collect web, feed and search results into tables, with optional API enrichment, incremental updates and source receipts. | [中文离线案例](https://github.com/workstonedai-collab/global-knowledge-crawl-pipeline/blob/main/docs/walkthrough.zh-CN.md) · [English walkthrough](https://github.com/workstonedai-collab/global-knowledge-crawl-pipeline/blob/main/docs/walkthrough.en.md) |
| **[Click-to-CSS](https://github.com/workstonedai-collab/click-to-css)** · 网页样式编辑器 | 点选静态页面中的元素，预览样式、保存回 CSS 源码，并可撤销。 / Select an element in a static page, preview its style, save to CSS source and undo. | [中文操作演示](https://github.com/workstonedai-collab/click-to-css/blob/main/docs/walkthrough.zh-CN.md) · [English walkthrough](https://github.com/workstonedai-collab/click-to-css/blob/main/docs/walkthrough.en.md) |
| **[留白 · A Little Pause](https://github.com/workstonedai-collab/liubai-alittlepause)** | 本机优先的情绪日记，包含照片手帐、主题回看、周笺与小册子；提供网页和浏览器扩展。AI 与同步需要另外配置。 / A local-first mood journal with scrapbooks, themes, weekly letters and booklets, available on the web and as a browser extension. AI and sync require separate setup. | [打开网页版 / Open app](https://workstonedai-collab.github.io/liubai-alittlepause/) · [下载 / Downloads](https://github.com/workstonedai-collab/liubai-alittlepause/releases/latest) |

两个研究 Agent 提供国区看板、来源追溯和多国比较。公开数据的时间、覆盖范围与计算方法见[看板说明](https://github.com/workstonedai-collab/market-entry-agent/blob/main/docs/country-dashboard.md)。它们用于研究参考；部分专用方法、提示词和知识内容暂未开源。

Both research agents include country dashboards, source references and country comparisons. The [dashboard guide](https://github.com/workstonedai-collab/market-entry-agent/blob/main/docs/country-dashboard.md) explains data periods, coverage and calculations. These are research references; some specialized methods, prompts and knowledge remain non-public.

<details>
<summary>信息采集与页面编辑演示 / Collection and CSS editing demos</summary>

下面的信息表来自可重复运行的虚构离线案例，无需账号或模型密钥。 / This table comes from a reproducible fictional offline case, with no account or model key required.

[![信息采集离线输出 / Offline collection output](https://raw.githubusercontent.com/workstonedai-collab/global-knowledge-crawl-pipeline/main/docs/walkthrough-table.png)](https://github.com/workstonedai-collab/global-knowledge-crawl-pipeline/blob/main/docs/walkthrough.zh-CN.md)

点选、预览、保存与撤销的实际操作： / An actual edit, preview, save and undo:

[![Click-to-CSS 操作演示 / Editing demo](https://raw.githubusercontent.com/workstonedai-collab/click-to-css/main/docs/demo.gif)](https://github.com/workstonedai-collab/click-to-css/blob/main/docs/walkthrough.en.md)

</details>

## More tools / 更多工具

| 工具 / Tool | 用途与边界 / Purpose and scope |
| --- | --- |
| [Report Export Kit](https://github.com/workstonedai-collab/report-export-kit) | 本地导出 PDF、Word、Markdown；另有保留版本与长字段的记录表格导出。 / Local report rendering, plus versioned record-workbook export. |
| [Agent Task Recovery Kit](https://github.com/workstonedai-collab/agent-task-recovery-kit) | 为顺序 JavaScript 任务保存检查点、复用结果并限制重试。 / Checkpoint sequential JavaScript tasks, reuse results and bound retries. |
| [AI Evidence Check](https://github.com/workstonedai-collab/ai-evidence-check) | 将字段、引用、数字和日期与提供的原文对照；不替代事实调查。 / Compare fields, quotations, numbers and dates with supplied text; not independent fact-checking. |
| [Public Data Connectors](https://github.com/workstonedai-collab/public-data-connectors) | 接入 World Bank、Eurostat 和 GLEIF，保留单位、期间、缺失状态与来源。 / Read public datasets while retaining units, periods, missing values and provenance. |
| [Miniapp Project Check](https://github.com/workstonedai-collab/miniapp-project-check) | 原生微信小程序的只读静态预检；设备表现仍需另行验证。 / Read-only static checks for native WeChat Mini Programs; device behavior needs separate testing. |

离线模板与示例：**[来源权限规则](https://github.com/workstonedai-collab/source-rights-gate)**、**[资讯去重](https://github.com/workstonedai-collab/bilingual-news-dedupe)**、**[人工批准流程](https://github.com/workstonedai-collab/human-review-research-agent)**、**[小程序长任务](https://github.com/workstonedai-collab/miniapp-ai-task-starter)**。它们展示特定规则或流程，适合参考、改造和验证。

Offline templates and examples cover **[source permissions](https://github.com/workstonedai-collab/source-rights-gate)**, **[news deduplication](https://github.com/workstonedai-collab/bilingual-news-dedupe)**, **[human approval](https://github.com/workstonedai-collab/human-review-research-agent)** and **[long-running miniapp tasks](https://github.com/workstonedai-collab/miniapp-ai-task-starter)**. They demonstrate particular rules or workflows for reuse and adaptation.

[完整项目目录 / Full project catalog](CATALOG.md)

## Open-source contributions / 开源贡献

我们也向实际使用、参考过的项目提交修复和文档。以下状态核对于 **2026-10-22**；待审 PR 的后续状态以链接为准。Fork 用于社区协作，上游项目与原作者归属保持不变。

We also contribute fixes and documentation to projects we use or learn from. Status checked on **2026-10-22**; linked PRs show subsequent changes. Contribution forks retain their upstream project and author attribution.

| 项目 / Project | 贡献 / Contribution | 状态 / Status |
| --- | --- | --- |
| [Kandev #4082](https://github.com/kdlbs/kandev/pull/4082) | 新检出项目的 E2E 准备说明。 / Fresh-checkout E2E setup instructions. | 已合并 / Merged |
| [Trafilatura #944](https://github.com/adbar/trafilatura/pull/944) | 在提取指南补充现有链接发现工具。 / Link existing discovery tools from extraction guidance. | 已合并 / Merged |
| mp-html [#701](https://github.com/jin-yufeng/mp-html/pull/701)、[#702](https://github.com/jin-yufeng/mp-html/pull/702)、[#703](https://github.com/jin-yufeng/mp-html/pull/703) | 表格单元格排版、补充平面数字实体解码、编辑器撤销重做。 / Grid-cell flow, supplementary numeric references, and editor undo/redo. | 待审 / Open |
| [Hermes Agent #140921](https://github.com/NousResearch/hermes-agent/pull/140921) | 修复 launchd 状态未知时的网关状态误报，延续原作者补丁。 / Preserve unknown launchd status in gateway reporting, continuing the original author's patch. | 待审 / Open |
| [Enterprise AI Scenario Map #4](https://github.com/MetaInFLow/Enterprise-ai-scenario-map-skill/pull/4) | 保持 JSON 标准输出可供程序读取。 / Keep JSON stdout machine-readable. | 待审 / Open |
| [Humanizer-zh #46](https://github.com/op7418/Humanizer-zh/pull/46) | 修复结构检查对波浪线及较长代码围栏的保护。 / Protect tilde and longer code fences in structure checks. | 待审 / Open |
| [MarkItDown 协作补丁 / Collaborative patch](https://github.com/ManoharPaturi/markitdown/pull/2) | 列表标记后的代码围栏与空白处理；补丁已由原作者纳入其上游 PR 分支并保留署名。 / Fence and whitespace handling after list markers; adopted into the original author's upstream PR branch with attribution. | [上游 #2529 待审 / Upstream open](https://github.com/microsoft/markitdown/pull/2529) |

[更多贡献、草稿与协作归属 / More contributions, drafts and attribution](CONTRIBUTIONS.md)

## About me & Global Knowledge Network

我是 **Global Knowledge Network（GKN）** 的团队成员。我们依托团队的专业知识与科研背景，面向有出海需求的企业和个人提供咨询与连接服务。团队成员多来自高校；我们帮助客户理解国际环境、分析出海问题，并连接相关资源与合作机会。

当前的工作包括：

- **热点追踪与研判：**持续追踪公开信息，分析事件背景、变化及可能影响。
- **出海与国际议题研究：**围绕市场进入、地缘政治、跨国制裁和出口管制等问题，开展有来源依据的分析。
- **产品与工具：**将 AI Agent 用于研究和业务流程，开发 SaaS、小程序与自动化工具，探索研究成果的交付和使用方式。

这里分享个人参与的开源实践，也保留团队工作的背景。可通用的工具单独整理；客户资料、私人记录、内部部署与未公开知识不放入公开仓库。

I am a member of **Global Knowledge Network (GKN)**. Drawing on the team's research and professional backgrounds, we provide advisory and connection services for businesses and individuals pursuing international expansion. Many members come from universities. We help clients understand international developments, examine expansion questions and connect with relevant resources and potential partners.

Our current work includes:

- **Monitoring developments:** following public information and examining events, changes and possible implications.
- **Global expansion and international affairs:** source-based analysis of market entry, geopolitics, sanctions and export controls.
- **Products and tools:** applying AI agents to research and business workflows, including SaaS, mini apps and automation, and exploring how research is delivered and used.

This account shares open-source work I take part in, alongside its team context. Reusable tools are published separately; customer materials, private records, internal deployments and non-public knowledge stay outside public repositories.

## Work & collaboration / 工作与合作

**求职方向：**研究与信息分析工具、AI 应用与产品落地，以及相关的产品研究和项目协作。欢迎联系我讨论岗位，也欢迎分享适合这些经历的机会。

**合作事项：**公开信息与国区研究工具、Agent 读取与研究流程、可复用组件，以及已有开源项目的修复和使用验证。GKN 的出海咨询与研究合作也可以通过此邮箱联系，我会按具体事项与团队沟通。

**邮箱：[workstonedai@gmail.com](mailto:workstonedai@gmail.com)**。来信可以简要说明岗位或项目、希望我参与的部分，以及相关链接。

**Job interests:** research and information tools, AI applications and product delivery, and related product research or project collaboration. I welcome conversations about relevant roles and opportunities.

**Collaboration:** public-information and country-research tools, agent reading and research workflows, reusable components, and fixes or usage verification for open-source projects. You can also contact me about GKN's international-expansion advisory and research work; I will coordinate with the team as appropriate.

**Email: [workstonedai@gmail.com](mailto:workstonedai@gmail.com)**. A short description of the role or project, the work you have in mind and relevant links is enough to start.

工具问题请在对应仓库提交 Issue，附版本、复现步骤及公开或虚构数据的最小示例；私人资料请通过合适的私下渠道沟通。 / For tool issues, use the relevant repository with a version, reproduction steps and a minimal example using public or fictional data. Keep private material out of public issues.
