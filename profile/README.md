# CANNJudge

CANNJudge：Ascend C 算子竞赛归档、状态台账、共享工具与跨题知识库。

维护者：[holtwood](https://github.com/holtwood)

> 除组织配置仓 `.github` 外，赛事仓库均为私有，仅用于个人与协作团队的赛事记录。

## 仓库命名

| 前缀 | 含义 |
|------|------|
| `2026-challenge-` | 主赛题 |
| `2026-ladder-` | 天梯赛题 |
| `2026-power-` | 电力专场 |
| `shared-infra` | 跨题共用的设备调度、提交校验、技能与规范 |
| `ledger` | 台账：题目、状态、账号与成绩 |
| `cann-ops-playbook` | 跨题算子优化知识库：设计模式、检查表、测量口径与判决模板 |

## 每个赛题仓库包含

- 题面来源与约束
- Ascend C 实现与构建脚本
- 正确性测试与边界用例
- 性能记录（绑定具体硬件与 CANN 版本）
- 赛后复盘：哪些尝试有效、哪些无效

赛后归档使用 GitHub 的 Archive 标记，不强制改仓库名；例如 `2026-challenge-sqrt-softplus-topk` 已归档。

组织内另有 `cann-ops-playbook`，只沉淀跨题可复用的设计与测量方法，不复制题目状态；题目状态仍只在 `ledger`。

## 边界

性能数字只在记录的硬件（910B2）和 CANN 版本下成立，不跨平台外推。赛事期间的账号、提交记录与成绩只在 `ledger` 中维护。
