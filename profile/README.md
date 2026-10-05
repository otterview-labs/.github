<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/otterview-labs/.github/main/profile/banner-dark.svg?v=20261003-2">
  <img src="https://raw.githubusercontent.com/otterview-labs/.github/main/profile/banner.svg?v=20261003-2" alt="Otterview Labs · Computer vision & intelligent hardware" width="100%">
</picture>

[关于我们](#关于我们) · [研发方向](#研发方向) · [公开项目](#公开项目) · [项目索引](https://github.com/otterview-labs/.github/blob/main/profile/PROJECTS.md) · [团队介绍](https://github.com/otterview-labs/.github/blob/main/profile/TEAM.md)

## 关于我们

Otterview Labs 是重庆浩鲸智能团队的技术与开源组织。我们研发视频事件复判、视觉检索与巡检软件，也开发 aibox、语音交互设备和消防机械手。

这里也维护公开项目：[agentBridge](https://github.com/otterview-labs/agentBridge) 用于在手机与电脑上处理 AI 编程任务，[SightIndex](https://github.com/otterview-labs/SightIndex) 用于检索本地图片与视频，[ChatBI](https://github.com/otterview-labs/chatbi) 探索自然语言问数。代码和使用说明都在各自仓库里。

## 研发方向

### 计算机视觉

从图片、视频和摄像头流中检测人员与车辆，检索相关画面，并复核候选事件。视觉检索用于查找原始素材，事件复判结合 CV 初筛与视觉语言模型复核，结果供人工核对。

我们也在研发 SOP 视觉巡检：配置检查规则，采集现场画面，保存检查结果和视频证据。SightIndex 提供视觉索引与检索的开源参考实现。

### 智能硬件

围绕 aibox、圆屏语音设备和消防机械手，开发嵌入式固件、推理软件及设备控制程序。语音设备的研发还包括语音服务和配套的蓝牙交互。

<p>
  <img src="https://raw.githubusercontent.com/otterview-labs/.github/main/profile/assets/edge-box.jpg" alt="aibox 边缘 AI 盒子产品示意图" width="640">
  <br><sub>aibox 产品示意图</sub>
</p>

| 设备 | 用途 |
| --- | --- |
| aibox | 在工厂、园区、门店等现场运行视频分析与模型推理。 |
| 消防机械手 | 通过视觉标定确定按键位置，用机械臂和按压执行器操作消防控制器。 |
| 文旅 IP 徽章 | 随身佩戴的圆屏设备，用于角色语音讲解、景点电子印章与蓝牙交互。 |
| 程序员桌面助手 | 显示 AI 编程任务，在需要输入或确认时提醒用户。 |

## 模型训练与部署

模型训练平台把采集素材、标注、数据版本和训练任务按项目管理。图片可以直接导入，视频可以抽帧采集。AI 标注经人工审核后发布为数据版本，用于目标检测模型训练和视觉语言模型微调。

WhaleStack 为 aibox 提供视频接入、解码、抽帧、模型推理和告警回传。边缘 Agent 与场景包的研发用于组织模型调用和事件处理流程；我们也开展高通平台的模型适配与运行验证。设备选型与模型部署按视频路数、模型和现场环境确定。

<a id="开源项目"></a>

## 公开项目

想先试用，可以从 agentBridge 的安卓版开始。SightIndex 提供本地素材接入与处理流程，ChatBI 提供规则模拟模式的问数体验。版本、文档与授权状态汇总在[项目索引](https://github.com/otterview-labs/.github/blob/main/profile/PROJECTS.md)。

### [agentBridge](https://github.com/otterview-labs/agentBridge)

把多台开发机器上的 AI 编程任务放到手机里，查看输出和记录，接着原来的会话回复。支持 Codex 与 Claude Code；管家可以查找需要回复的任务、准备回复草稿，由用户确认发送。Gemini CLI 目前支持基础进程发现。

[安装与使用](https://github.com/otterview-labs/agentBridge#readme) · [版本发布](https://github.com/otterview-labs/agentBridge/releases) · [问题反馈](https://github.com/otterview-labs/agentBridge/issues)

### [SightIndex](https://github.com/otterview-labs/SightIndex)

为本地图片、视频和摄像头流建立可检索的视觉索引，找到相关内容后查看原始素材。提供人员检测、视觉与属性检索，以及 FastAPI 接口和 Vue 控制台。项目是实验性参考实现，检索结果需人工复核。

[首次体验](https://github.com/otterview-labs/SightIndex/blob/main/docs/first-run.zh-CN.md) · [中文文档](https://github.com/otterview-labs/SightIndex/blob/main/README.zh-CN.md) · [问题反馈](https://github.com/otterview-labs/SightIndex/issues)

### [ChatBI](https://github.com/otterview-labs/chatbi)

用自然语言提出数据问题，查看 SQL、表格和图表，再把图表放到 Dashboard。项目处于原型阶段，默认使用规则模拟模式，真实模型需另行配置。

[首次体验](https://github.com/otterview-labs/chatbi/blob/main/projects/chatbi-smart-ask/docs/first-query.md) · [项目说明](https://github.com/otterview-labs/chatbi#readme) · [English](https://github.com/otterview-labs/chatbi/blob/main/README.en.md) · [问题反馈](https://github.com/otterview-labs/chatbi/issues)

## 交流与贡献

欢迎试用项目、反馈问题，也欢迎补充文档和提交代码。使用问题请在对应仓库提交 Issue，附上运行环境、复现步骤与必要日志；较大的代码改动建议先讨论，再提交 Pull Request。

agentBridge 使用 Apache-2.0。SightIndex 与 ChatBI 尚未明确覆盖整个项目的许可证，具体授权状态、部署条件和功能范围见仓库文档。

[团队介绍](https://github.com/otterview-labs/.github/blob/main/profile/TEAM.md) · [Labs 网站](https://otterview-labs.github.io/)
