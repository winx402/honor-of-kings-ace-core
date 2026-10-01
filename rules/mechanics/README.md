# 关键词、事件与效果

模块标识：`mechanics`。当前为定义阶段，尚未实现数据或工具。

职责：事件语义、条件、选目标、公式与单位、效果动作、持续期/叠加/唯一限制、复合效果和触发链。

边界：不从文案自动确定优先级；关键词、技能、效果和战斗状态分别定义。

对象：`KeywordDefinition`、`EventDefinition`、`AbilityDefinition`、`EffectDefinition`、`Condition`、`TargetSelector`、`Formula`、`StatusDefinition`、`ProbabilityDistribution`、`SamplingRule`。

分布与抽样规则保留候选、条件、权重/概率、有无放回及未知依赖；概率表不自动等于完整算法。具体契约见[知识站对照](../../docs/research/wzwxq对照.md)。

详见[模块与关系定义](../../docs/模块与关系.md)。
