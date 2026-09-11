# Decent Research Skills

一套面向深度学习研究的工作方法，覆盖问题发现、文献查新、表示与架构、训练与数据、实验设计、研究决策和论文写作，并提供科学机器学习与粒子仿真的专项审查。

## 使用

从 [SKILL.md](SKILL.md) 进入，根据当前任务选择一至三个专项技能。每份技能直接说明所需知识、执行过程、判断条件和输出；专项技能也可以独立使用。模板用于整理结果，可以按项目规模合并。

可直接交给研究 agent 的指令：

> 在本仓库根目录读取 SKILL.md，按当前研究阶段使用相关专项技能。先明确问题、部署信息和待验证假设，选择最能改变研究判断的下一项工作；据此设计方法、数据和实验，记录证据、适用条件与结果。根据实际需要决定模型和流程的复杂度。

这些文件可由 agent 直接读取，也可作为项目内的研究规范进行版本管理。自动发现与安装方式由所使用的 agent 工具决定。

## 导航

| 工作 | 文件 |
|---|---|
| 总入口与阶段路由 | [SKILL.md](SKILL.md) |
| 研究判断原则 | [research_taste.md](research_taste.md) |
| 文献阅读与创新边界 | [skills/01-literature/SKILL.md](skills/01-literature/SKILL.md) |
| 问题发现与假设检验 | [skills/02-problem-discovery/SKILL.md](skills/02-problem-discovery/SKILL.md) |
| 机制驱动的表示与架构 | [skills/03-mechanism-architecture/SKILL.md](skills/03-mechanism-architecture/SKILL.md) |
| 训练范式、数据与学习信号 | [skills/04-training-data/SKILL.md](skills/04-training-data/SKILL.md) |
| 实验设计与证据裁决 | [skills/05-experiments/SKILL.md](skills/05-experiments/SKILL.md) |
| 研究决策与写作 | [skills/06-decision-writing/SKILL.md](skills/06-decision-writing/SKILL.md) |
| 科学机器学习与粒子仿真 | [skills/07-scientific-ml/SKILL.md](skills/07-scientific-ml/SKILL.md) |

## 工作模板

[问题卡](templates/problem_card.md)、[论文研究卡](templates/reading_card.md)、[主张—证据矩阵](templates/claim_evidence_matrix.md)、[实验计划](templates/experiment_plan.md)、[信息与梯度审计](templates/gradient_information_audit.md)、[阶段研究评审](templates/research_review.md)。

先填写当前决策需要的字段。小项目可以只维护一份研究记录，复杂项目再按数据、实验和方法拆分。

## 维护

将新经验写成“适用情形—判断依据—操作—验收—边界”的规则。研究项目中的事实、已有方法与实验结果继续保留来源和可复现记录；通用技能正文写出完整方法，不以论文代号或外部案例代替解释。

新增规则时检查它是否改变实际决策，是否与现有规则冲突，是否有适用范围和反例。论文阅读档案可独立保存，技能执行不依赖档案。
