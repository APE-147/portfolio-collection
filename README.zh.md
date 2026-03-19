# Portfolio Collection

**中文** | [English](README.md)

这个仓库用来整理我的部分作品。

这里的介绍刻意保持在高层抽象，只说明项目在解决什么问题、为什么这样设计、以及我想强调的思路

## 项目总览

| 项目名称 | 语言 | 描述 / 功能 |
| --- | --- | --- |
| [tmux-sync](projects/zh/tmux-sync.md) | Rust / Python | 跨设备工作区恢复与状态收拢工具。 |
| [timing-entries-sync](projects/zh/timing-entries-sync.md) | Python | 把 Timing App 记录稳定同步到 Google Calendar 的 CLI 工具。 |
| [agent-cli](projects/zh/agent-cli.md) | Python | 把规划、执行、审查和配置切换收拢到同一入口的 Agent CLI 运行时。 |
| [yolo](projects/zh/yolo.md) | Shell / Python | 统一启动多个 AI 开发 CLI 的跨平台入口。 |
| [cc-todo](projects/zh/cc-todo.md) | Go | 从 AI 编码会话中提取并持续追踪 TODO、承诺和方向变化。 |
| [notion-composer](projects/zh/notion-composer.md) | JavaScript | 围绕 Notion 任务库的本地编排器，用来统一时间块计算、属性联动和日程同步。 |
| [notion-anki](projects/zh/notion-anki.md) | Python | 在 Notion 笔记和 Anki 卡片之间做双向同步。 |
| [tweet-database](projects/zh/tweet-database.md) | TypeScript | 以 Notion 为中枢的内容系统，通过回写社交反馈来追踪内容流转。 |
| [idea-transfer](projects/zh/idea-transfer.md) | Python | 把任务系统中的零散想法聚合、分流并转写进知识系统。 |
| [claude-mem-cloud](projects/zh/claude-mem-cloud.md) | TypeScript | 围绕 Claude 记忆系统做的云端化扩展，强调持久化、检索和 Provider 适配。 |
| [meeting-voice](projects/zh/meeting-voice.md) | TypeScript / Rust | 面向实时跨语言沟通场景的语音翻译应用。 |
| [animal-meme-generate](projects/zh/animal-meme-generate.md) | Python | 面向动物拟人化梗图的生成流水线，重点解决主体一致性和动作可信度。 |
| [spec-cloud](projects/zh/spec-cloud.md) | TypeScript | 把长会话历史做成可检索能力的 MCP 服务。 |
| [language-practice](projects/zh/language-practice.md) | TypeScript / Rust | 把媒体导入、转录、播放、练习和 AI 互动收进同一工作台的语言学习应用。 |
| [daily-collection](projects/zh/daily-collection.md) | Python | 把健康数据、时间数据和日程安排接起来的个人数据系统。 |

## 说明

- 每个项目使用一个独立 Markdown 文件记录。
- 文案优先展示问题意识、方案选择和工程判断。
- 介绍会刻意保留在公开安全的抽象层，不展开敏感实现细节。
- 项目详情现已按语言拆分到 `projects/zh/` 和 `projects/en/`。
