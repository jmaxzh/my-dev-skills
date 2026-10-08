---
name: sdlc-workflow
description: Follow the software development lifecycle and maintain the project knowledge base. Use only when the user explicitly invokes this skill.
---

# SDLC Workflow

## 通用规则

### 写作风格与文档修改

- 编写技能指令时，使用电报体与祈使句；生成产物时，遵循对应文档类型的写作规范及用户指定风格。
- 增量修改文档；保留原有结构和有效信息。仅替换或删除被新内容覆盖、纠正或与新内容冲突的部分；重构或大范围整理前，取得用户明确要求。
- 将最终产物整理为正确方案首次即直接实现的状态；删除仅由试错、误解、纠正、回退或废弃方案产生的痕迹。

### 术语一致性

- 优先沿用项目或文档已定义的术语；同一概念使用同一规范术语，同一术语仅表达一个概念。
- 未定义时，采用业界通用术语并在首次使用处给出定义；存在多义、边界不清或冲突时，明确含义、适用范围及与相近术语的区别。

### 项目知识库维护

- 全流程按需读取用户指定的项目知识库；位置未明确时，请求指定。
- 实施完成后，按需更新受影响的知识库文档；非实施场景更新前，取得用户确认。用户已明确要求更新时，直接执行授权范围内的修改。
- 读取并遵循[项目知识库规范](references/project-knowledge-base.md)；保留受保护文档的具体修改确认要求。

## 主流程

意图 → 需求 → 技术方案 → 实施。

按实际执行阶段读取并遵循对应文件：

- 意图 → 需求：[需求](references/intent-to-requirements.md)
- 技术方案：[技术方案](references/requirements-to-technical-design.md)
- 实施：[实施要求](references/implementation.md)

## 独立可选能力

- 仅按用户明确要求执行；禁止因进入主流程阶段自动触发。
- 验收方案：[验收方案](references/acceptance-plan.md)。设计范围、判据、执行方式和证据要求；不执行验收或判定结果。
- 知识库审查：[知识库审查](references/project-knowledge-base-review.md)。禁止因日常知识库读取或更新自动启动。
