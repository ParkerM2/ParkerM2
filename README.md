# Parker M.

Full-stack developer building AI-powered developer tooling. Currently focused on multi-agent workflow orchestration for Claude Code — creating systems that bring structure, quality gates, and crash recovery to AI-assisted software development.

---

## Featured Projects

### [create-claude-workflow](https://github.com/ParkerM2/create-claude-workflow)
**Multi-agent workflow orchestration plugin for Claude Code**

A Claude Code plugin that implements branch-per-task feature development with specialist agents, automated QA gates, and stamp-file crash recovery. Complex features are decomposed into agent-ready tasks, executed in parallel waves with isolated git worktrees, and gated by per-task QA review before merging.

- **24 slash commands** across core workflow, Jira/Atlassian integration, and code quality analysis — `/agent-team`, `/new-plan`, `/sprint-tickets`, `/start-day`, `/audit-dependencies`, `/generate-changelog`, and more
- **3 built-in agents**: Team Leader (orchestrator), QA Reviewer (per-task quality gate), Codebase Guardian (final structural integrity check)
- **10 skills** — `/agent-team` is decomposed into 6 stamp-gated steps (`wf-preflight` → `wf-plan` → `wf-setup` → `wf-spawn` → `wf-qa-gate` → `wf-guardian` → `wf-finalize`) that survive context compaction
- **Enforcement hooks**: branch guard, destructive command guard, config guard, phase gate enforcement, JSONL progress tracking
- **Jira + Confluence integration** via `/connect-atlassian` — sprint management, ticket sync, blocker detection, retrospective prep
- Works alongside other Claude Code plugins — configurable per-project via `.claude/workflow.json`

[Install via marketplace](https://github.com/ParkerM2/claude-workflow-marketplace) | [Documentation](https://github.com/ParkerM2/create-claude-workflow)

### [Agentic-Desktop-Command](https://github.com/ParkerM2/Agentic-Desktop-Command)
**Full-Stack Multi-Device Workspace & Project Management Platform**

Massive full-stack application with mobile, Mac, and Windows support for computer-specific workspace and project management. Uses Claude Agent Teams and claude-workflow to automate everyday tasks — taking tickets or bullet-point task descriptions all the way to merged PRs. Integrates Calendar, Spotify, Discord, GitHub, and project automation into a unified AI-powered interface.

### [Syrnia-Tracker](https://github.com/ParkerM2/Syrnia-Tracker)
**Browser Extension for Gameplay Analytics**

Chrome extension for storing, formatting, analyzing, and exporting gameplay data — fully local, in-browser processing with no external dependencies.

---

## What I'm Working On

- Extending claude-workflow with deeper Atlassian integration and sprint automation
- Exploring stamp-file and JSONL patterns for crash-safe AI agent orchestration
- Building tools that give developers more control over AI agent teams — planning gates, QA cycles, scope enforcement, and auditability

---

## Tech Stack

**Languages**: TypeScript, JavaScript, Python, HTML/CSS

**Frontend**: React, Vue 3, React Native, Tailwind CSS

**Backend**: Node.js, Supabase, REST APIs

**AI/Agent Tooling**: Claude Code plugins, MCP servers, multi-agent orchestration, JSONL event systems

**Tools**: Git, GitHub Actions, Chrome Extensions, Electron

---

## Get in Touch

- Browse my repos below or check out [claude-workflow](https://github.com/ParkerM2/create-claude-workflow) to see what I'm building
- Open to collaborating on AI developer tooling and agent orchestration systems
