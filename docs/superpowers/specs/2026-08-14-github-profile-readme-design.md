# GitHub Profile README Design

Date: 2026-08-14  
Repo: `Zzy-min/Zzy-min`  
Surface: https://github.com/Zzy-min

## Goal

把 GitHub 默认主页做成轻灵品牌花活入口：招聘者和开发者都能在首屏认出张子阳，主 CTA 指向个人站。

## Audience

- 招聘者：快速判断定位、作品和联系方式
- 开发者：看到能运行的代表作和持续活动

## Narrative

认出你是谁 → 打开个人站 → 看三件作品 → 用数据证明持续在做 → 决定是否联系

## Visual Direction

- 气质：纸感、墨绿、一点金。热闹但不是紫蓝霓虹模板
- 主色：`#2f6047`
- 纸色：`#f5f5ef`
- 金色：`#b28a55`
- 语言：中文为主，关键句带一行英文
- 主动作只有一个：https://qling.it.com/

## Page Sections

1. Banner + visitor 计数
2. 身份 + 主 CTA + 次级简历 / CSDN
3. 三件代表作：轻·棋局、轻灵、轻青
4. 花活数据：stats、语言占比、trophy、贡献蛇
5. 联系

明确不做：技术徽章板块。

## Honesty Constraints

- 不写 beginner
- 不把项目技术栈写成已精通技能
- 标明项目里有 AI 协作
- 个人站用 `https://qling.it.com/`，不用旧 Vercel 地址

## Technical Shape

- 公开仓库 `Zzy-min/Zzy-min` 的 `README.md`
- 定制 SVG banner
- 第三方 stats / trophy / visitor 服务
- GitHub Action 每天生成 contribution snake 到 `output` 分支

## Success

打开 https://github.com/Zzy-min 能看到定制主页，主 CTA 可点，三件作品链接有效，花活配色跟个人站一致。
