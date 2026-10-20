# Otterview Labs 项目索引

[English](PROJECTS.md) · 中文

[组织主页](https://github.com/otterview-labs) · [Labs 介绍页](https://otterview-labs.github.io/zh/) · [团队介绍](TEAM.zh-CN.md)

## 公开仓库

| 项目 | 适合谁 | 第一次体验 | 当前状态与授权 |
| --- | --- | --- | --- |
| [agentBridge · 办公小镇](https://github.com/otterview-labs/agentBridge) | 希望在手机上查看和回复 Codex、Claude Code 任务的开发者 | [下载安卓版](https://github.com/otterview-labs/agentBridge/releases/latest)，按[使用说明](https://github.com/otterview-labs/agentBridge/blob/main/docs/android-app.md)连接自己的开发机器 | 提供中英文安卓版；管家查询与语音需配置服务，自主任务管理仍在计划中。Apache-2.0。 |
| [SightIndex](https://github.com/otterview-labs/SightIndex) | 研究本地图片、视频和摄像头流检索的开发者 | [上传、处理与结果核对](https://github.com/otterview-labs/SightIndex/blob/main/docs/first-run.zh-CN.md) · [常见问题](https://github.com/otterview-labs/SightIndex/blob/main/docs/first-run.zh-CN.md#常见问题) · [English](https://github.com/otterview-labs/SightIndex/blob/main/docs/first-run.md) | 默认 SQLite + HOG 可体验图片接入与处理；属性解析、语义检索和 ReID 需额外配置。实验性参考实现，候选结果需人工核验。原创代码采用 Apache-2.0；内附 SapiensID 等材料保留单独授权，见[适用范围](https://github.com/otterview-labs/SightIndex/blob/main/LICENSE_SCOPE.md)。 |
| [DocuGen](https://github.com/otterview-labs/DocuGen) | 需要基于资料填写 Word 模板或生成文档的个人和团队 | [安装与使用](https://github.com/otterview-labs/DocuGen#readme) · [English](https://github.com/otterview-labs/DocuGen/blob/main/README.en.md) | 整合原 Quill 工作台，支持资料管理、检索、模板填写和文档生成。AI 功能需配置模型；当前为共享工作区，没有独立用户权限。Apache-2.0，保留上游署名与来源记录。 |
| [.github](https://github.com/otterview-labs/.github) | 了解团队和研发方向的读者 | [团队介绍](TEAM.zh-CN.md) | 组织介绍、项目索引与展示素材，不是可安装的软件。 |

模型服务、设备与运行环境不同，体验条件也会不同。请先查看各项目的当前文档；不要把模拟数据或候选检索结果当成生产效果。

## 产品研发

团队主要开发 AI 视觉软件，主线是模型训练与部署应用。训练平台管理素材、标注、数据版本、训练任务和模型产物；aibox 是现场模型部署与视频推理软件，配套开展边缘 Agent、场景包与模型适配研发。

圆屏语音交互设备和消防机械手属于设备应用探索，已积累样机、固件和控制集成经验。团队不生产边缘计算设备。

这些内容的团队介绍不表示代码或安装包已公开。机器人与具身智能为后续计划。

## 问题与贡献

使用问题提交到对应项目的 Issues，说明版本、运行环境、复现步骤和启用的模型服务。较大的改动先讨论。代码复用与再分发以各项目及第三方组件的授权声明为准。
