# Holtwood Arena

个人维护者：[@holtwood](https://github.com/holtwood) · competitions / benchmarks / performance engineering

比赛与 benchmark 归档：CANN Ascend 算子题、FlagOS、Kunpeng HPC、Muse kernel，以及性能工程练习。这里保留题面来源、实现、测量记录与赛后复盘；公开入口只链接已脱敏、可复现的材料。

## 公开入口

| 仓库 | 内容 | 状态 |
|------|------|------|
| [kunpeng-s2-conv](https://github.com/holtwood-arena/kunpeng-s2-conv) | Kunpeng HPC S2：FP32 2D convolution 优化、基线分析、先验调研与分阶段路线 | public |
| [kunpeng-s3-openfoam](https://github.com/holtwood-arena/kunpeng-s3-openfoam) | Kunpeng S3：OpenFOAM v2606 `simpleFoam` 性能优化工作区 | public |
| [race](https://github.com/holtwood-arena/race) | 性能工程竞赛实验室：Speed Demon / 1BRC / PPC / DIMACS / AHC | public |

## 赛事归档结构

| 前缀 / 仓库 | 含义 |
|------|------|
| `cann-2026-challenge-` | CANN 主赛题 |
| `cann-2026-ladder-` | CANN 天梯赛题 |
| `cann-2026-power-` | CANN 电力专场 |
| `cann-shared-infra` | 跨题共用的设备调度、提交校验、技能与规范 |
| `arena-ledger` | 台账：题目、状态、账号与成绩（私有） |
| `cann-rankwatch` | 榜单观察：公开排名快照与变动记录（私有） |
| `cann-ops-playbook` | 跨题算子优化知识库：设计模式、检查表、测量口径与判决模板（私有） |
| `flagos-s2-*` | FlagOS S2 赛道工作区（私有） |
| `kunpeng-*` | Kunpeng HPC 挑战赛工作区 |
| `muse-spark-*` | Muse Spark Open Kernel Challenge 工作区（私有） |

私有赛事仓只用于个人与协作团队的赛事记录；公开主页不复制账号、提交记录、榜单快照或未脱敏题面。

## 每个赛题仓库包含

- 题面来源与约束
- 实现与构建脚本
- 正确性测试与边界用例
- 性能记录（绑定具体硬件、编译器/运行时版本与提交号）
- 赛后复盘：哪些尝试有效、哪些无效

赛后归档使用 GitHub 的 Archive 标记，例如 `cann-2026-challenge-sqrt-softplus-topk` 已归档。

## 证据边界

性能数字只在记录的硬件与软件版本下成立，不跨平台外推。赛事期间的账号、提交记录与成绩只在 `arena-ledger` 中维护；公开页面只呈现可以复核的结论和脱敏证据。
