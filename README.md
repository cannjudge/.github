# holtwood-arena/.github

Holtwood Arena 的组织级配置仓库。组织主页显示在 [`profile/README.md`](profile/README.md)。

本仓库保持公开，以便组织主页可访问；赛事工作区大多为私有。公开导航只链接已脱敏、可复现的仓库，不复制比赛中的账号、提交记录或私有状态。

## 维护

- 新增赛题仓库时，在 `profile/README.md` 的命名表中确认前缀
- 台账与状态只在 `arena-ledger` 仓库维护
- 公开仓库必须具备来源、复现命令、证据边界和赛后结论

## 代理入口维护

本仓工作入口是 `AGENTS.md`，`CLAUDE.md` 导入同一正文。此处规则不会自动被其它仓库继承；各仓保留自己的项目入口。通用技术技能在 `agent-skills-kit` 维护并按固定版本发布，设备共用协议在 `cann-shared-infra` 维护和下发，题目状态留在 `arena-ledger`。更新前盘点组织仓库，更新后分别核对生成块、技能哈希与链接；公开导航不复制比赛中的私有状态。
