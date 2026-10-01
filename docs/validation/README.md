# 验证与覆盖率

模块标识：`validation`。当前为定义阶段，尚未实现数据或工具。

职责：将格式/引用/版本一致性检查、游戏内文字核对、机制实验与完整性统计分开。

边界：本模块当前只有定义；不代表已有可运行引擎、实验自动化或全量覆盖。

对象：`ValidationCase`、`Observation`、`VerificationStatus`、`CoverageReport`、`CalculationScenario`、`ModelCoverage`、`CalculationResult`、`FieldComparison`。

字段交叉比对保留双方版本、单位和来源链。计算场景保留输入、模型修订、支持项、遗漏与近似；同源计算不能充当独立实测。具体契约见[知识站对照](../research/wzwxq对照.md)。

详见[模块与关系定义](../../docs/模块与关系.md)。
