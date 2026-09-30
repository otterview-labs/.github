<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/otterview-labs/.github/main/profile/banner-dark.svg">
  <img src="https://raw.githubusercontent.com/otterview-labs/.github/main/profile/banner.svg" alt="Otterview Labs · 浩鲸智能的技术与开源" width="100%">
</picture>

<p align="center">
  <a href="#产品方向">产品方向</a> &nbsp; / &nbsp;
  <a href="#开源项目">开源项目</a> &nbsp; / &nbsp;
  <a href="https://github.com/otterview-labs/.github/blob/main/profile/TEAM.md">团队介绍</a> &nbsp; / &nbsp;
  <a href="#交流与贡献">交流与贡献</a>
</p>

## 关于 Otterview Labs

**Otterview Labs 是重庆浩鲸智能团队的技术与开源组织。**

我们做模型训练平台、边缘 AI 设备，也开发文旅 AI 玩具和消防机械手。软件、模型和硬件一起做：训练出来的模型要能在设备上运行，设备要能接入现场的视频和业务系统。

在 GitHub，我们分享视觉检索和 AI 开发工具的代码、部署方法与使用文档。

## 产品方向

<table>
<tr>
<td width="50%" valign="top">
<img src="https://raw.githubusercontent.com/otterview-labs/.github/main/profile/assets/training-platform.jpg" alt="AI 自训练平台实际界面" width="100%">

### 01 / AI 自训练平台

从样本采集、标注到训练、评估和模型转换，在一个平台里完成。提供私有化软件和训练一体机，支持视觉模型与多模态大模型。

<sub>实际产品界面</sub>
</td>
<td width="50%" valign="top">
<img src="https://raw.githubusercontent.com/otterview-labs/.github/main/profile/assets/edge-box.jpg" alt="WhaleBox 边缘 AI 盒子示意图" width="100%">

### 02 / 边端推理

WhaleBox 边缘 AI 盒子与 WhaleStack 软件栈，负责视频接入、模型推理和告警回传。面向 NVIDIA、高通、x86 GPU 与国产平台开展适配。

<sub>产品示意图</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<img src="https://raw.githubusercontent.com/otterview-labs/.github/main/profile/assets/ai-toy.jpg" alt="文旅 IP 圆屏徽章概念演示" width="100%">

### 03 / AI 玩具

文旅 IP 徽章可以随身带，集电子印章、听角色讲解；程序员桌面助手用来显示 AI 编程任务、接收提醒和确认操作。两类设备目前处于样机阶段。

<sub>文旅产品概念演示截图</sub>
</td>
<td width="50%" valign="top">
<img src="https://raw.githubusercontent.com/otterview-labs/.github/main/profile/assets/fire-manipulator.jpg" alt="消防机械手操作火灾报警控制器的效果图" width="100%">

### 04 / 消防机械手

用机械臂和按压执行器操作火灾报警控制器面板上的按键，通过视觉标定确定位置。已制作样机，按现有面板进行适配。

<sub>根据样机实拍重绘的效果图</sub>
</td>
</tr>
</table>

## 开源项目

<table>
<tr>
<td width="50%" valign="top">

### [agentBridge](https://github.com/otterview-labs/agentBridge)

**在手机上查看和处理 AI 编程任务。**

连接自己的开发机器，查看 Codex、Claude Code、Gemini CLI 会话的进度，接收待确认提醒并回复。提供 Android 客户端，以及本地会话管理工具。

[项目说明](https://github.com/otterview-labs/agentBridge#readme) · [版本发布](https://github.com/otterview-labs/agentBridge/releases)

</td>
<td width="50%" valign="top">

### [SightIndex](https://github.com/otterview-labs/SightIndex)

**为图片、视频和摄像头流建立可检索的索引。**

支持媒体接入、人员检测、视觉和属性检索，提供 FastAPI 接口与 Vue 控制台。项目目前是实验性参考实现，检索结果供人工复核。

[项目说明](https://github.com/otterview-labs/SightIndex#readme) · [中文文档](https://github.com/otterview-labs/SightIndex/blob/main/README.zh-CN.md)

</td>
</tr>
</table>

另外，我们也维护 [ChatBI](https://github.com/otterview-labs/chatbi)：一个自然语言问数原型，尝试把问题转换为 SQL，返回图表和报告。

## 交流与贡献

使用中遇到问题，请在对应仓库提交 Issue，附上运行环境、复现步骤和必要日志。文档修正和代码改进可以直接提交 Pull Request；较大的改动建议先讨论。

各项目的许可证、部署条件和当前限制见仓库文档。产品合作与团队方向可先查看[团队介绍](https://github.com/otterview-labs/.github/blob/main/profile/TEAM.md)，或通过对应项目的 Issue 交流。

---

<p align="center"><sub>Otterview Labs · 重庆浩鲸智能</sub></p>
