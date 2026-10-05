# Workstone · Global Knowledge Network

**Research, global expansion, and practical AI tools.**  
**研究、出海服务与实用 AI 工具。**

[English](#about-me--global-knowledge-network) · [中文](#关于我与-global-knowledge-network) · [Projects / 开源项目](#start-here--从这里开始) · [Contributions / 社区贡献](#open-source-contributions--开源贡献)

## About Me & Global Knowledge Network

I am a team member at **Global Knowledge Network (GKN)**. Drawing on our professional expertise and research backgrounds, we provide advisory and connection services to businesses and individuals pursuing international expansion. Many of our team members come from universities. We bring research into practical business contexts, helping clients understand the international landscape, assess questions around global expansion, and connect with relevant resources and potential partners.

In the AI era, we are integrating AI agents into our research and business workflows to explore new ways of delivering services and building tools. Our current work focuses on:

- **Monitoring and assessing emerging developments:** Using AI to track information, identify emerging issues, and examine their context, evolution, and potential implications.
- **Analyzing global expansion and international affairs:** Conducting in-depth analysis grounded in source evidence on international expansion needs, geopolitical developments, international sanctions, and export controls.
- **Building products and tools:** Developing SaaS platforms, mini apps, and automation tools that make research and analysis more accessible in everyday business workflows.

This account documents our open-source work and contributions to the wider community. We share reusable tools developed through our practice, covering information collection, evidence checking, public data access, task recovery, and report generation. We hope they will also be useful to other researchers, developers, and teams.

## 关于我与 Global Knowledge Network

我是 **Global Knowledge Network（GKN）** 的团队成员。我们依托团队的专业知识与科研背景，面向有出海需求的企业和个人，提供咨询与连接服务。团队成员多来自高校，致力于将研究能力与实际业务需求相结合，帮助客户理解国际环境、分析出海问题，并连接相关资源与合作机会。

在 AI 时代，我们正在将 AI Agent 融入研究与业务流程，探索新的服务方式和工具。当前的尝试主要集中在：

- **热点追踪与研判**：使用 AI 持续追踪信息，识别热点，并分析其背景、变化及潜在影响。
- **出海与国际议题分析**：围绕出海需求、地缘政治热点、跨国制裁和出口管制等议题，开展有来源依据的深度分析。
- **产品与工具开发**：开发 SaaS 平台、小程序和自动化工具，让研究与分析能力更方便地应用于实际业务。

这个账号记录我们在上述方向上的开源实践与社区贡献。我们将实践中具有通用价值的工具整理出来，涉及信息采集、证据校验、公共数据接入、任务恢复和报告生成，希望它们也能帮助其他研究者、开发者和团队开展工作。

## Start here / 从这里开始

Choose a tool by the task you want to complete. Each repository contains its own setup instructions, examples, scope, and license.  
根据你想完成的任务选择工具。各仓库都有自己的安装说明、示例、适用范围和许可证。

| Project / 项目 | What it helps you do / 可以帮你做什么 |
| --- | --- |
| **[Global Knowledge Crawl Pipeline](https://github.com/workstonedai-collab/global-knowledge-crawl-pipeline)** | Collect information from configured web pages and keyword searches, optionally enrich it through your own APIs, and organize it into a configurable information table. / 从指定网页和关键词检索收集信息，可通过自定义 API 进行摘要、研判和标签富化，并按自定义字段整理成信息表。 |
| **[Click-to-CSS](https://github.com/workstonedai-collab/click-to-css)** | Select elements in a local static page, preview CSS changes, save them to allowed stylesheets, and undo edits. Built for static HTML and ordinary CSS with Vite. / 在本地静态页面中点选元素、预览样式调整、保存到允许修改的 CSS 文件并撤销；适用于 Vite 下的静态 HTML 和普通 CSS。 |
| **[AI Evidence Check](https://github.com/workstonedai-collab/ai-evidence-check)** | Compare AI-extracted fields and quotations with supplied source text, produce review reports, and optionally request model-assisted review suggestions. / 将 AI 提取的字段和引用与提供的原文对照，生成复核报告，并可接入模型获取人工复核建议。 |
| [Public Data Connectors](https://github.com/workstonedai-collab/public-data-connectors) | Access World Bank, Eurostat, and GLEIF data through reusable adapters that preserve source context. / 通过可复用的连接器接入世界银行、Eurostat 和 GLEIF 公共数据，并保留来源信息。 |
| [Agent Task Recovery Kit](https://github.com/workstonedai-collab/agent-task-recovery-kit) | Save local checkpoints and resume sequential workflows after interruptions, with explicit retry and idempotency handling. / 保存本地检查点，在中断后恢复顺序任务，并明确处理重试与幂等性。 |
| [Report Export Kit](https://github.com/workstonedai-collab/report-export-kit) | Export structured content, tables, and charts as PDF, DOCX, and Markdown reports. / 将结构化内容、表格和图表导出为 PDF、Word 和 Markdown 报告。 |

### More tools / 更多工具

- [Bilingual News Dedupe](https://github.com/workstonedai-collab/bilingual-news-dedupe) — Deduplication for Chinese and English news workflows. / 中英文资讯流程中的去重工具。
- [Source Rights Gate](https://github.com/workstonedai-collab/source-rights-gate) — Configurable source permissions and collection rules. / 可配置的信息来源权限与采集规则。
- [Human Review Research Agent](https://github.com/workstonedai-collab/human-review-research-agent) — A research-agent example with human review. / 带人工复核的研究智能体示例。
- [Miniapp Project Check](https://github.com/workstonedai-collab/miniapp-project-check) — Local checks for mini-program project setup. / 小程序项目配置的本地检查工具。

## Open-source contributions / 开源贡献

We also contribute fixes and documentation to tools we use. Status below was checked on **2026-10-05**; the linked pull requests contain the latest updates.  
我们也向使用的开源工具提交修复和文档改进。以下状态核对于 **2026-10-05**，最新进展请查看对应 PR。

| Project / 项目 | Contribution / 贡献 | Status / 状态 |
| --- | --- | --- |
| [Kandev](https://github.com/kdlbs/kandev/pull/4082) | Documented E2E setup for a fresh checkout. / 补充从新检出项目开始的端到端测试准备说明。 | **Merged; included in [v0.97.0](https://github.com/kdlbs/kandev/releases/tag/v0.97.0). / 已合并，并进入正式版本。** |
| [Trafilatura](https://github.com/adbar/trafilatura/pull/944) | Linked existing URL-discovery tools from extraction guidance. / 在内容提取说明中补充已有链接发现工具的入口。 | **Merged. / 已合并。** |
| [MarkItDown](https://github.com/microsoft/markitdown/pull/2529#issuecomment-5997199878) | Fixed code-fence handling after list markers, preserving code whitespace. / 修复列表标记后代码围栏的处理，保留代码空白。 | **Patch adopted into the original author's PR branch with authorship preserved; upstream PR awaits merge. / 补丁已被原作者纳入其 PR 分支并保留署名，上游 PR 待合并。** |

## Feedback & collaboration / 反馈与协作

If you try a tool, its repository is the best place to report a problem or suggest an improvement. Include your goal, the tool version, reproduction steps, and a minimal example using public or synthetic data. Contributions and practical usage examples are welcome.  
如果你试用了某个工具，欢迎在对应仓库反馈问题或提出改进建议。请说明使用目标、工具版本、复现步骤，并提供使用公开或合成数据的最小示例。也欢迎提交改进和实际使用案例。
