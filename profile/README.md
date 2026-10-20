<p>
  <a href="https://otterview-labs.github.io/zh/">
    <img src="https://raw.githubusercontent.com/otterview-labs/.github/main/profile/assets/otterview-wordmark.jpg" alt="Otterview" width="300" height="100">
  </a>
</p>

# Otterview Labs

专注于 AI 视觉软件，开发模型训练平台与 aibox 部署软件。

[Labs 介绍页](https://otterview-labs.github.io/zh/) · [English](https://otterview-labs.github.io/)

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

### [DocuGen](https://github.com/otterview-labs/DocuGen)

把资料放进知识库，查看原文和检索结果，填写 Word 模板或按章节生成文档。可以先手动填模板；AI 填写和文档写作需要配置模型服务。适合个人或可信团队自部署，目前使用一个共享工作区。

[安装与使用](https://github.com/otterview-labs/DocuGen#readme) · [版本发布](https://github.com/otterview-labs/DocuGen/releases) · [English](https://github.com/otterview-labs/DocuGen/blob/main/README.en.md) · [问题反馈](https://github.com/otterview-labs/DocuGen/issues)

## 参与项目

试用后可以在对应仓库提交 Issue，附上版本、复现步骤和必要日志。文档补充与代码改进欢迎提交 Pull Request，较大的改动建议先讨论。

首次体验、配置条件与许可证信息汇总在[项目索引](https://github.com/otterview-labs/.github/blob/main/profile/PROJECTS.md)。
