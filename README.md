# Up-Skills

A collection of AI-powered skills for enhancing developer productivity, code quality, and project workflows.

## Overview

This repository contains a curated set of skills designed for AI-assisted development tools (such as Trae). Each skill is a self-contained module that provides specialized knowledge and capabilities for specific domains and tasks.

## Skills

### Vue.js Ecosystem

| Skill | Description |
|:---|:---|
| [vue-best-practices](./vue-best-practices/) | Vue 3 core best practices — Composition API + `<script setup>` + TypeScript, reactivity, performance, SSR, Volar, vue-tsc |
| [vue-debug-guides](./vue-debug-guides/) | Vue 3 debugging and error handling for runtime errors, warnings, async failures, and SSR/hydration issues |
| [vue-development-guides](./vue-development-guides/) | Collection of best practices and tips for developing, refactoring, or reviewing Vue.js / Nuxt projects |
| [vue-testing-best-practices](./vue-testing-best-practices/) | Vue.js testing — Vitest, Vue Test Utils, component testing, mocking patterns, Playwright E2E |
| [vue-router-best-practices](./vue-router-best-practices/) | Vue Router 4 patterns — navigation guards, route params, route-component lifecycle interactions |
| [vue-pinia-best-practices](./vue-pinia-best-practices/) | Pinia stores — state management patterns, store setup, and reactivity with stores |
| [vue-options-api-best-practices](./vue-options-api-best-practices/) | Vue 3 Options API best practices with TypeScript integration and common pitfalls |
| [vue-jsx-best-practices](./vue-jsx-best-practices/) | Vue JSX best practices — syntax differences from React JSX, JSX plugin configuration |
| [create-adaptable-composable](./create-adaptable-composable/) | Create library-grade Vue composables that accept `MaybeRef` / `MaybeRefOrGetter` flexible inputs |

### Code Quality & Review

| Skill | Description |
|:---|:---|
| [code-review-expert](./code-review-expert/) | Structured code review with a senior engineer lens — detects SOLID violations, security risks, and proposes improvements |
| [systematic-code-review](./systematic-code-review/) | Layered progressive code review for large frontend projects — infrastructure → logic → UI → testing, with prioritized summary reports |

### Git & GitHub

| Skill | Description |
|:---|:---|
| [git-commit-push](./git-commit-push/) | Git commit with flexible quality gates — level presets (`-l`/`-m`/`-h`) and granular options (`--lint`, `--ut`, `--e2e`, `--build`, `--cr`) |
| [git-pull](./git-pull/) | Pull latest code from remote Git repositories with per-repo configurable default branches |
| [git-worktree](./git-worktree/) | Manage Git worktrees — create child worktrees with auto-linked `node_modules`, or remove existing ones |
| [github-download](./github-download/) | GitHub repository download accelerator — multi-mirror fallback for faster downloads |

### UI Frameworks

| Skill | Description |
|:---|:---|
| [ant-design](./ant-design/) | Build enterprise React applications with Ant Design — admin dashboards, data tables, complex forms |

### Project Tooling

| Skill | Description |
|:---|:---|
| [split-instructions](./split-instructions/) | Progressively split large `copilot-instructions.md` into a lean main file (<100 lines) plus on-demand sub-files via VS Code `applyTo` |
| [rebuild-project-instructions](./rebuild-project-instructions/) | Rebuild project-level AI instruction files using the Harness Engineering three-layer architecture (Suggestion / Constraint / Verification) |
| [learning-path-generator](./learning-path-generator/) | Learning path generator — acts as a private AI tutor, collecting requirements through conversation and writing progressive tutorial documents for Obsidian |

### 思维视角（古圣贤蒸馏）

用女娲.skill 蒸馏的古人思维操作系统：基于一手文本逐条核验的深度调研，提炼核心心智模型、决策启发式与表达 DNA。作为思维顾问，用特定人物的视角分析问题、审视决策。

| Skill | Description |
|:---|:---|
| [kongzi-perspective](./kongzi-perspective/) | 孔子 — 基于《论语》一手文本与历代批评史，5 个心智模型、9 条决策启发式、完整表达 DNA |
| [mengzi-perspective](./mengzi-perspective/) | 孟子 — 基于《孟子》七篇一手文本，5 个心智模型、9 条决策启发式、雄辩表达 DNA |
| [laozi-perspective](./laozi-perspective/) | 老子 — 基于王弼本《道德经》及帛书/楚简本考古信息，5 个心智模型、9 条决策启发式、极简悖论式表达 DNA |
| [zhuangzi-perspective](./zhuangzi-perspective/) | 庄子 — 基于内篇为核心的一手文本与内外杂篇分层研究，5 个心智模型、9 条决策启发式、寓言式表达 DNA |
| [wangxizhi-perspective](./wangxizhi-perspective/) | 王羲之 — 基于《兰亭集序》、书信帖文与《晋书》本传，6 个心智模型、9 条决策启发式、尺牍体表达 DNA |
| [yanzhenqing-perspective](./yanzhenqing-perspective/) | 颜真卿 — 基于《争座位帖》《祭侄文稿》等一手文本与两唐书核验，6 个心智模型、10 条决策启发式、审判文体表达 DNA |
| [sudongpo-perspective](./sudongpo-perspective/) | 苏东坡 — 基于 29+ 篇一手文本（策论、赋、书信、题跋），6 个心智模型、10 条决策启发式、完整表达 DNA |
| [mifu-perspective](./mifu-perspective/) | 米芾 — 基于《海岳名言》《画史》及宋人笔记核验，6 个心智模型、10 条决策启发式、断言式毒舌表达 DNA |
| [zhaomengfu-perspective](./zhaomengfu-perspective/) | 赵孟頫 — 基于《兰亭十三跋》、松雪斋集诗文与致中峰明本十一札，6 个心智模型、10 条决策启发式、三语域表达 DNA |
| [dongqichang-perspective](./dongqichang-perspective/) | 董其昌 — 基于《画禅室随笔》四卷与南北宗论争议史，6 个心智模型、10 条决策启发式、断片判词表达 DNA |
| [wang-yangming-perspective](./wang-yangming-perspective/) | 王阳明 — 基于 131 个来源（《传习录》三卷、《王文成公全书》、年谱等，一手占比 77%），6 个心智模型、10 条决策启发式、完整表达 DNA |
| [zengguofan-perspective](./zengguofan-perspective/) | 曾国藩 — 基于家书、日记、奏折一手文献体系与毁誉两极的批评史，5 个心智模型、9 条决策启发式、家书体表达 DNA |
| [maozedong-perspective](./maozedong-perspective/) | 毛泽东 — 基于《实践论》《矛盾论》《论持久战》等公开著作逐条核验，5 个心智模型、9 条决策启发式 |
| [xinqiji-perspective](./xinqiji-perspective/) | 辛弃疾 — 基于《美芹十论》《九议》《稼轩词》四库本全文，6 个心智模型、10 条决策启发式、完整表达 DNA |

## Structure

Each skill follows a consistent directory structure:

```
skill-name/
├── SKILL.md          # Skill definition and entry point
├── references/       # Reference documents loaded on demand
├── agents/           # Agent configuration (optional)
└── assets/           # Static assets (optional)
```

## License

[MIT](./LICENSE) © CherishTheYouth
