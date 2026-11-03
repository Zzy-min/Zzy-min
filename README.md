<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg" />
    <img src="./assets/banner.svg" alt="张子阳 · AI 应用与全栈开发者。把产品想法做成能运行、能验证的项目。" width="100%" />
  </picture>

  <p align="center">
    <a href="https://qling.it.com/">
      <img src="https://img.shields.io/badge/🌐_打开个人站-qling.it.com-2f6047?style=for-the-badge&labelColor=20241f" alt="打开个人站 qling.it.com" />
    </a>
    <a href="https://qling.it.com/projects">
      <img src="https://img.shields.io/badge/🗂️_项目长页-Projects-3d6b52?style=for-the-badge&labelColor=20241f" alt="项目案例长页" />
    </a>
    <a href="https://qling.it.com/resume">
      <img src="https://img.shields.io/badge/📄_在线简历-Resume-b28a55?style=for-the-badge&labelColor=20241f" alt="在线简历" />
    </a>
    <a href="https://blog.csdn.net/Zzydzyg0618">
      <img src="https://img.shields.io/badge/📝_CSDN博客-Zzydzyg0618-fc5531?style=for-the-badge&labelColor=20241f" alt="CSDN博客" />
    </a>
    <a href="mailto:zzy19812007@gmail.com">
      <img src="https://img.shields.io/badge/📧_联系邮箱-Email-2f6047?style=for-the-badge&labelColor=20241f" alt="联系邮箱" />
    </a>
    <img src="https://komarev.com/ghpvc/?username=Zzy-min&label=Views&color=2f6047&style=for-the-badge&labelColor=20241f" alt="Profile views" />
  </p>
</div>

软件工程学生（河南郑州）。我把产品想法做成**能运行、能验证、可持续维护**的项目。  
*I turn ideas into running, testable projects.*

