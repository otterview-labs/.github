<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/otterview-labs/.github/main/profile/banner-dark.svg?v=20261003-2">
  <img src="https://raw.githubusercontent.com/otterview-labs/.github/main/profile/banner.svg?v=20261003-2" alt="Otterview Labs · Computer vision & intelligent hardware" width="100%">
</picture>

[关于我们](#关于我们) · [研发方向](#研发方向) · [开源项目](#开源项目) · [团队介绍](https://github.com/otterview-labs/.github/blob/main/profile/TEAM.md)

## 关于我们

Otterview Labs 是重庆浩鲸智能团队的技术与开源组织。我们研发计算机视觉软件和智能硬件，包括视频事件复判、模型训练平台和 aibox 边缘设备。

这里也有可以自行部署的开源工具：[agentBridge](https://github.com/otterview-labs/agentBridge) 用于在手机与电脑上处理 AI 编程任务，[SightIndex](https://github.com/otterview-labs/SightIndex) 用于检索本地图片与视频，[ChatBI](https://github.com/otterview-labs/chatbi) 探索自然语言问数。代码和安装说明都在各自仓库里。

## 研发方向

### 计算机视觉

从图片、视频和摄像头流中检测人员与车辆，检索相关画面，并复核候选事件。

事件复判结合 CV 初筛与视觉语言模型复核，检查候选事件是否成立，结果供人工核对。SightIndex 提供视觉索引与检索的开源参考实现。

### 智能硬件

研发边缘 AI 设备、语音交互终端和专用控制设备。设备运行所需的推理软件、语音交互和控制逻辑也由团队开发。

<p>
  <img src="https://raw.githubusercontent.com/otterview-labs/.github/main/profile/assets/edge-box.jpg" alt="aibox 边缘 AI 盒子产品示意图" width="640">
  <br><sub>aibox 产品示意图</sub>
</p>

| 设备 | 用途 |
| --- | --- |
| aibox | 在工厂、园区、门店等现场运行视频分析与模型推理。 |
| 消防机械手 | 通过视觉标定确定按键位置，用机械臂和按压执行器操作消防控制器。 |
| 文旅 IP 徽章 | 随身佩戴的圆屏设备，提供角色语音讲解和景点电子印章。 |
| 程序员桌面助手 | 显示 AI 编程任务，在需要输入或确认时提醒用户。 |

## 模型训练与部署

模型训练平台把素材、标注、数据版本和训练任务按项目管理。AI 标注经人工审核后发布为数据版本，用于目标检测模型训练和视觉语言模型微调。

WhaleStack 为 aibox 提供视频接入、解码、抽帧、模型推理和告警回传。设备选型与模型部署按视频路数、模型和现场环境确定。

## 开源项目

### [agentBridge](https://github.com/otterview-labs/agentBridge)

连接自己的开发机器，在手机上查看 AI 编程任务的进度，接收待确认提醒并回复。支持 Codex、Claude Code 和 Gemini CLI 会话，提供 Android 客户端与本地管理工具。

[安装与使用](https://github.com/otterview-labs/agentBridge#readme) · [版本发布](https://github.com/otterview-labs/agentBridge/releases) · [问题反馈](https://github.com/otterview-labs/agentBridge/issues)

### [SightIndex](https://github.com/otterview-labs/SightIndex)

为本地图片、视频和摄像头流建立可检索的视觉索引，找到相关内容后查看原始素材。提供人员检测、视觉与属性检索，以及 FastAPI 接口和 Vue 控制台。项目是实验性参考实现，检索结果需人工复核。

[安装与使用](https://github.com/otterview-labs/SightIndex#readme) · [中文文档](https://github.com/otterview-labs/SightIndex/blob/main/README.zh-CN.md) · [问题反馈](https://github.com/otterview-labs/SightIndex/issues)

### [ChatBI](https://github.com/otterview-labs/chatbi)

用自然语言提出数据问题，尝试转换为 SQL 查询，返回图表和报告。项目处于原型阶段。

[项目说明](https://github.com/otterview-labs/chatbi#readme) · [问题反馈](https://github.com/otterview-labs/chatbi/issues)

## 交流与贡献

欢迎试用项目、反馈问题，也欢迎补充文档和提交代码。使用问题请在对应仓库提交 Issue，附上运行环境、复现步骤与必要日志；较大的代码改动建议先讨论，再提交 Pull Request。

各项目的许可证、部署条件和功能范围见仓库文档。

[团队介绍](https://github.com/otterview-labs/.github/blob/main/profile/TEAM.md) · [Labs 网站](https://otterview-labs.github.io/)
