# PR Skills / PR 技能库

A collection of reusable Codex skills for public relations and communications workflows.

一个用于公关与传播工作的 Codex Skill 集合。

## Skills / 技能

- [pr-media-background](skills/pr-media-background/SKILL.md): evidence-based research on journalists and media outlets for PR outreach. Covers reporter background, outlet audience and importance, company/brand/competitor coverage, pitch ideas, activity fit, risks, and verification gaps. It does not profile KOLs or influencers.

  面向 PR 媒体邀约与传播策划的记者及媒体背调，涵盖记者职业背景、媒体受众与重要程度、公司/品牌/竞品报道、约稿选题、活动适配度、风险与待核实信息。不用于 KOL 或网红筛选。

## Install a skill / 安装 Skill

Copy the skill folder into your Codex skills directory: / 将 Skill 文件夹复制到 Codex 的 skills 目录：

```bash
cp -R skills/pr-media-background ~/.codex/skills/
```

Then start a new Codex conversation or invoke `$pr-media-background`.

完成后，重新开启一个 Codex 对话，或在对话中调用 `$pr-media-background`。

## Add another skill / 添加其他 Skill

Create a new folder under `skills/`, include its `SKILL.md` and any optional resources such as `agents/openai.yaml`, then commit and push the new folder.

在 `skills/` 目录下为新 Skill 新建文件夹，放入 `SKILL.md` 和可选资源文件（例如 `agents/openai.yaml`），然后提交并推送该文件夹。
