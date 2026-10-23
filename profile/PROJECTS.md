# Otterview Labs project index

English · [中文](PROJECTS.zh-CN.md)

[Organization](https://github.com/otterview-labs) · [Website](https://otterview-labs.github.io/) · [Team notes](TEAM.md)

## Public repositories

| Project | Who it is for | Try it | Status and license |
| --- | --- | --- | --- |
| [agentBridge](https://github.com/otterview-labs/agentBridge) | Developers who want to follow and reply to Codex and Claude Code tasks from a phone | [Android release](https://github.com/otterview-labs/agentBridge/releases/latest) · [Get started](https://github.com/otterview-labs/agentBridge/blob/main/docs/getting-started.en.md) | English and Chinese Android app. Butler queries and voice require configured services; autonomous task management remains planned. Apache-2.0. |
| [SightIndex](https://github.com/otterview-labs/SightIndex) | Developers exploring local image, video and camera-stream retrieval | [First run](https://github.com/otterview-labs/SightIndex/blob/main/docs/first-run.md) · [README](https://github.com/otterview-labs/SightIndex/blob/main/README.md) | SQLite and HOG support a basic image upload and processing flow. Attribute parsing, semantic search and ReID need additional configuration. Experimental; candidate results need human review. Original code: Apache-2.0. Bundled materials, including SapiensID, retain separate terms; see [license scope](https://github.com/otterview-labs/SightIndex/blob/main/LICENSE_SCOPE.md). |
| [DocuGen](https://github.com/otterview-labs/DocuGen) | Individuals and teams filling Word templates or writing documents from source material | [Setup and usage](https://github.com/otterview-labs/DocuGen/blob/main/README.en.md) | Incorporates the former Quill workspace for source management, retrieval, template filling and document generation. AI features need a model service. One shared workspace, without separate user permissions. Apache-2.0, with upstream attribution and provenance retained. |
| [.github](https://github.com/otterview-labs/.github) | Readers looking for team background and research directions | [Team notes](TEAM.md) | Organization profile, project index and presentation assets. |

Setup requirements vary with model services, devices and runtime environments. Check the current project documentation before trying a release. Evaluate performance on your own data and review candidate search results.

## Product development

Our main work is AI vision software for model training and deployment. The training platform manages media, annotations, dataset versions, training jobs and model artifacts. aibox runs deployed models and video inference, alongside work on edge agents, scene packages and model adaptation.

Round-screen voice devices and a fire-control manipulator are device application research projects, with prototype, firmware and control integration work. We do not manufacture edge computing hardware.

These descriptions do not imply that product source code or installation packages are public. Robotics and embodied AI are longer-term plans.

## Issues and contributions

Use the relevant repository's Issues and include the version, environment, reproduction steps and configured model services. Discuss larger changes first. Reuse and redistribution follow the licenses of each project and its third-party components.
