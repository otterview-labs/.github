# Otterview Labs project index

English · [中文](PROJECTS.zh-CN.md)

[Organization](https://github.com/otterview-labs) · [Website](https://otterview-labs.github.io/) · [Team notes](TEAM.md)

## Public repositories

### Visual search and image services

| Project | Who it is for | Try it | Status and license |
| --- | --- | --- | --- |
| [SightIndex](https://github.com/otterview-labs/SightIndex) | Developers exploring local image, video and camera-stream retrieval | [Live demo](http://43.153.213.96/search) · [First run](https://github.com/otterview-labs/SightIndex/blob/main/docs/first-run.md) · [README](https://github.com/otterview-labs/SightIndex/blob/main/README.md) | SQLite and HOG support a basic image upload and processing flow. Attribute parsing, semantic search and ReID need additional configuration. Candidate results need human review. Original code: Apache-2.0. Bundled materials, including SapiensID, retain separate terms; see [license scope](https://github.com/otterview-labs/SightIndex/blob/main/LICENSE_SCOPE.md). |
| [Qwen-Image-2.1-AMD-Service](https://github.com/otterview-labs/Qwen-Image-2.1-AMD-Service) | Developers running Qwen image generation and editing on an AMD GPU | [API guide](https://github.com/otterview-labs/Qwen-Image-2.1-AMD-Service#readme) | The current configuration targets AMD Radeon AI PRO R9700. Apache-2.0. |

### Document tools

| Project | Who it is for | Try it | Status and license |
| --- | --- | --- | --- |
| [DocuGen](https://github.com/otterview-labs/DocuGen) | Individuals and teams filling Word templates or writing documents from source material | [Live demo](https://docugen.otterview.ai/templates?source=builtin) · [Setup and usage](https://github.com/otterview-labs/DocuGen#readme) | Incorporates the former Quill workspace for source management, retrieval, template filling and document generation. AI features need a model service. The standard self-hosted setup uses one shared workspace. Apache-2.0, with upstream attribution and provenance retained. |
| [OtterView Knowledge](https://github.com/otterview-labs/otterview-knowledge) | People who need to find documents, read originals and see summaries | [Setup and usage](https://github.com/otterview-labs/otterview-knowledge#readme) | Standalone deployment with one shared operator account. Apache-2.0. |

### Developer tools

| Project | Who it is for | Try it | Status and license |
| --- | --- | --- | --- |
| [agentBridge](https://github.com/otterview-labs/agentBridge) | Developers who want to follow and reply to Codex and Claude Code tasks from a phone | [Android release](https://github.com/otterview-labs/agentBridge/releases/latest) · [Get started](https://github.com/otterview-labs/agentBridge/blob/main/docs/getting-started.en.md) | English and Chinese Android app. Butler queries and voice require configured services; autonomous task management remains planned. Apache-2.0. |
| [AgentHarbor](https://github.com/otterview-labs/agentharbor) | Developers running coding tasks with separate execution and review on their own computer | [Desktop guide](https://github.com/otterview-labs/agentharbor/blob/main/docs/desktop-alpha.md) · [Releases](https://github.com/otterview-labs/agentharbor/releases) | Desktop alpha. Requires configured Codex and Claude Code CLIs. Platform support and known limitations are documented in the repository. MIT. |

Setup requirements vary with model services, devices and runtime environments. Check the current project documentation before trying a release. Evaluate performance on your own data and review candidate search results.

## Related repositories

- [.github](https://github.com/otterview-labs/.github) holds this organization profile and project index. [otterview-labs.github.io](https://github.com/otterview-labs/otterview-labs.github.io) holds the Labs website and technical articles.

## Product development

Our main work is AI vision software for model training and deployment. The training platform manages media, annotations, dataset versions, training jobs and model artifacts. aibox runs deployed models and video inference, alongside work on edge agents, scene packages and model adaptation.

Round-screen voice devices and fire-control manipulator projects cover firmware, voice interaction and visual-control integration. We do not manufacture edge computing hardware.

These descriptions do not imply that product source code or installation packages are public. Robotics and embodied AI are longer-term plans.

## Issues and contributions

Use the relevant repository's Issues and include the version, environment, reproduction steps and configured model services. Discuss larger changes first. Reuse and redistribution follow the licenses of each project and its third-party components.
