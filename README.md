<div align="center">

# Hi, I'm Null

### 企业应用开发 · AI 工作流 · 自动化与可靠性

做企业应用，也做让开发和运维更可靠的小工具。

关注业务规则、数据质量与交付验证，让 AI 能力落到可维护的系统里。

</div>

---

## 关于我

我主要使用 C#、Python 和 TypeScript，开发企业应用、Web 服务与自动化工具。既有 .NET、Django 和 Microsoft Power Platform 的实践，也在持续使用 FastAPI、Vue 和 React 构建业务系统。

相比单独接入一个模型，我更关注完整的工程过程：输入是否可信、业务规则是否清晰、结果能否追溯，以及失败后如何安全恢复。

## 最近在做

- **AI 文档处理**：从 PDF、Excel 等业务文档中提取结构化数据，处理多级 BOM、字段映射与规则校验，保留原文和结果之间的对应关系。
- **本地知识处理**：实践多格式资料整理、OCR、音频转写与本地检索，关注来源追溯、内容去重和敏感信息边界。
- **开发者工具**：围绕 AI 编码工具构建有界重试和会话恢复能力，区分临时故障、权限问题与已经发生的副作用。
- **可靠性与维护**：持续处理备份恢复、容器化服务、监控排障、依赖安全更新与 PR 审查，通过本地验证和远端回读确认交付结果。

---

## 技术栈

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

| 方向 | 常用技术 |
| --- | --- |
| 后端与接口 | Python · FastAPI · Django · C# · .NET |
| Web 前端 | TypeScript · JavaScript · Vue · React · Vite |
| 企业应用与低代码 | Power Apps · Power Automate · Dataverse |
| 数据与存储 | PostgreSQL · Redis · SQLite |
| 云与工程工具 | Linux · Docker · Nginx · Azure · Google Cloud · Cloudflare · GitHub Actions · Shell · PowerShell |

---

## 公开项目

| 项目 | 在解决什么问题 |
| --- | --- |
| [codex-auto-retry-plugin](https://github.com/Matrtex/codex-auto-retry-plugin) | 为 Codex `Stop` Hook 可见的临时模型错误提供有限退避与续跑；不是底层 HTTP 重试器，也不保证捕获所有网络故障。 |
| [claude-auto-retry](https://github.com/Matrtex/claude-auto-retry) | 面向 Claude Code CLI 的保守恢复工具：优先使用内置重试，仅在满足安全条件时恢复同一会话，不重放原始 prompt。 |

两者都重视次数限制与副作用检查，不把“自动恢复”当成事务或 exactly-once 保证。具体能力与兼容范围以各项目 README 为准。

## 我重视的工程方式

- **先核对事实，再修改**：从原始数据、代码调用链和真实日志定位原因，不只修表面现象。
- **小范围、可验证的改动**：尽量保持现有行为，用相关测试、构建和静态检查验证修改。
- **区分代码与运行结果**：提交成功不等于部署成功，任务完成状态也不等于业务结果正确。
- **保留清晰的安全边界**：保护凭据和业务数据；遇到结果未知的写入，先核对状态，不盲目重试。

---

<details>
<summary>GitHub 公开活动与语言统计</summary>

![GitHub stats](https://github-readme-stats-fast.vercel.app/api?username=Matrtex&show_icons=true&theme=default&include_all_commits=true)

![Top Langs](https://github-readme-stats-fast.vercel.app/api/top-langs/?username=Matrtex&theme=default&layout=compact&langs_count=8)

</details>
