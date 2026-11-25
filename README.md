# 组会汇报备稿

`lab-meeting-brief` 是一个 Codex 技能。给它一个实验目录，它会对照日志和数据表核实结果，挑选适合在组会上讲的图表，并把每页要讲的结论、证据和待讨论的问题写成提纲。

## 安装

在 PowerShell 中运行以下命令，将仓库克隆到 Codex 的个人技能目录。

```powershell
git clone https://github.com/hwxyk2004/Pre-skill.git "$HOME/.codex/skills/lab-meeting-brief"
```

## 使用

把示例里的路径和时长替换为本次汇报的实际信息。

> 用 `$lab-meeting-brief` 从 `D:\实验\本周结果` 准备一次 10 分钟的组会汇报。重点讲这次改动和基线的差异，挑出最值得讨论的反例，并给出逐页提纲。

完成后打开交接目录中的 `组会汇报方案.md`，即可看到讲述顺序、每页的重点、要展示的图表和出处。入选的图片和小型数据表放在相邻的 `素材/` 目录中。

需要制作幻灯片时，可把这份方案交给配套的 [PPT 制作助手](https://github.com/hwxyk2004/BUAA-PPT-skill)。
