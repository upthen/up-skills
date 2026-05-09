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
