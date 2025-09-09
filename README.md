## 项目宗旨

记录与沉淀「厉害、可复用、可验证」的 Prompts，来源于不同理念或个人实践经验，帮助在不同场景下快速拿到更稳定、更可控的输出。

### 目标
- **收集**: 高质量、可落地的 Prompts 与其使用上下文
- **组织**: 按理念、任务类型、领域等进行结构化归档
- **复用**: 提供统一模板与元数据，方便检索、对比与复用
- **验证**: 附带验收标准与示例，支持快速 A/B 与改写迭代

## 仓库结构
- `诠释学/`: 从诠释学视角整理的笔记与步骤
  - `hermeneutics.md`
  - `steps/step_1.md`
  - `steps/step_2.md`
  - `steps/step_3.md`

建议新增目录（可按需扩展）：
- `prompts/` 按类别存放具体 Prompt 条目
  - `task/`（任务类型，如 summarize、rewrite、plan、extract）
  - `domain/`（领域，如 coding、law、medicine、finance）
  - `framework/`（思维框架，如 hermeneutics、chain-of-thought、tree-of-thought）
  - `style/`（风格，如 concise、formal、step-by-step、socratic）

## 快速开始
1) 浏览理念与方法论：`诠释学/` 下的资料可帮助你理解「如何构造更稳的 Prompt」。
2) 复制模板创建新条目：在 `prompts/` 目录合适位置新建一个 Markdown（或 JSON）文件。
3) 按模板填写元信息、指令正文、输入输出示例与验收标准。
4) 运行并验证：根据验收标准对比输出，必要时记录失败模式与改写思路。
