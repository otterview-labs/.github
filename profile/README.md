<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/otterview-labs/.github/main/profile/banner-dark.svg?v=20261003-2">
  <img src="https://raw.githubusercontent.com/otterview-labs/.github/main/profile/banner.svg?v=20261003-2" alt="Otterview Labs · Computer vision & intelligent hardware" width="100%">
</picture>

[关于我们](#关于我们) · [研发方向](#研发方向) · [开源项目](#开源项目) · [团队介绍](https://github.com/otterview-labs/.github/blob/main/profile/TEAM.md)

## 关于我们

Otterview Labs 是重庆浩鲸智能团队的技术与开源组织。我们做计算机视觉和智能硬件研发，在这里分享项目代码、部署方法和使用文档。

## 研发方向

### 计算机视觉

视觉研发包括目标检测、人员与车辆识别、视频事件复判和内容检索。

事件复判先用 CV 筛选候选事件，再由视觉语言模型判断事件是否成立，结果供人工核对。视觉检索用于从图片、视频和摄像头流中查找相关内容，开源项目 SightIndex 提供索引与检索的参考实现。

### 智能硬件

研发边缘 AI 设备、语音交互终端和专用控制设备。aibox 用于现场视频分析，交互设备和消防机械手各自承担讲解、提醒或面板操作。

<p>
  <img src="https://raw.githubusercontent.com/otterview-labs/.github/main/profile/assets/edge-box.jpg" alt="aibox 边缘 AI 盒子产品示意图" width="640">
  <br><sub>aibox 产品示意图</sub>
</p>

| 设备 | 用途 |
| --- | --- |
| 消防机械手 | 通过视觉标定确定按键位置，用机械臂和按压执行器操作消防控制器。 |
| 文旅 IP 徽章 | 随身佩戴的圆屏设备，提供角色语音讲解和景点电子印章。 |
| 程序员桌面助手 | 显示 AI 编程任务，在需要输入或确认时提醒用户。 |

## 模型训练与部署

模型训练平台为视觉和设备研发管理素材、标注、数据版本与训练任务。AI 标注经人工审核后发布，支持目标检测模型训练和视觉语言模型微调。

WhaleStack 是 aibox 的配套推理软件，处理视频接入、解码、抽帧、模型推理和告警回传。设备选型与模型部署按视频路数、模型和现场环境确定。

## 开源项目

### [agentBridge](https://github.com/otterview-labs/agentBridge)

查看和管理 Codex、Claude Code、Gemini CLI 会话。连接自己的开发机器，查看任务进度、接收待确认提醒并回复，提供 Android 客户端和本地管理工具。

[安装与使用](https://github.com/otterview-labs/agentBridge#readme) · [版本发布](https://github.com/otterview-labs/agentBridge/releases) · [问题反馈](https://github.com/otterview-labs/agentBridge/issues)

### [SightIndex](https://github.com/otterview-labs/SightIndex)

为图片、视频和摄像头流建立视觉索引，提供人员检测、视觉和属性检索，以及 FastAPI 接口与 Vue 控制台。项目是实验性参考实现，检索结果需要人工复核。

[安装与使用](https://github.com/otterview-labs/SightIndex#readme) · [中文文档](https://github.com/otterview-labs/SightIndex/blob/main/README.zh-CN.md) · [问题反馈](https://github.com/otterview-labs/SightIndex/issues)

### [ChatBI](https://github.com/otterview-labs/chatbi)

自然语言问数原型：把问题转换为 SQL，返回图表和报告。

[项目说明](https://github.com/otterview-labs/chatbi#readme) · [问题反馈](https://github.com/otterview-labs/chatbi/issues)

## 交流与贡献

使用问题请到对应仓库提交 Issue，附上运行环境、复现步骤和必要日志。文档修正和代码改进可以提交 Pull Request，较大的改动建议先讨论。

各项目的许可证、部署条件和功能范围见仓库文档。

[团队介绍](https://github.com/otterview-labs/.github/blob/main/profile/TEAM.md) · [Labs 网站](https://otterview-labs.github.io/)
