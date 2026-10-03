<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/otterview-labs/.github/main/profile/banner-dark.svg?v=20261003-2">
  <img src="https://raw.githubusercontent.com/otterview-labs/.github/main/profile/banner.svg?v=20261003-2" alt="Otterview Labs · Computer vision & intelligent hardware" width="100%">
</picture>

[关于我们](#关于我们) · [研发方向](#研发方向) · [开源项目](#开源项目) · [团队介绍](https://github.com/otterview-labs/.github/blob/main/profile/TEAM.md)

## 关于我们

Otterview Labs 是重庆浩鲸智能团队的技术与开源组织。我们研发视觉软件和智能硬件，在这里分享项目代码、部署方法和使用文档。

## 研发方向

### 视觉软件

研发目标检测、图文数据处理、模型训练与边缘推理软件。

模型训练平台把素材、标注、数据版本、训练任务和模型产物放在同一个项目里。图片可直接导入，视频文件和实时流可以抽帧采集。AI 标注作为候选结果，人工审核后发布数据版本，再用于检测模型训练或视觉语言模型微调。

> 采集素材 → 标注审核 → 发布数据版本 → 模型训练 → 效果评测

WhaleStack 处理视频拉流、解码、抽帧、推理和告警回传，配合 WhaleBox 在现场运行。

### 智能硬件

WhaleBox 是边缘 AI 设备系列。设备选型需要结合视频路数、使用的模型和现场运行环境。

<p>
  <img src="https://raw.githubusercontent.com/otterview-labs/.github/main/profile/assets/edge-box.jpg" alt="WhaleBox 边缘 AI 盒子产品示意图" width="640">
  <br><sub>WhaleBox 产品示意图</sub>
</p>

| 设备 | 用途 |
| --- | --- |
| 消防机械手 | 操作消防控制器面板上的按键，通过视觉标定确定位置。已完成样机。 |
| 文旅 IP 徽章 | 随身佩戴的圆屏设备，提供角色语音讲解和景点电子印章。处于样机阶段。 |
| 程序员桌面助手 | 显示 AI 编程任务，在需要输入或确认时提醒用户。处于样机阶段。 |

机器人是后续研发方向，当前已有消防机械手的样机工作。

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
