# 独立发布与命名依据（2026-10-30）

采用“具体任务词 + skill”的英文标识，配中文展示名和中英简介。仓库名、SKILL.md 的 name、文件夹和调用示例保持一致；标签覆盖实际领域，不堆无关品牌或热门词。

这是一组基于用途和搜索字段的命名选择，不是搜索量测算或排名保证。

## 查询依据

- [GitHub 仓库搜索规则](https://docs.github.com/en/search-github/searching-on-github/searching-for-repositories)：默认查名称、简介、topics；README 内容需要 in:readme。名称、简介和标签因此一起更新。
- [GitHub topics](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/classifying-your-repository-with-topics)：主题页能连接同领域仓库。
- [Agent Skills 格式规范](https://agentskills.io/specification)：name 最多64字符，使用小写字母、数字、连字符，并与目录一致；description 说明用途与触发条件。
- [Skills FAQ](https://www.skills.sh/docs/faq)：目录排名依据真实用户安装遥测。上传 GitHub 不等于已被收录或有安装流量；本次没有制造安装量。
- 同类公开仓库 [paper-reading-skill](https://github.com/xiaofengShi/paper-reading-skill) 和 [Paper Reading Skills](https://github.com/superiony/Paper-Reading-Skills) 使用 paper reading 这一直接任务词，作为用词参考；未复制其内容，也未据此推断关键词搜索量。

## 名称映射

| 用途 | 独立仓库与新调用名 | 原调用名 |
|---|---|---|
| 论文精读教练 | [research-paper-reading-skill](https://github.com/narsss242/research-paper-reading-skill) | `paper-reading-coach` |
| 学术论文中英对照翻译 | [academic-paper-translation-skill](https://github.com/narsss242/academic-paper-translation-skill) | `nature-reader` |
| 论文精读卡与证据分析 | [research-paper-analysis-skill](https://github.com/narsss242/research-paper-analysis-skill) | `nature-paper-card` |
| 论文导读网页生成 | [paper-explainer-webpage-skill](https://github.com/narsss242/paper-explainer-webpage-skill) | `paper-teaching-pages` |
| 课程笔记与学习资料整理 | [lecture-notes-organizer-skill](https://github.com/narsss242/lecture-notes-organizer-skill) | `course-material-processing` |
| 编程与数据分析作业助手 | [programming-homework-assistant-skill](https://github.com/narsss242/programming-homework-assistant-skill) | `course-homework` |
| 学术报告 Word 与 PDF 排版 | [academic-report-formatting-skill](https://github.com/narsss242/academic-report-formatting-skill) | `academic-report-format` |
| 音视频转写与校对 | [audio-video-transcription-skill](https://github.com/narsss242/audio-video-transcription-skill) | `media-transcribe` |
| 托福口语采访练习 | [toefl-speaking-practice-skill](https://github.com/narsss242/toefl-speaking-practice-skill) | `toefl-speaking-coach` |
| 托福写作批改与反馈 | [toefl-writing-feedback-skill](https://github.com/narsss242/toefl-writing-feedback-skill) | `toefl-writing-review` |
| Obsidian 图片转文字 | [obsidian-image-ocr-skill](https://github.com/narsss242/obsidian-image-ocr-skill) | `transcribe-obsidian-images` |

## 发布与安装

11个仓库各含完整技能、中文快速开始、中英简介、领域标签和独立ZIP。旧总仓库保留旧路径，并在首页指向这些独立版本。已安装旧版本的人先备份，再选择替换；不要同时启用同用途新旧两个版本。

论文翻译、论文分析来自 nature-skills 社区适配，保留 SOURCE.md、Apache-2.0 LICENSE 和改动说明。其他资料未新增统一授权条款。

## 检查范围

11个 skill-creator 结构校验通过；11个ZIP可读取；论文翻译数学校验脚本自测通过；论文分析来源定位7项测试通过。核对改名引用与个人信息模式，发布后回读远端文件核验。

这些检查不等于完整实际课程、托福测评或外部转写服务集成测试。