工程关注点：**本地优先状态管理（Local-First）**、**可追溯的证据与评测门禁**、**多模型路由与终端 Agent 工具链**。代表作是 **Voling 日记** 与 **轻灵 Qling CLI**，同时长期参与开源网关 **[codex-router](https://github.com/duolahypercho/codex-router)** 的核心功能维护，并独立维护线上实时对弈平台 **[轻·棋局 XiangqiArena](https://www.xiangqiarena.com/)**。

---

### 🚀 核心代表作 / Core Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h4 align="center">01 · 📔 Voling 日记 (Voonie)</h4>
      <p align="center">
        <code>微信小程序</code> · <code>React 19 Web</code> · <code>Python FastAPI</code> · <code>SQLAlchemy</code>
      </p>
      <p>
        <strong>面向微信小程序与 Web 的 AI 语音与插画日记产品</strong>。围绕「低摩擦语音/文字输入 → 结构化日记整编 → 语义插画生成 → 长期记忆检索」构建完整产品闭环。
      </p>
      <ul>
        <li><strong>双端协同与状态流</strong>：Taro 微信小程序端 + React 19 管理与预览端 + FastAPI 异步后端服务。</li>
        <li><strong>工程可靠性设计</strong>：针对移动端弱网与长耗时生成场景，实现会话并发锁、幂等写入、失败重试与优雅降级回退。</li>
      </ul>
      <p align="center">
        <a href="https://qling.it.com/projects/voling/">
          <img src="https://img.shields.io/badge/Case-项目长页介绍-b28a55?style=flat-square" alt="Voling 项目介绍" />
        </a>
        <a href="https://github.com/Zzy-min/voonie">
          <img src="https://img.shields.io/badge/Repo-源码仓库-20241f?style=flat-square&logo=github" alt="Source" />
        </a>
        <a href="https://github.com/Zzy-min/voonie/stargazers">
          <img src="https://img.shields.io/github/stars/Zzy-min/voonie?style=flat-square&color=2f6047&label=%E2%98%85" alt="Stars" />
        </a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h4 align="center">02 · ⚡ 轻灵 (Qling CLI)</h4>
      <p align="center">
        <code>TypeScript</code> · <code>Node.js</code> · <code>MCP Protocol</code> · <code>Streaming TUI</code>
      </p>
      <p>
        <strong>面向中文开发者的本地优先 AI Agent 命令行与自动化工作台</strong>。把多步工程任务收敛在终端内执行，强调工具边界透明、运行有显式终态。
      </p>
      <ul>
        <li><strong>Agent 核心运行时</strong>：支持 SSE 流式终端 TUI、MCP 白名单工具治理、多轮持久化任务（Durable Missions）与检查点会话恢复（Checkpoint / Resume）。</li>
        <li><strong>多渠道标准分发</strong>：已正式发布至 <strong>npm</strong> 并合入微软官方 <strong>WinGet</strong> 软件源（<code>Zzy-min.qling</code>）。</li>
      </ul>
      <p align="center">
        <a href="https://www.npmjs.com/package/@qlingzzy/qling">
          <img src="https://img.shields.io/npm/v/@qlingzzy/qling?style=flat-square&color=2f6047&label=npm" alt="NPM Version" />
        </a>
        <a href="https://github.com/microsoft/winget-pkgs/pull/402294">
          <img src="https://img.shields.io/badge/WinGet-Zzy--min.qling-2f6047?style=flat-square&logo=windows-terminal" alt="WinGet Package" />
        </a>
        <a href="https://github.com/Zzy-min/qling">
          <img src="https://img.shields.io/badge/Repo-源码仓库-20241f?style=flat-square&logo=github" alt="Source" />
        </a>
        <a href="https://github.com/Zzy-min/qling/stargazers">
          <img src="https://img.shields.io/github/stars/Zzy-min/qling?style=flat-square&color=b28a55&label=%E2%98%85" alt="Stars" />
        </a>
      </p>
    </td>
  </tr>
</table>

---

### 🤝 重点参与开源维护 / Core Open Source Maintenance

<table>
  <tr>
    <td width="100%" valign="top">
      <h4>
        03 · 🔀 <a href="https://github.com/duolahypercho/codex-router">duolahypercho/codex-router</a>
        &nbsp;—&nbsp; 外部模型路由网关与跨平台控制中心
      </h4>
      <p>
        <a href="https://github.com/duolahypercho/codex-router/stargazers">
          <img src="https://img.shields.io/github/stars/duolahypercho/codex-router?style=flat-square&color=b28a55&logo=github&label=Stars" alt="GitHub Stars" />
        </a>
        <a href="https://github.com/duolahypercho/codex-router/network/members">
          <img src="https://img.shields.io/github/forks/duolahypercho/codex-router?style=flat-square&color=2f6047&logo=github&label=Forks" alt="GitHub Forks" />
        </a>
        <a href="https://github.com/duolahypercho/codex-router/commits?author=Zzy-min">
          <img src="https://img.shields.io/badge/Role-Core_Contributor_(25+_Commits)-2f6047?style=flat-square" alt="Contributor Commits" />
        </a>
        <a href="https://github.com/Zzy-min/antigravity-oauth-integration">
          <img src="https://img.shields.io/badge/Standalone_Module-antigravity--oauth--integration-20241f?style=flat-square&logo=github" alt="Standalone Extraction" />
        </a>
      </p>
      <p>
        面向 Codex CLI 及现代 AI 编程工具的本地多模型路由网关与进程编排系统。作为核心贡献者深度参与功能迭代与稳定性维护：
      </p>
      <ul>
        <li><strong>多提供商 OAuth 授权流与会话锁</strong>：设计并落地 Kimi、DeepSeek 及 Antigravity（Google Cloud Code Assist）的 OAuth 2.0 PKCE 授权引导、回调监听、并发会话锁（Session Lock）、凭据自动刷新与旧配置无感脱敏迁移。</li>
        <li><strong>流式协议转换与独立模块抽离</strong>：实现 OpenAI Chat Completions 到 Cloud Code Assist 内部 <code>v1internal</code> SSE 流式协议的双向整形与重试，并将该核心链路抽离为零外部依赖的独立模块 <a href="https://github.com/Zzy-min/antigravity-oauth-integration"><code>Zzy-min/antigravity-oauth-integration</code></a>。</li>
        <li><strong>跨平台托盘控制中心与安全回滚</strong>：参与 Windows / Linux / macOS 桌面控制中心（Control Center）、网关守护进程生命周期编排，以及配置文件的原子备份与一键安全回滚机制。</li>
      </ul>
    </td>
  </tr>
</table>

---

### ♟️ 线上系统与更多工程实践 / Production & Multi-Platform Projects

<table>
  <tr>
    <td colspan="2" width="100%" valign="top">
      <h4>
        04 · ♟️ <a href="https://www.xiangqiarena.com/">轻·棋局 XiangqiArena</a> (<a href="https://github.com/Zzy-min/Chinese-chess"><code>Zzy-min/Chinese-chess</code></a>)
        &nbsp;—&nbsp; 线上实时三棋对弈平台
      </h4>
      <p>
        <a href="https://www.xiangqiarena.com/">
          <img src="https://img.shields.io/badge/Live-www.xiangqiarena.com-2f6047?style=flat-square&logo=cloudflare" alt="Live Site" />
        </a>
        <a href="https://qling.it.com/projects/xiangqi-arena/">
          <img src="https://img.shields.io/badge/Case-架构与项目解析-b28a55?style=flat-square" alt="Case Study" />
        </a>
        <a href="https://github.com/Zzy-min/Chinese-chess">
          <img src="https://img.shields.io/badge/Repo-源码仓库-20241f?style=flat-square&logo=github" alt="Source" />
        </a>
        <a href="https://github.com/Zzy-min/Chinese-chess/stargazers">
          <img src="https://img.shields.io/github/stars/Zzy-min/Chinese-chess?style=flat-square&color=b28a55&label=%E2%98%85" alt="Stars" />
        </a>
      </p>
      <p>
        将<strong>中国象棋、五子棋、围棋</strong>汇聚一体的低延迟 Web 对弈系统。摒弃笨重传统容器，基于原生 <code>Java 11 + Undertow</code> 构建高并发 HTTP / WebSocket 服务，配合 <code>PostgreSQL (HikariCP)</code> 持久化与 <code>Cloudflare Worker + Tunnel</code> 前置门面；后端通过标准协议池化调度 <code>Pikafish</code>（皮卡鱼）、<code>Rapfi</code>、<code>KataGo</code> 引擎，支持多档位人机博弈、在线匹配、复盘导出与局面分析。
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>05 · 🌐 <a href="https://github.com/Zzy-min/qling-crossborder-insight">Qling 出海智察</a></h4>
      <p>
        <code>React 19</code> · <code>FastAPI</code> · <code>Electron</code> · <code>Playwright E2E</code>
      </p>
      <p>
        <strong>面向中小跨境卖家的证据约束型 AI 市场决策工作台</strong>（CSDN AI+跨境黑客松作品）。内置<strong>引用合同校验器</strong>（阻断无证据支撑的幻觉结论）、<strong>200 例黄金评测集</strong>（分类准确率 / 引用覆盖率门禁）与跨端自动化 E2E 测试。
      </p>
      <p>
        <a href="https://github.com/Zzy-min/qling-crossborder-insight">
          <img src="https://img.shields.io/badge/Repo-源码仓库-20241f?style=flat-square&logo=github" alt="Repo" />
        </a>
        <img src="https://img.shields.io/badge/Eval-200例黄金集门禁-2f6047?style=flat-square" alt="Golden Dataset" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h4>06 · 🌱 <a href="https://github.com/Zzy-min/studyloop">StudyLoop</a></h4>
      <p>
        <code>Flutter</code> · <code>Dart</code> · <code>SQLite</code> · <code>RevenueCat</code>
      </p>
      <p>
        <strong>专为克服学习启动阻力设计的离线优先 Android 学习伴侣</strong>（RevenueCat Shipaton Next Gen Award 参赛作品）。采用本地 SQLite 存储与三步微习惯闭环（选定任务 → 25 分钟无干扰专注 → 轻量复盘），无需联网注册即可完整运行。
      </p>
      <p>
        <a href="https://github.com/Zzy-min/studyloop">
          <img src="https://img.shields.io/badge/Repo-源码仓库-20241f?style=flat-square&logo=github" alt="Repo" />
        </a>
        <a href="https://www.youtube.com/watch?v=wFz6Qis-V9M">
          <img src="https://img.shields.io/badge/Demo-YouTube演示-b28a55?style=flat-square&logo=youtube" alt="Demo Video" />
        </a>
        <a href="https://devpost.com/software/studyloop">
          <img src="https://img.shields.io/badge/Award-Shipaton_Entry-2f6047?style=flat-square" alt="Devpost" />
        </a>
      </p>
    </td>
  </tr>
  <tr>
    <td colspan="2" width="100%" valign="top">
      <strong>更多开源仓库与工程探索：</strong>
      📈 <a href="https://github.com/Zzy-min/qling-trade"><strong>轻灵 Trade (qling-trade)</strong></a>（面向 A 股与 ETF 的本地优先规则驱动信号与仓位推演工作台，<code>FastAPI + Next.js + DuckDB</code>）
      &nbsp;｜&nbsp;
      🖥️ <a href="https://github.com/Zzy-min/personal-website"><strong>个人作品集与工程档案站 (qling.it.com)</strong></a>（展示项目长页、架构权衡与在线简历，<code>HTML/CSS/JS + Cloudflare</code>）
    </td>
  </tr>
</table>

---

### 🧰 技术栈与工程实践 / Tech Stack

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=ts,js,nodejs,py,fastapi,java,dart,flutter,react,nextjs,postgres,sqlite,docker,cloudflare,git,githubactions&theme=dark" />
    <img src="https://skillicons.dev/icons?i=ts,js,nodejs,py,fastapi,java,dart,flutter,react,nextjs,postgres,sqlite,docker,cloudflare,git,githubactions&theme=light" alt="Tech Stack Icons" />
  </picture>
</div>

| 领域 / Domain | 工程实践与使用工具 / Technologies & Practices |
| :--- | :--- |
| **AI & Agent 工具链** | Model Context Protocol (MCP)、SSE 流式网关与协议转换、OAuth 2.0 (PKCE / Session Lock)、结构化输出与引用校验、终端 TUI |
| **后端与系统架构** | TypeScript / Node.js、Python (FastAPI / SQLAlchemy / DuckDB)、Java 11/17 (原生 Undertow / WebSocket / 进程池调度)、PostgreSQL |
| **前端与多端开发** | React 19、Next.js、微信小程序 (Taro)、Flutter (Android / Desktop)、Electron、TailwindCSS |
| **验证与交付门禁** | Vitest、Playwright E2E、JUnit 5、200 例黄金评测集回归、GitHub Actions、npm / WinGet / Scoop 软件包发布 |

<p align="center">
  <sub><i>注：项目开发中有 AI 辅助协作；仓库技术栈代表实际工程落地与问题解决范围，不等于全部已精通。</i></sub>
</p>

---

### 📊 工程积累与状态 / Activity & Stats

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/stats-dark.svg" />
    <img height="186" src="./assets/stats.svg" alt="代表作品与开源协作足迹：6 核心代表作，3.9k+ 参与维护项目 Star，2 线上运行站点，25+ 开源维护 Commits" />
  </picture>
  &nbsp;
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/langs-dark.svg" />
    <img height="186" src="./assets/langs.svg" alt="原创仓库语言分布：TypeScript/Node.js 48%，Java 28%，Python 14%，Dart & JS 10%" />
  </picture>
</div>

<p align="center">
  <sub><i>语言占比按个人原创仓库代码体积估算（不含 Fork 与外部参与维护仓库），不直接代表个人熟练度。</i></sub>
</p>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Zzy-min/Zzy-min/output/github-snake-dark.svg" />
    <img alt="github contribution snake" src="https://raw.githubusercontent.com/Zzy-min/Zzy-min/output/github-snake.svg" width="100%" />
  </picture>
</div>

---

### 📬 联系与交流 / Contact

正在寻找 **AI Agent 工具链研发、全栈应用开发** 相关的实习与开源协作机会，欢迎随时交流：

- 🌐 **个人网站**：[qling.it.com](https://qling.it.com/)（含完整 [项目案例长页](https://qling.it.com/projects)）
- 📄 **在线简历**：[qling.it.com/resume](https://qling.it.com/resume)
- 📧 **联系邮箱**：[zzy19812007@gmail.com](mailto:zzy19812007@gmail.com) · [2293822701@qq.com](mailto:2293822701@qq.com)
- 📝 **技术博客**：[CSDN @Zzydzyg0618](https://blog.csdn.net/Zzydzyg0618)
