# Otterview Labs 项目索引

[组织主页](https://github.com/otterview-labs) · [Labs 介绍页](https://otterview-labs.github.io/zh/) · [团队介绍](TEAM.md)

## 公开仓库

| 项目 | 适合谁 | 第一次体验 | 当前状态与授权 |
| --- | --- | --- | --- |
| [agentBridge · 办公小镇](https://github.com/otterview-labs/agentBridge) | 希望在手机上查看和回复 Codex、Claude Code 任务的开发者 | [下载安卓版](https://github.com/otterview-labs/agentBridge/releases/latest)，按[使用说明](https://github.com/otterview-labs/agentBridge/blob/main/docs/android-app.md)连接自己的开发机器 | 提供中英文安卓版；管家查询与语音需配置服务，自主任务管理仍在计划中。Apache-2.0。 |
| [SightIndex](https://github.com/otterview-labs/SightIndex) | 研究本地图片、视频和摄像头流检索的开发者 | [上传、处理与结果核对](https://github.com/otterview-labs/SightIndex/blob/main/docs/first-run.zh-CN.md) · [常见问题](https://github.com/otterview-labs/SightIndex/blob/main/docs/first-run.zh-CN.md#常见问题) · [English](https://github.com/otterview-labs/SightIndex/blob/main/docs/first-run.md) | 默认 SQLite + HOG 可体验图片接入与处理；属性解析、语义检索和 ReID 需额外配置。实验性参考实现，候选结果需人工核验；尚无覆盖整个项目的许可证，模型与第三方组件另有授权说明。 |
| [ChatBI](https://github.com/otterview-labs/chatbi) | 验证自然语言问数、SQL 和图表流程的开发者 | [规则模拟问数体验](https://github.com/otterview-labs/chatbi/blob/main/projects/chatbi-smart-ask/docs/first-query.md) · [English README](https://github.com/otterview-labs/chatbi/blob/main/README.en.md) | 原型；示例数据需显式生成，真实模型和外部数据源需配置。尚无覆盖整个项目的许可证。 |
| [.github](https://github.com/otterview-labs/.github) | 了解团队和研发方向的读者 | [团队介绍](TEAM.md) | 组织介绍、项目索引与展示素材，不是可安装的软件。 |

模型服务、设备与运行环境不同，体验条件也会不同。请先查看各项目的当前文档；不要把模拟数据或候选检索结果当成生产效果。

## 产品研发

团队当前围绕计算机视觉与智能硬件研发，包括视频事件复判、SOP 视觉巡检、aibox、圆屏语音交互设备和消防机械手。模型训练平台、WhaleStack、边缘 Agent 与模型适配支持这些产品的研发。

这些内容的团队介绍不表示代码或安装包已公开。机器人与具身智能为后续计划。

## 问题与贡献

使用问题提交到对应项目的 Issues，说明版本、运行环境、复现步骤和启用的模型服务。较大的改动先讨论。代码复用与再分发以各项目及第三方组件的授权声明为准。
