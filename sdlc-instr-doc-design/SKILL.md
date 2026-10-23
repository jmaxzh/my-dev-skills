---
name: sdlc-instr-doc-design
description: Design, write, revise, and review instructions, prompts, skills, and instructional or explanatory documents. Use for document artifacts, including knowledge-base documents, not ordinary conversational answers. Knowledge-base factual audits follow the applicable knowledge-base rules.
---

# 指令与文档设计原则

## 适用范围

- 为指令、提示词、技能及文档产物的设计、撰写、修改和审查应用本技能；不用于普通对话回答。
- 按目标产物已有约定处理领域规则、格式和维护权限，不将项目或知识库的专属要求推广到其他产物。

## 共同表达规则

- 优先沿用项目或文档已定义的术语，未定义时采用业界通用术语；按需解释影响理解的概念。
- 同一概念使用同一规范术语，同一术语仅表达一个概念；不要为避免重复轮换同义词。
- 识别原始表述的实际含义，转换为规范表述，不机械沿用；存在多义或定义冲突时，明确含义、范围及与相近概念的区别。
- 消除指代歧义，明确否定范围，区分可能原因与确定原因。
- 按内容的逻辑关系表达，保持事实准确、语义完整；不因压缩措辞拆散必要的条件、否定和因果关系。

## 按内容用途读取

- 设计、修改或审查约束模型行为的指令、提示词、技能及文档中的模型执行规则时，读取[提示词设计指导原则](references/prompt-design.md)。
- 处理供读者理解、操作或排障的文档时，读取[文档设计原则](references/document-design.md)；不因包含祈使句或步骤而加载提示词参考。
- 文档同时包含需要设计或审查的模型指令时，组合使用两份参考，按具体内容分别应用；不默认加载全部参考文件。

## 审查边界

- 按实际问题报告具体位置、问题、影响和修订建议；区分已确认问题、待确认事项和未验证范围。仅有审查请求时不修改目标产物。
- 提示词审查使用对应参考的最终检查；面向读者的文档审查使用文档参考，不强制套用提示词维度。
- 知识库表达审查按内容用途读取参考并遵循目标文档约定，不自动扩展为事实审计；专项审查中的事实来源、内容归属、实施状态和跨文档一致性，按适用的知识库规范和审查流程核查。
