# Otterview Labs

We build computer vision software and open-source tools in Chongqing, China.

[Company website](https://otterview.ai/?utm_source=github&utm_campaign=org-profile) · [Lutrio training platform](https://otterview.ai/training-platform?utm_source=github&utm_campaign=org-profile) · [Technical articles](https://otterview-labs.github.io/) · [Discuss a project](https://otterview.ai/contact?source=github&utm_campaign=org-profile#evaluation-form)

Lutrio by Otterview brings data preparation, assisted annotation and CV/VLM training workflows into one project. The overseas environment currently provides invited sign-in; complete training execution is not open yet. See the product page for availability and evaluation scope.

## Open-source projects

| Project | What to try | Current scope |
| --- | --- | --- |
| [SightIndex](https://github.com/otterview-labs/SightIndex) | Self-hosted visual indexing for images, videos and camera streams | Experimental reference implementation; optional models require configuration and results need human review |
| [agentBridge](https://github.com/otterview-labs/agentBridge) | View and reply to coding-agent sessions from Android | Requires an accessible development computer; see the downloads, first-run guide and operation video |
| [AgentHarbor](https://github.com/otterview-labs/agentharbor) | Coordinate local coding agents with execution and review | Alpha desktop release; supported tools and platforms are listed in the repository |
| [DocuGen](https://github.com/otterview-labs/DocuGen) | Search source material, fill Word templates and generate documents | Self-hosted workspace; AI features require a configured model service |
| [ChatBI](https://github.com/otterview-labs/chatbi) | Inspect natural-language queries, SQL, tables and charts | Prototype; uses a rule-based demo by default |

For project support, use the corresponding repository's Issues. For product demos or business enquiries, [contact Otterview](https://otterview.ai/contact?source=github&utm_campaign=org-profile#evaluation-form).

## 中文介绍

<p>
  <a href="https://otterview-labs.github.io/">
    <img src="https://raw.githubusercontent.com/otterview-labs/.github/main/profile/assets/otterview-wordmark.jpg" alt="Otterview" width="300" height="100">
  </a>
</p>

# Otterview Labs

We build AI vision software: an agent-guided model training platform and aibox for video analysis and model deployment.

[Website](https://otterview-labs.github.io/) · [中文](https://github.com/otterview-labs/.github/blob/main/profile/README.zh-CN.md)

## Open source

### [agentBridge](https://github.com/otterview-labs/agentBridge)

Continue Codex and Claude Code sessions from your Android phone. Read task output, browse session history and reply to the same conversation. Each connected development machine has a pixel office, with tasks shown as employee cards.

- Connect to Mac and Linux machines over SSH to see progress and tasks awaiting a reply.
- Ask the AI butler to check progress and prepare reply drafts for you to review and send.

Available in English and Chinese. Session access starts with connecting your own computer; butler chat and voice require a model service.

[Download for Android](https://github.com/otterview-labs/agentBridge/releases/latest) · [Get started](https://github.com/otterview-labs/agentBridge/blob/main/docs/getting-started.en.md) · [Issues](https://github.com/otterview-labs/agentBridge/issues)

### [SightIndex](https://github.com/otterview-labs/SightIndex)

Index local images, videos and camera streams. Inspect person crops, search candidate frames by description or parsed attributes, and return to the source material to check the result.

- FastAPI backend and Vue console for media management, person crops and search results.
- Try image upload and processing with SQLite and HOG. Attribute parsing, semantic search and cross-camera retrieval need additional models and indexes.

An experimental reference implementation. Search results need human review. The first-run guide includes response examples and help with empty results.

[First run](https://github.com/otterview-labs/SightIndex/blob/main/docs/first-run.md) · [Documentation](https://github.com/otterview-labs/SightIndex/blob/main/README.md) · [Issues](https://github.com/otterview-labs/SightIndex/issues)

### [DocuGen](https://github.com/otterview-labs/DocuGen)

Add material to a knowledge base, inspect sources and search results, fill Word templates, or generate documents section by section. You can fill templates manually before connecting a model service for AI assistance.

For individuals and trusted teams running their own instance. The current version uses one shared workspace.

[Setup and usage](https://github.com/otterview-labs/DocuGen/blob/main/README.en.md) · [Releases](https://github.com/otterview-labs/DocuGen/releases) · [Issues](https://github.com/otterview-labs/DocuGen/issues)

## Contributing

Report problems in the relevant repository, including the version, steps to reproduce and useful logs. Documentation fixes and pull requests are welcome. Please discuss larger changes first.

See the [project index](https://github.com/otterview-labs/.github/blob/main/profile/PROJECTS.md) for setup requirements, current status and licenses.
