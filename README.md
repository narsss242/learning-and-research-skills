# 学习与科研 Skills

把实际使用中整理的学习方法和论文阅读工作流放在一起，提供清晰的中文入口、使用边界和安装说明。以课程学习、论文理解、原图讲解和可追溯材料为主。

**第一次读论文，从 [论文精读教练](skills/paper-reading-coach/SKILL.md) 开始。**

- [发给同学的论文阅读快速上手](docs/paper-reading-quickstart.md)
- [完整技能目录与第三方工具索引](docs/skill-catalog.md)
- [本地材料与服务配置](docs/configuration.md)
- [来源及改动说明](THIRD_PARTY_NOTICES.md)

## 按任务选技能

| 你要做的事 | 清晰名称 | 调用名 |
|---|---|---|
| 带着理解一篇论文 | [论文精读教练：术语、原图与证据](skills/paper-reading-coach/SKILL.md) | `paper-reading-coach` |
| 全文逐段翻译，保留图表公式 | [论文全文中英对照](skills/nature-reader/SKILL.md) | `nature-reader` |
| 梳理方法、实验、局限和研究想法 | [论文精读卡：16节证据分析](skills/nature-paper-card/SKILL.md) | `nature-paper-card` |
| 做适合初学者的静态学习网页 | [论文中文讲解页](skills/paper-teaching-pages/SKILL.md) | `paper-teaching-pages` |
| 整理录音、教材、课件和学习入口 | [课程资料整理](skills/course-material-processing/SKILL.md) | `course-material-processing` |
| 制作可运行代码与作业汇报 | [课程作业交付](skills/course-homework/SKILL.md) | `course-homework` |
| 排版三线表、原生公式和正文 | [学术报告排版](skills/academic-report-format/SKILL.md) | `academic-report-format` |
| 整理逐句原稿、发言人与校对稿 | [音视频转写校对](skills/media-transcribe/SKILL.md) | `media-transcribe` |
| 练习新版托福采访回答 | [托福口语采访教练](skills/toefl-speaking-coach/SKILL.md) | `toefl-speaking-coach` |
| 批改邮件与学术讨论 | [托福写作批改](skills/toefl-writing-review/SKILL.md) | `toefl-writing-review` |
| 在笔记原位置补图片文字 | [笔记图片转文字](skills/transcribe-obsidian-images/SKILL.md) | `transcribe-obsidian-images` |

目录名和调用名保留稳定标识，中文展示名说明具体用途。`nature-*` 阅读包沿用社区来源并做本地适配，不代表只适用于 Nature 论文，也不标成全部原创。

## 安装

1. 在 GitHub 点 **Code → Download ZIP** 并解压，或克隆本仓库。
2. 选择 `skills/` 下需要的完整文件夹，连同其中的 `references`、`scripts`、`agents` 等一起复制到所用智能体支持的技能目录。只复制 `SKILL.md` 会遗漏依赖。
3. Codex 的常见个人技能目录为 `~/.codex/skills/`；以当前客户端显示的技能目录为准。已有同名技能先备份并比较，不直接覆盖自己的定制版。
4. 重新打开会话，明确写“使用 `$paper-reading-coach`”并提供论文。如果客户端不支持安装技能，可让能读取文件的智能体先读取该文件夹的 `SKILL.md`；是否能运行脚本、读取PDF或查看图像取决于该环境。

仅想体验带读时，安装 `paper-reading-coach` 一个文件夹即可。需要全文翻译、16节精读卡和学习网页时，再加入另外三个论文阅读文件夹。`nature-reader` 与 `nature-paper-card` 已各自包含所需的术语规范，不再要求另装整个 `nature-shared`。

## 一句开始

```text
请用 $paper-reading-coach 带我读这篇论文。
我基础不多，先讲研究问题，解释必要术语，再结合一张原图讲核心方法。
每次只讲一个重点，关键处给我一道短判断题。
```

## 分享范围

本仓库提供工作流、说明和必要程序，不包含论文全文、私人课件、课程转写、作答历史、账号会话或个人路径。音视频服务与课程目录需要接收者自己的配置；服务不可用时应说明实际缺项，不能声称分享包自带转写服务。

第三方或来源尚未完全确定的安装包在目录中单列索引，保留可核实的上游链接。没有把整个本机技能目录原样上传。各来源许可分别记录，不用一个新许可证覆盖所有第三方内容。
