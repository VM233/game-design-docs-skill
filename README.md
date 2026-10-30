# 游戏设计文档维护 · game-design-docs

用于各类游戏项目的 Codex skill：维护用户目标，处理需求变化，说明设计选型，按问题沉淀经验，减少臃肿和流水账。文档按主题与实际规模组织，不固定拆成三份，也不要求引擎或额外工具。

主要规则见 [SKILL.md](SKILL.md)，压缩与冲突处理的虚构示例见 [references/examples.md](references/examples.md)。

## 安装与使用

将本仓库克隆到个人技能目录下的 `game-design-docs` 文件夹；个人技能目录已存在时执行：

```powershell
git clone https://github.com/VM233/game-design-docs-skill.git "$env:USERPROFILE/.codex/skills/game-design-docs"
```

若已安装则在该目录更新，不重复克隆或覆盖本地改动。也可以按自己的 Codex 环境使用其技能目录。入口包含标准 `SKILL.md` 和 `agents/openai.yaml`，支持正常自动选用，也可显式调用：

> 使用 $game-design-docs 整理这个项目的设计资料，核对新旧要求，说明选型理由，按问题汇总踩坑经验。

> 使用 $game-design-docs 把我刚提出的需求同步到相关设计，处理与旧要求的冲突。

一次调用只处理指定项目与授权范围；不会因为安装该 skill 就批量改写所有游戏文档。

公开仓库仅包含通用方法和虚构示例，不包含作为研究样本的游戏文档、原始会话、素材或测试产物。
