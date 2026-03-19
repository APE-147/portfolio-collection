# Portfolio Collection

这个仓库用来整理我的主要作品。

这里的介绍刻意保持在高层抽象，只说明项目在解决什么问题、为什么这样设计、以及我想强调的思路。

## 项目总览

| 项目名称 | 语言 | 描述 / 功能 |
| --- | --- | --- |
| [tmux-sync](projects/tmux-sync.md) | Rust / Python | 基于单一真实数据源（SSOT）理念，统管 tmux 会话与 git worktree，实现跨设备工作区无缝恢复的工作台管理器 |
| [timing-entries-sync](projects/timing-entries-sync.md) | Python | 把 Timing App 时间记录稳定同步到 Google Calendar 的 CLI 工具 |
| [agent-cli](projects/agent-cli.md) | Python | 把规划、执行、审查和运行配置收拢到同一入口里的 Agent CLI 运行时 |
| [yolo](projects/yolo.md) | Shell / Python | 统一启动 Claude Code、Codex、Gemini 等开发 CLI 的跨平台入口 |
| [cc-todo](projects/cc-todo.md) | Go | 把 AI 编码会话里的承诺、待办和方向变化提取出来并持续追踪的工具 |
| [notion-composer](projects/notion-composer.md) | JavaScript | 基于 Notion 任务库的本地编排系统，用“事件排程总线 + 决策工厂”的架构收编散落在各处的自动化脚本 |
| [notion-anki](projects/notion-anki.md) | Python | 在 Notion 笔记和 Anki 记忆卡片之间做双向同步的工具 |
| [tweet-database](projects/tweet-database.md) | TypeScript | 以 Notion 为中枢，通过集中管理多源创作并解析社交互动信号来沉淀圈子动态的内容系统 |
| [idea-transfer](projects/idea-transfer.md) | Python | 把任务系统里的零散想法重新聚合、分流并转写进知识系统的治理流程 |
| [claude-mem-cloud](projects/claude-mem-cloud.md) | TypeScript | 围绕 Claude 记忆系统做的云端化扩展，重点处理跨会话记忆的持久化、检索和 Provider 适配 |
| [meeting-voice](projects/meeting-voice.md) | TypeScript / Rust | 面向实时跨语言沟通场景的语音翻译应用，覆盖桌面端和浏览器入口 |
| [animal-meme-generate](projects/animal-meme-generate.md) | Python | 面向动物拟人化梗图的生成流水线，重点解决“像不像原来的主体”和“动作成不成立” |
| [spec-cloud](projects/spec-cloud.md) | TypeScript | 把长会话历史做成可检索能力的 MCP 服务，重点解决“按意图找回上下文” |
| [language-practice](projects/language-practice.md) | TypeScript / Rust | 把媒体导入、转录、播放、练习和 AI 互动收进同一工作台的英语学习桌面应用 |
| [daily-collection](projects/daily-collection.md) | Python | 把健康数据、时间数据和日程安排接起来的个人数据采集与分析系统 |

## 说明

- 每个项目使用一个独立 Markdown 文件记录。
- 文案优先展示问题意识、方案选择和工程判断。
- 后续可以继续补充截图、架构图、公开链接和英文版本。
