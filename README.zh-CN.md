![LuvElixir · 为真实工作构建 AI 产品](.readme-assets/hero.zh-CN.png)

<p align="center"><a href="README.md">English</a> · <strong>简体中文</strong></p>
<p align="center"><a href="https://luckyloading.com/">Luckyloading</a> · <a href="#正在做的产品">产品</a> · <a href="#可以直接看代码的项目">公开代码</a></p>

# 你好，我是 Archie

我在 [Luckyloading](https://luckyloading.com/) 做 AI 产品，主要做团队协作和视频创作工具。这里也放了一些给 Agent 用的开发工具，源码可以直接看。

SameDesk 处理团队里的任务分工和审阅，Cutline 把脚本与素材做成能在剪映里继续修改的工程。围绕这些工作，我也在做素材研究和知识管理，方便人和 Agent 查资料、核对依据。

![SameDesk、Cutline.ai 与抱抱米产品矩阵](.readme-assets/workflow.zh-CN.png)

## 正在做的产品

| 产品 | 服务谁 | 帮助完成什么 |
| --- | --- | --- |
| **[SameDesk · 同桌](https://luckyloading.com/products/samedesk/)** | 与 AI 协作的团队 | 整理任务资料，分配工作，让成员与 Agent 协作并审阅结果。 |
| **[Cutline.ai](https://cutlineai.luckyloading.com/)** | 视频创作者与剪辑师 | 把脚本和已有录屏做成粗剪，导出工程后继续在剪映里修改。 |
| **[BaoBaoMi · 抱抱米](https://luckyloading.com/products/baobaomi/)** | 游戏广告创意团队 | 查找游戏广告素材，对比内容与来源，跟踪后续变化。 |

具体开放方式与可用范围见各产品页面。

## 可以直接看代码的项目

### [MindexAI](https://github.com/LuvElixir/MindexAI)
**给 Agent 查资料时，把原文和出处一起交给它。**

Mindex 会保存资料快照，为整理出的结论附上原文证据。有疑问的内容可以审核，需要交给 Agent 的资料则整理成带引用的 Context Pack，通过 REST 或 MCP 读取。

`TypeScript` · `SQLite` · `React` · `MCP`

### [PlayGenCLI](https://github.com/LuvElixir/PlayGenCLI)
**Agent 改完工程，就能启动 Godot 看看结果。**

PlayGenCLI 可以创建场景、修改脚本和配置素材，也能调用 Godot 检查工程，获取运行记录与截图。修改前可以保存文件快照，出问题时恢复。

`Python` · `Godot` · `CLI` · `Agent 工具`

## 技术与实现

这些项目主要使用 TypeScript、Python、React 和 Next.js。视频处理会用到 FFmpeg，PlayGenCLI 面向 Godot，Mindex 则用 SQLite 保存本地知识。

每个仓库里都写了启动方式、实现结构和当前限制。如果你对其中某个方向感兴趣，可以从对应项目的 README 开始看。

产品信息与联系方式见 **[Luckyloading](https://luckyloading.com/)**。
