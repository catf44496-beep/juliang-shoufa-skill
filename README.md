# 巨量首发skill

基于巨量首发素材方法的中文信息流买量广告创意与素材制作 Skill，支持手游、小游戏和其他产品。

技能标识：`ua-ad-creative`。

## 能做什么

- 拆解参考广告的吸引机制，评估开头钩子、卖点证据、节奏和行动引导。
- 策划创意方向，扩展人物、场景、情节及视觉设计。
- 编写带时间轴的分镜、口播、字幕和素材清单。
- 输出图片与视频生成提示词，并明确角色、场景、动作和镜头的一致性要求。
- 检查参考复用与版本差异，设计创意版本测试和复盘。

## 安装

在 Codex 中输入：

```text
使用 $skill-installer 安装 GitHub 仓库 catf44496-beep/juliang-shoufa-skill 中的 ua-ad-creative 目录。
```

也可以下载本仓库，将完整的 `ua-ad-creative` 文件夹复制到 Codex 的 skills 目录（默认 `~/.codex/skills/`）。私有仓库需要使用具备访问权限的 GitHub 账号。

## 使用示例

```text
使用 $ua-ad-creative，测评这条买量素材，分析前三秒、卖点证据、节奏与改进方向。
```

```text
使用 $ua-ad-creative，为我的手游策划 3 个有实质差异的 30 秒竖屏广告方向，输出分镜口播和素材生成提示词。
```

```text
使用 $ua-ad-creative，拆解这条参考广告的吸引机制，保留人物和固定机位，给出新的事件与动作设计。
```

## 文件结构

```text
ua-ad-creative/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── creative-playbook.md
    ├── output-templates.md
    └── source-summary.md
```

## 来源与适用边界

方法参考《【创意生态】首发素材项目介绍》和《【巨量营销】首发素材创作指南》。来源链接、读取范围和文档差异见 [文档总结与规则边界](ua-ad-creative/references/source-summary.md)。

本 Skill 是创作辅助工具。历史文档中的权益、阈值和入口不自动代表现行政策；首发状态以平台实际反馈为准。不提供首发保证、平台级相似率或必然起量承诺。玩法、福利、价格和其他产品承诺应由真实素材和已确认信息支撑。
