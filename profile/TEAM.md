# Otterview Labs

English · [中文](TEAM.zh-CN.md)

Otterview Labs is the technology and open-source organization of 重庆浩鲸智能, based in Chongqing, China. We develop AI vision software for model training and deployment: the training platform manages data and models, while aibox applies models to video analysis on site.

We also maintain public projects for coding-agent task management and image and video retrieval.

## Research directions

### Computer vision

Our work covers object detection, event review and visual retrieval for people, vehicles and events in images, videos and camera streams.

For event review, CV selects candidate events and a vision-language model checks them against the scene. Visual retrieval finds related images and videos, with source material available for users to verify.

SOP visual inspection is in development. Users configure inspection rules and models, capture on-site images, and inspect results and saved evidence. Work includes rule management and an Android inspection client; mobile capture and video uploads are still undergoing device testing.

### Device applications

We explore visual perception, voice interaction and device control, including firmware, voice services and control logic. These projects involve prototypes and application research.

The fire-control manipulator uses visual calibration to locate a panel and its buttons. A pressing tool on the arm operates the existing fire-control panel, with adaptation for each panel layout.

A wearable round-screen tourism badge provides character voice guides and electronic attraction stamps. Work includes firmware, voice services and a companion mini program connected over Bluetooth. Phone testing and publication of the mini program are still in progress. A programmer's desktop assistant displays AI coding tasks and alerts the user when input or confirmation is needed.

## Model training and deployment

The training platform uses an agent to guide model training. aibox combines CV detection with vision-language model review for on-site video analysis.

### Model training platform

People training their first model can use natural language to work through data preparation, training and result inspection. The assistant prepares parameters and queries tasks; users confirm key operations.

Media, annotations, dataset versions, training jobs and model artifacts are managed within a project, with separate workspaces for object detection and visual question answering. Images can be imported directly; frames can be sampled from video files and live streams.

Users edit boxes, classes or image-question-answer pairs in the annotation workspace. AI annotations go through human review before publication as a dataset version. Training uses a selected dataset version, base model and parameters; model artifacts and evaluation records can then be inspected.

Images generated from references and prompts follow the same annotation and review process.

### aibox model deployment

aibox is visual analysis software combining CV and vision-language models. CV detects objects and selects candidate events. A vision-language model reviews the images against scene rules, then event results and alerts are returned to business systems.

We focus on software and model adaptation, and do not manufacture edge devices. Deployment uses computing hardware suited to the site. Supported models, video capacity and results depend on the version and runtime environment.

### Edge agents and model adaptation

We organize model calls, scene rules and event handling into configurable tasks and scene packages. Research includes object detection, vision-language model review, and model execution and interface adaptation on Qualcomm platforms. Scene-package testing, device adaptation and end-to-end validation are progressing separately; availability depends on the validated version.

## Future work

Robotics and embodied AI are future research plans. A fire-control manipulator prototype has been completed, providing experience in visual perception and device control.

Integration between robotic arms, PLCs and embedded controllers is also being studied and needs validation against the available interfaces and devices.

## Public projects

| Project | Purpose |
| --- | --- |
| [agentBridge](https://github.com/otterview-labs/agentBridge) | Follow Codex and Claude Code sessions across development machines from a phone, find tasks awaiting a reply, and prepare drafts for the user to send. |
| [SightIndex](https://github.com/otterview-labs/SightIndex) | Visual indexing and retrieval for images, videos and camera streams. An experimental reference implementation whose results need human review. |

See the [project index](PROJECTS.md) for setup and current status. License terms and scope are defined in each repository.

## Get in touch

We welcome discussion of visual algorithms, model training and edge deployment, as well as contributions to our projects. Report software problems in the relevant repository's Issues with the environment, reproduction steps and expected behavior. Documentation fixes and code changes can be submitted as pull requests.

[Organization](https://github.com/otterview-labs) · [Website](https://otterview-labs.github.io/) · [Project index](PROJECTS.md)
