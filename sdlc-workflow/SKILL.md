---
name: sdlc-workflow
description: Follow the software development lifecycle and maintain the project knowledge base. Use only when the user explicitly invokes this skill.
---

# SDLC Workflow

## 工作流程与能力

意图 → 需求 → 技术方案 → 实施。

按实际执行阶段读取并遵循对应文件：

- 意图 → 需求：[需求](references/intent-to-requirements.md)
- 技术方案：[技术方案](references/requirements-to-technical-design.md)
- 实施：[实施要求](references/implementation.md)

独立可选能力仅按用户明确要求执行；禁止因进入主流程阶段自动触发：

- 验收方案：[验收方案](references/acceptance-plan.md)。设计范围、判据、执行方式和证据要求；不执行验收或判定结果。
- 知识库审查：[知识库审查](references/project-knowledge-base-review.md)。禁止因日常知识库读取或更新自动启动。

## 规则

- 将执行本技能产生的回答与交付产物统称为任务输出；交付产物指代码、文档等可交付成果，不含普通对话回答。两者均不含本技能指令。
- 优先沿用项目或文档已定义的术语；未定义时，采用业界通用术语并在首次使用处给出定义。
- 同一概念使用同一规范术语，同一术语仅表达一个概念；不要为避免重复轮换同义词。
- 识别原始表述的实际含义，转换为规范表述；避免机械沿用。
- 存在术语多义、边界不清或定义冲突时，明确含义、适用范围及与相近术语的区别。
- 缩写首次使用时给出全称；后文保持同一写法。
- 根据任务类型和读者调整任务输出；优先遵循用户明确指定的风格、项目约定及必须保留的格式。
- 明确必要的执行主体、操作对象、前置条件、约束及预期结果；消除指代歧义。
- 保持事实准确、逻辑清晰、语义完整；删除套话、重复及无效修饰，保留必要的背景、因果、权衡与不确定性。
- 按内容的逻辑顺序表达；明确否定范围，区分可能原因与确定原因。
- 不为追求变化而改写已经清晰的内容；避免过度简化。
- 以正确方案首次直接实现为最终交付标准；清除试错、误解、纠正、回退及废弃方案留下的无效内容与痕迹。
- 修改已有交付产物时，读取并遵循[已有产物修改规则](references/artifact-editing.md)。
- 编写中文技术操作说明或故障排查内容时，读取并遵循[中文技术写作细则](references/technical-writing.md)。
- 全流程按需读取用户指定的项目知识库；需要读取但位置未明确时，请求指定。
- 使用项目知识库时，读取[项目知识库规范](references/project-knowledge-base.md)，按实际活动遵循对应条款；变更受保护文档前，遵循具体修改确认要求。
- 用户要求修改本技能时，读取并遵循[本技能维护规则](references/skill-maintenance.md)。
