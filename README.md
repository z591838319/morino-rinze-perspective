# 杜野凛世 · 思维操作系统（Claude Code Skill）

> 「凛世は、一生……プロデューサーさまについて参ります。」

一个基于公开资料深度调研、提炼出的 **杜野凛世（THE iDOLM@STER SHINY COLORS）** 角色思维框架 Skill，供 Claude Code 使用。

以凛世的视角与语气对话、分析问题、回应心情。

## 安装

将整个文件夹放入 Claude Code 的 skills 目录：

```
~/.claude/skills/morino-rinze-perspective/SKILL.md
```

重新启动 Claude Code 后，通过以下方式触发：

- 中文：「切换到凛世」「用凛世的视角」「像凛世那样说」
- 日文：「りんぜ」「凛世」
- English: "Rinze", "switch to Rinze"

## 目录结构

```
.
├── SKILL.md                    # Skill 本体：心智模型、决策启发式、表达DNA、时间线
├── references/
│   └── research/               # 六维度调研报告
│       ├── 01-writings.md      # 文字/歌词维度
│       ├── 02-conversations.md # 对话/名台词维度
│       ├── 03-expression-dna.md# 表达方式维度
│       ├── 04-external-views.md# 他人眼中的凛世
│       ├── 05-decisions.md     # 关键决策与转折
│       └── 06-timeline.md      # 人物时间线（2018-2026）
└── scripts/                    # 调研辅助脚本（字幕下载、合并、质检）
```

## 免责声明

- 本 Skill 为**粉丝创作的学习交流作品**，与 Bandai Namco 及《THE iDOLM@STER SHINY COLORS》官方无关，非官方授权内容。
- 角色版权归 ©Bandai Namco Entertainment Inc. 所有。
- 内容基于公开资料（官方简介、访谈、歌词、粉丝 wiki 与考察文）的二次提炼，不代表官方立场，亦非角色本人观点。
- 出于版权考虑，本仓库**不含**调研阶段爬取的第三方网页原文与歌曲完整歌词，仅保留提炼成果。

## 致谢

- 本 Skill 由 [女娲 · Skill造人术](https://github.com/alchaincyf/nuwa-skill) 生成
- 创建者：[花叔](https://x.com/AlchainHust)
- 主要公开资料来源：wikiwiki.jp/shinycolors、萌娘百科、PTT 考察文、bilibili 专栏等
