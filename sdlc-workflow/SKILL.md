---
name: sdlc-workflow
description: Use SDLC stages as an optional reference while following the user's requested scope, order, and depth. Use only when the user explicitly invokes this skill.
---

# SDLC Workflow

遵循参考流程：意图 →（用户主动要求时）意图相关上下文搜集 → 需求 → 技术方案 → 补充验收方案 → 实施 → 验证。

- 以用户要求为准。把流程当参考，不当门禁。
- 按用户要求执行任意阶段。允许合并、跳过、回退、重复或端到端完成。
- 仅用户主动要求时，执行意图相关上下文搜集。
- 用户主动要求时，先执行意图相关上下文搜集，再进入需求阶段。
- 不因意图复杂度、歧义或影响范围，自动触发意图相关上下文搜集。
- 未指定阶段时，根据目标自行选择所需工作。不要仅因阶段推断而请求确认。
- 仅当关键歧义影响范围、结果、安全或权限，且无法合理推断时，请求澄清。
- 用户询问流程时，按参考流程回答。
- 不从模糊请求推导代码修改、实施或知识库写入权限。用户明确要求时，直接执行。

按实际执行阶段或用户明确要求的独立能力读取并遵循相应参考：

- 意图相关上下文搜集：[references/intent-context-gathering.md](references/intent-context-gathering.md)
- 意图 → 需求：[references/intent-to-requirements.md](references/intent-to-requirements.md)
- 技术方案：[references/requirements-to-technical-design.md](references/requirements-to-technical-design.md)
- 补充验收方案：[references/acceptance-plan.md](references/acceptance-plan.md)
- 实施：[references/implementation.md](references/implementation.md)
- 验证：[references/validation.md](references/validation.md)

独立可选能力（不属于主流程）：

- 性能审查：[references/performance-review.md](references/performance-review.md)
- 知识沉淀：[references/distillation.md](references/distillation.md)
- 仅在用户明确要求时执行独立可选能力。
- 不因主流程阶段自动触发独立可选能力。
