<div align="center">

# WritingStudio

### 面向中文长篇小说的本地 AI 写作工作台

[![Version](https://img.shields.io/badge/version-3.5.0-blue?style=flat-square)](https://github.com/lingxiaoyiyu-hub/WritingStudio-3.5.0/releases)
[![License: MIT](https://img.shields.io/badge/license-MIT-green?style=flat-square)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey?style=flat-square)](#下载安装)
[![Language](https://img.shields.io/badge/language-中文-red?style=flat-square)](#)
[![Release](https://img.shields.io/github/v/release/lingxiaoyiyu-hub/WritingStudio-3.5.0?style=flat-square&label=latest%20release)](https://github.com/lingxiaoyiyu-hub/WritingStudio-3.5.0/releases)
[![Downloads](https://img.shields.io/github/downloads/lingxiaoyiyu-hub/WritingStudio-3.5.0/total?style=flat-square&label=downloads)](https://github.com/lingxiaoyiyu-hub/WritingStudio-3.5.0/releases)
[![PRs Welcome](https://img.shields.io/badge/Issues-welcome-brightgreen?style=flat-square)](https://github.com/lingxiaoyiyu-hub/WritingStudio-3.5.0/issues)

**大纲推演 · 章节续写 · 角色记忆 · 质检润色 · 钩子爽点 · 自媒体创作**

把长篇小说写作拆成稳定可控的流程：先做全书大纲，再拆卷、拆章、写正文、定稿、沉淀角色与上下文，尽量让每一章都能接得住前文。

[下载安装](#下载安装) · [功能特性](#功能特性) · [界面预览](#界面预览) · [使用流程](#推荐小说写作流程) · [更新日志](CHANGELOG.md)

</div>

---

## 项目简介

WritingStudio 不是"一键生成一段文字"的玩具工具，而是为长篇中文小说创作打造的本地 AI 写作工作台。它也支持自媒体文章、选题灵感和内容改写。

核心理念是：**把不可控的灵感写作，变成可拆解、可推进、可沉淀的创作工程。**

> 本仓库仅提供公开发行的安装包与软件说明，**不包含源码**。

---

## 功能特性

### 小说创作主线

| 模块 | 功能说明 |
| :--- | :--- |
| **小说项目管理** | 创建/管理多个小说项目；按卷、章节组织内容；左侧章节列表快速切换；区分草稿与定稿状态；支持继续写作已有项目 |
| **大纲推演** | 根据故事灵感生成全书大纲；支持续写大纲；支持分卷、分章推进；先搭好主线、阶段目标与剧情走向 |
| **章节正文创作** | 按本章大纲生成正文；按章自然续写；支持额外指令临时控制本章写法；预览上下文减少前后文断裂；生成前检查大纲/摘要/定稿完整性 |
| **章节摘要与上下文** | 每章自动生成摘要；摘要作为后续章节上下文参考；避免长篇创作中"每章都从零开始" |
| **角色管理** | 管理小说角色信息；从正文提取关键人物；记录角色在章节中的经历与变化；维持人物一致性 |
| **AI 润色与定稿** | 对正文进行 AI 润色；支持章节定稿；定稿后可更新摘要、角色履历与记忆信息；适合"先初稿后打磨" |
| **钩子与爽点辅助** | 生成章节钩子；制造悬念、断章点和追读点；专为网文连载场景设计 |
| **质检工具** | 检测正文 AI 味；检查人物/线索/任务是否断档；连续性分析；发现前后文不连贯 |

### 自媒体与灵感辅助

| 模块 | 功能说明 |
| :--- | :--- |
| **自媒体写作** | 原创文章生成；模仿二创；选题灵感；可设置文章类型、内容领域、目标字数、语气风格与目标平台 |
| **文网与灵感** | 网文方向创作辅助；灵感生成；适合卡文、缺剧情点、缺设定时使用 |

---

## 界面预览

### 首页

![首页](docs/screenshot-main.png)

### 小说写作工作台

![小说写作工作台](docs/screenshot-novel-writing.png)

### AI 创意写作

![AI 创意写作](docs/screenshot-writing.png)

### 自媒体写作

![自媒体写作](docs/screenshot-media.png)

---

## 下载安装

### 从 Release 下载

请前往 [Releases 页面](https://github.com/lingxiaoyiyu-hub/WritingStudio-3.5.0/releases) 下载最新版本：

- `WritingStudio3.5.0.zip` —— 当前发行版安装包

### 安装步骤

1. 下载 `WritingStudio3.5.0.zip`
2. 解压到本地任意文件夹
3. 双击启动程序
4. 在**模型配置**中填入自己的模型接口（支持 OpenAI 兼容协议）
5. 回到首页，选择 **AI 创意写作** 或 **自媒体写作** 即可开始

> 💡 首次使用建议先在模型配置中确认 API Key 与模型名称无误，再开始正式写作。

---

## 推荐小说写作流程

```
新建小说项目
    │
    ▼
输入故事灵感与基础设定
    │
    ▼
生成全书大纲 ────────► （可选）续写大纲
    │
    ▼
拆分卷与章节
    │
    ▼
进入章节，补充本章大纲
    │
    ▼
生成正文初稿
    │
    ▼
AI 润色 / 钩子 / 质检 反复打磨
    │
    ▼
确认后点击定稿 ────────► 自动更新摘要、角色履历、记忆
    │
    ▼
继续写下一章
```

---

## 路线图

- [x] 小说项目管理（卷 / 章）
- [x] 全书大纲推演与续写
- [x] 章节正文生成与续写
- [x] 角色管理与上下文沉淀
- [x] 章节摘要与连续性质检
- [x] 钩子爽点辅助
- [x] 自媒体写作模块
- [ ] 更多平台风格预设
- [ ] 角色关系图谱可视化
- [ ] 长篇项目数据导出 / 备份

---

## 反馈与支持

- **Bug 反馈 / 功能建议**：请通过 [Issues](https://github.com/lingxiaoyiyu-hub/WritingStudio-3.5.0/issues) 提交，并使用对应模板
- **安全漏洞**：请按 [SECURITY.md](SECURITY.md) 中的流程私下报告
- **更新记录**：详见 [CHANGELOG.md](CHANGELOG.md)

---

## 许可证

本项目基于 [MIT License](LICENSE) 发布。

本仓库发布的安装包与可执行文件同样遵循 MIT 许可证；源代码暂不公开，但欢迎在 Issue 中交流。

---

<div align="center">

**如果这个项目对你有帮助，欢迎 Star ⭐ 支持一下**

Made with care for Chinese novel writers

</div>
