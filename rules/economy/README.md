# 能量、商店与拍卖

模块标识：`economy`。当前为定义阶段，尚未实现数据或工具。

职责：能量获得/消耗、商店刷新与锁定、候选和公共池、拍品、竞价、分红及奖励发放。

边界：品阶与购买价格不同；购牌、获得牌、用牌是不同动作。

对象：`ResourceRule`、`ShopRule`、`PoolRule`、`PoolState`、`AuctionRule`、`AuctionLot`、`Bid`、`DividendRule`。

商店和锦囊引用mechanics中的分布与抽样过程；费用层概率、指定对象概率、卡池余量和抽样依赖条件分开。概率表不自动决定完整抽样算法。

详见[模块与关系定义](../../docs/模块与关系.md)。
