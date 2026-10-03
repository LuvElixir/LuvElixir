![Archie · Luckyloading 创始人](.readme-assets/hero.zh-CN.png)

<p align="center"><a href="README.md">English</a> · <strong>简体中文</strong></p>
<p align="center"><a href="https://luckyloading.com/">Luckyloading</a> · <a href="#产品">产品</a> · <a href="#在研项目">在研项目</a> · <a href="#公开项目">公开代码</a></p>

# Archie · Luckyloading 创始人

**AI 应用创业者。**

我创办了 [Luckyloading](https://luckyloading.com/)，和团队一起开发 AI 应用。我们的工作从产品设计、工程实现延伸到商业化，围绕不同场景中的需求，探索新的产品机会。

目前的产品与研究涉及团队协作、内容创作、知识服务和市场研究。这里展示其中的部分成果，也会随着新产品的推进持续更新。

![Luckyloading 部分产品](.readme-assets/workflow.zh-CN.png)

## 产品

| 产品 | 面向用户 | 产品方向 |
| --- | --- | --- |
| **[SameDesk · 同桌](https://luckyloading.com/products/samedesk/)** | 与 AI 协作的团队 | 在共享工作台中组织任务与资料，协调成员和 Agent 的分工、执行与审阅。 |
| **[Cutline.ai](https://cutlineai.luckyloading.com/)** | 视频创作者与剪辑师 | 将脚本与已有素材组织为可编辑时间线，支持剪映工程导出。 |
| **[BaoBaoMi · 抱抱米](https://luckyloading.com/products/baobaomi/)** | 游戏广告创意团队 | 监测游戏广告数据，检索、收藏与比较素材，为创意研究提供参考。 |

各产品的开放方式与当前可用功能见产品网站。

## 在研项目

**Pumio · 游戏视频创作 Agent**  
正在开发结合对话式编辑与时间线操作的创作工作台，让用户和 Agent 共同修改同一个视频工程。

**Elixir Capital · 个人市场研究**  
探索 AI 辅助的信息研究与市场观察，结合历史实验和决策记录验证研究方法。当前为个人研究项目。

## 公开项目

### [MindexAI](https://github.com/LuvElixir/mindex)
**面向 Agent 的可追溯知识库。**

Mindex 保存来源快照，将研究结论与原文证据关联，并记录审核状态。下游 Agent 可通过 REST 或 MCP 获取带引用的 Context Pack，在任务中使用这些知识。

`TypeScript` · `SQLite` · `React` · `MCP`

### [PlayGenCLI](https://github.com/LuvElixir/playgen-cli)
**面向 Agent 的 Godot 开发工具。**

PlayGenCLI 将场景编辑、工程校验与运行观察接入同一命令行。Agent 可根据 Godot 返回的日志和截图继续修改，并通过文件快照保留可恢复的版本。

`Python` · `Godot` · `CLI` · `Agent 工具`

## 工程实现

这些项目主要使用 TypeScript 与 Python，界面基于 React 和 Next.js。视频处理使用 FFmpeg，游戏工具通过 Godot 获取运行反馈，知识服务使用 SQLite 存储本地数据。

各仓库提供运行步骤、架构说明与当前开发范围。产品介绍与联系入口见 **[Luckyloading](https://luckyloading.com/)**。
