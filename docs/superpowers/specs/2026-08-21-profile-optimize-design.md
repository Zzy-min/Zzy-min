# Profile Optimization Design (Round 2)

Date: 2026-08-21
Repo: `Zzy-min/Zzy-min`
Surface: https://github.com/Zzy-min

## 现状问题

1. 代表作表格数据是静态的，qling 已有 4 stars 但页面上看不到任何热度信号。
2. 全页没有技术栈展示，招聘者无法一眼看到 TypeScript / Java / Python 组合。
3. Profile 侧栏 bio（"A beginner coder who enjoys Java and AI."）与 README 定位（AI 应用开发者）不一致，且偏弱。
4. Pinned repositories 混入 fork（ChineseChess-AlphaZero）和工具仓库（codex-app-config-recovery），稀释代表作。
5. Profile website 只挂了 CSDN，主 CTA 个人站 qling.it.com 没有出现在侧栏。

## 改动

### README.md
- 代表作三列各加一枚动态 stars 徽章（shields.io github/stars），沿用 flat-square 风格。
- 新增「🧰 技术栈 / Tech Stack」小节：skillicons.dev 一行图标（typescript, java, python, javascript, nodejs, npm），保持克制不加进度条。
- snake `<img>` fallback 加 `width="100%"`，避免窄屏溢出。

### Profile 设置（gh api）
- name: `zzy` → `张子阳`
- bio: 对齐 README 定位，中英一句 + 代表作署名
- blog: → `https://qling.it.com/`

### Pinned Repositories（GraphQL）
- Pin: qling, Chinese-chess, qingqing, personal-website, skill-publisher, qling-trade
- Unpin: ChineseChess-AlphaZero (fork), codex-app-config-recovery

## 不做的事

- 不替换静态 stats.svg/langs.svg 为动态卡：动态卡会把 fork 计入，破坏"原创仓库"叙事；静态资产由本人定期更新。
- 不加 trophy / streak 等堆砌组件，维持纸感墨绿的克制气质。
