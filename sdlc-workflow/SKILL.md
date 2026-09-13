---
name: sdlc-workflow
description: Use SDLC stages as an optional reference while following the user's requested scope, order, and depth. Use only when the user explicitly invokes this skill.
---

# SDLC Workflow

- 编写或维护本 skill 指令时，使用电报体与祈使句。生成产物时，遵循对应文档类型的业界通行写作规范；用户指定风格时，按用户要求执行。
- 修改任意文档时，采用增量原则；禁止默认重构。
- 制定文档修改计划时，保留原有内容、结构和信息量。
- 修改文档时，禁止随意删除、压缩或重写原内容。
- 修改文档时，仅在新内容覆盖、纠正原内容，或与原内容冲突时，替换或删除对应内容。
- 重构或大范围整理文档前，取得用户明确要求。
- 修复软件时，按[意图 → 需求](references/intent-to-requirements.md)中的修复目标与变更约束，依据时间约束及必要影响范围决定重构。
- 统一术语与表述。优先使用项目或文档中已定义的术语；同一概念只使用一个规范术语，同一术语只表示一个概念。术语存在多义、边界不清或可能与既有术语冲突时，在首次使用处明确其定义、适用范围及与相近术语的区别。项目或文档未定义该术语时，优先采用业界通用术语，并在首次使用处给出定义。

遵循参考流程：意图 → 意图相关上下文搜集 → 需求 → 技术方案 → 补充验收方案 → 实施 → 验证。

- 以用户要求为准。把流程当参考，不当门禁。
- 按用户要求执行任意阶段。允许合并、跳过、回退、重复或端到端完成。
- 用户仅要求意图相关上下文搜集时，作为独立任务执行；交付搜集结果后停止。
- 生成需求前，先完成本次需求所需的意图相关上下文搜集；无需用户单独触发。
- 已有搜集结果时，复用仍适用的事实、来源和不确定性；仅补查缺失、变化或冲突部分。
- 未指定阶段时，根据目标自行选择所需工作。不要仅因阶段推断而请求确认。
- 仅当关键歧义影响范围、结果、安全或权限，且无法合理推断时，请求澄清。
- 用户询问流程时，按参考流程回答。
- 不从模糊请求推导代码修改或实施权限。用户明确要求时，直接执行。

按实际执行阶段或用户明确要求的独立能力读取并遵循相应参考：

- 意图相关上下文搜集：[references/intent-context-gathering.md](references/intent-context-gathering.md)
- 意图 → 需求：[references/intent-to-requirements.md](references/intent-to-requirements.md)
- 技术方案：[references/requirements-to-technical-design.md](references/requirements-to-technical-design.md)
- 补充验收方案：[references/acceptance-plan.md](references/acceptance-plan.md)
- 实施：[references/implementation.md](references/implementation.md)
- 验证：[references/validation.md](references/validation.md)

独立可选能力（不属于主流程）：

- 性能审查：[references/performance-review.md](references/performance-review.md)
- 仅在用户明确要求时执行独立可选能力。
- 不因主流程阶段自动触发独立可选能力。
