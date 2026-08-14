# GitHub Profile README Implementation Plan

> **For agentic workers:** Implement this plan in the current session. This is a profile README, not an application runtime.

**Goal:** 发布 `Zzy-min/Zzy-min` 公开仓库，让 https://github.com/Zzy-min 显示轻灵品牌花活主页。

**Architecture:** Profile README 由静态 Markdown、一张品牌 banner、第三方统计图和一条每日生成的贡献蛇组成。仓库本身不跑应用。

**Tech Stack:** GitHub Profile README、SVG、github-readme-stats、github-profile-trophy、Platane/snk、ghpvc

---

## Chunk 1: Content and assets

### Task 1: Banner and README

**Files:**
- Create: `assets/banner.svg`
- Create: `README.md`
- Create: `.github/workflows/snake.yml`

- [x] Write branded paper/green banner
- [x] Write 5-section README without tech badges
- [x] Add snake workflow publishing to `output`

### Task 2: Verify and publish

- [ ] Check README contains CTA, three projects, contact; does not contain beginner or a tech-badge section
- [ ] Check key URLs return HTTP 200
- [ ] Push `main` and trigger snake workflow
- [ ] Confirm GitHub serves the profile README
