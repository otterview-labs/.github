# Otterview Labs

Computer vision & intelligent hardware · 计算机视觉与智能硬件

我们研发视觉检索、视频事件复判与智能硬件，也维护 AI 编程任务管理和数据查询工具。这里可以找到公开代码、安装入口和使用文档。

## 公开项目

### [agentBridge · 办公小镇](https://github.com/otterview-labs/agentBridge)

离开电脑后，在手机上查看任务输出、翻阅记录，接着原来的 Codex、Claude Code 会话回复。多台开发机器各有自己的像素办公室，任务以员工卡片展示。

- 通过 SSH 连接 Mac / Linux 电脑，查看多台机器的任务和待回复状态。
- 让管家查进展、找需要输入的任务，准备回复草稿，由你确认发送。

提供中文与英文安卓版。基础会话操作从连接电脑开始；管家聊天与语音需要配置模型服务。

[下载安卓版](https://github.com/otterview-labs/agentBridge/releases/latest) · [首次使用](https://github.com/otterview-labs/agentBridge/blob/main/docs/getting-started.zh.md) · [使用文档](https://github.com/otterview-labs/agentBridge/blob/main/docs/android-app.md) · [问题反馈](https://github.com/otterview-labs/agentBridge/issues)

### [SightIndex](https://github.com/otterview-labs/SightIndex)

把本地图片、视频和摄像头流接入同一套视觉索引。查看检测出的人员裁剪图，按描述或已解析属性检索候选画面，再回到原始素材核对。

- FastAPI 接口与 Vue 控制台，支持素材管理、人员裁剪和检索结果查看。
- 默认 SQLite + HOG 可体验图片上传与处理；属性解析、语义检索和跨摄像头候选检索需配置相应模型与索引。

实验性参考实现，检索结果需人工复核。首次体验指南包含响应对照和空结果排查。

[首次体验](https://github.com/otterview-labs/SightIndex/blob/main/docs/first-run.zh-CN.md) · [中文文档](https://github.com/otterview-labs/SightIndex/blob/main/README.zh-CN.md) · [English](https://github.com/otterview-labs/SightIndex/blob/main/README.md) · [问题反馈](https://github.com/otterview-labs/SightIndex/issues)

### [ChatBI](https://github.com/otterview-labs/chatbi)

用自然语言提出数据问题，查看生成的 SQL、查询结果与图表，再把图表放到 Dashboard。适合验证从提问到结果展示的完整流程。

- 保留 SQL 和表格，便于核对查询是否符合问题。
- 提供图表展示与 Dashboard，使用 FastAPI 和 Vue。

项目处于原型阶段，默认使用规则模拟模式。首次体验使用显式生成的模拟数据；真实模型和外部数据源需另行配置。

[首次体验](https://github.com/otterview-labs/chatbi/blob/main/projects/chatbi-smart-ask/docs/first-query.md) · [项目说明](https://github.com/otterview-labs/chatbi/blob/main/README.md) · [English](https://github.com/otterview-labs/chatbi/blob/main/README.en.md) · [问题反馈](https://github.com/otterview-labs/chatbi/issues)

## 产品研发

| 方向 | 当前工作 |
| --- | --- |
| 计算机视觉 | 人员与车辆检测、视频事件复判、视觉检索，以及正在研发的 SOP 视觉巡检。 |
| 智能硬件 | aibox、圆屏语音设备与消防机械手，涉及嵌入式固件、模型推理和设备控制。 |

模型训练平台和 WhaleStack 支持数据管理、模型训练及现场部署。具体研发进展见[研发资料](https://github.com/otterview-labs/.github/blob/main/profile/TEAM.md)，公开代码与安装包以各项目仓库为准。

## 参与项目

试用后可以在对应仓库提交 Issue，附上版本、复现步骤和必要日志。文档补充与代码改进欢迎提交 Pull Request，较大的改动建议先讨论。

首次体验、配置条件与许可证信息汇总在[项目索引](https://github.com/otterview-labs/.github/blob/main/profile/PROJECTS.md)。
