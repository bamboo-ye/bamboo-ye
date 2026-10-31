<h1 align="center">Hi, I'm 叶晓艺 👋</h1>

<p align="center"><strong>AI 全栈开发 · Agent 工程 · 从想法到可交付的产品</strong></p>

<p align="center">
  <a href="https://bamboo-ye.github.io/cv-ye/">个人主页 / 简历</a> ·
  <a href="https://github.com/bamboo-ye?tab=repositories">全部仓库</a> ·
  <a href="mailto:13003139690@163.com">联系我</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Next.js-171717?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/LangGraph-355E4B?style=flat-square" alt="LangGraph" />
</p>

## 关于我

我关注 **Agent 系统与全栈产品开发**，喜欢把模型能力接到真实业务里，让任务能执行、结果能追溯、产物能继续编辑。

- 🎓 香港城市大学人工智能（Generative AI）硕士在读；云南大学软件工程本科、硕士背景。
- 🛠️ 主要使用 **Go + Python + TypeScript**，覆盖前端交互、业务 API、Agent 编排、数据存储与部署。
- 🔍 持续实践上下文工程、Agentic RAG、多 Agent 协作、工具调用与人工确认。
- 🌱 当前重点投入个人 AI 工作空间，以及连接日常记录与可复现研究的 AI 应用。
- 💬 欢迎交流 **AI 全栈开发、Agent 工程与相关合作机会**。

## 重点项目

### [伴AI · AI Companion](https://github.com/bamboo-ye/ai-companion)

**一个可自部署的个人 AI 工作空间，把角色陪伴、生活管理与办公创作放进同一段对话。**

从记账、提醒，到多附件阅读、文档处理和可编辑 PPT，关注的不只是生成答案，还包括任务执行、来源核验和后续修改。

- **完整产品链路**：Next.js 负责交互，Go 承载鉴权、业务与任务状态，Python / LangGraph 编排 Agent，独立 Worker 处理文档。
- **复杂任务处理**：大文件分片、覆盖校验、依赖任务规划和有界并行，处理超出单次上下文窗口的材料。
- **可恢复执行**：结合 Checkpoint、任务租约、幂等与版本隔离，保留成功步骤，支持中断后继续。
- **可追溯交付**：统一知识检索、来源与版本核验、人工审批，以及可在对话中续改的演示文稿。

`Go` · `Python` · `LangGraph` · `Next.js` · `PostgreSQL` · `Redis` · `Qdrant` · `Docker`

[查看项目](https://github.com/bamboo-ye/ai-companion) · [中文介绍](https://github.com/bamboo-ye/ai-companion/blob/master/README.zh-CN.md) · [技术与架构](https://github.com/bamboo-ye/ai-companion/blob/master/docs/ENGINEERING.md)

### [伴AI · 健康伙伴](https://github.com/bamboo-ye/healthy-care)

**用图文对话记录院外健康过程，连接个人健康空间与可追溯的科研工作台。**

- **记录与确认**：整理症状、实际用药与恢复过程，支持确认、更正、持续跟进和独立研究授权。
- **科研执行闭环**：冻结队列与输入版本，调用 SciencePal 执行研究任务，取回报告、CSV 与日志，再独立校验结果。
- **可复现研究**：保留合成输入、分析脚本与实验记录；目前的实验基于合成数据，尚无临床有效性结论。

`Go` · `Python` · `LangGraph` · `React` · `PostgreSQL` · `SciencePal` · `Docker Compose`

[查看项目](https://github.com/bamboo-ye/healthy-care) · [项目演示](https://github.com/bamboo-ye/healthy-care/blob/main/docs/demo.md) · [研究设计](https://github.com/bamboo-ye/healthy-care/blob/main/docs/research-design.md)

## 更多仓库

| 仓库 | 做了什么 | 技术与关注点 |
| --- | --- | --- |
| [GoChat · 即时通信与 AI 对话](https://github.com/bamboo-ye/goChat)（私有） | 实时消息、用户在线状态、历史记录、离线消息与 AI 机器人对话；[项目介绍](https://bamboo-ye.github.io/cv-ye/gochat_project.html) | Go、WebSocket、Redis、MySQL、大模型 API；消息路由、在线状态管理与离线投递 |
| [emoji · 表情包生成系统](https://github.com/bamboo-ye/emoji) | 从创建任务、异步图片生成到实时通知的完整链路 | Go、Kafka、Redis、MySQL；Outbox、请求幂等、离线补投与动态降级 |
| [display_pod · CVPR 论文展示舱](https://github.com/bamboo-ye/display_pod) | 论文采集、流处理、检索与实时可视化大屏 | Python、Kafka、Flink、Gin、Vue 3、ECharts；数据去重与 WebSocket 更新 |
| [cv-ye · 个人主页](https://github.com/bamboo-ye/cv-ye) | 简历、项目介绍与研究经历的统一入口 | HTML、CSS、GitHub Pages；[在线访问](https://bamboo-ye.github.io/cv-ye/) |

## 技术栈

| 方向 | 常用技术 |
| --- | --- |
| Agent 与知识工程 | LangGraph、MCP、Skills / Tool Use、Human-in-the-loop、Checkpoint、Agentic RAG、上下文管理 |
| 后端与通信 | Go、Python、Gin、GORM、REST API、gRPC、SSE、WebSocket |
| 前端与交互 | TypeScript、Next.js、React、Vue、ECharts |
| 数据与异步任务 | PostgreSQL、MySQL、Redis、Qdrant、Kafka、MinIO |
| 交付与可观测性 | Docker、CI/CD、OpenTelemetry、Langfuse、Prometheus、Grafana、Loki |

## 我在意的工程问题

- **执行可靠性**：任务失败或进程重启后，如何恢复进度，并避免重复写入？
- **知识可信度**：引用是否对应原始来源，来源更新或权限变化后是否仍然有效？
- **长任务体验**：多附件与长文档如何分片、并行、控制预算，并让用户看到进度？
- **交付可用性**：生成的文件能否检查、导出，并在下一轮对话里继续编辑？

<details>
<summary><strong>研究与其他经历</strong></summary>

除应用开发外，我也做过超图对比协同学习与分子图表征相关研究，探索图结构如何表达复杂关系。

曾获“互联网+”大学生创新创业大赛省级银奖两项、“挑战杯”大学生创业计划竞赛省级银奖，并参与校园技术社团组织工作。

更多背景与项目说明见[在线简历](https://bamboo-ye.github.io/cv-ye/)。

</details>

---

欢迎在[对应仓库](https://github.com/bamboo-ye?tab=repositories)的 Issues 中交流项目问题，或通过[邮件](mailto:13003139690@163.com)联系我。
