# Parker M.

Full-stack developer building AI-powered developer tooling. Currently focused on multi-agent workflow orchestration for Claude Code — creating systems that bring structure, quality gates, and crash recovery to AI-assisted software development.

---

## Featured Projects

### [create-claude-workflow](https://github.com/ParkerM2/create-claude-workflow)
**Multi-agent workflow orchestration plugin for Claude Code**

A Claude Code plugin that implements branch-per-task development with specialist agents (Team Leader, QA Reviewer, Codebase Guardian), automated quality gates, and crash-safe JSONL progress tracking. Designed for complex multi-file features that benefit from structured decomposition and automated QA cycles.

- 14 slash commands: `/implement-feature`, `/review-pr`, `/generate-tests`, `/hotfix`, `/refactor`, and more
- Enforcement hooks: branch guard, config guard, destructive command guard
- Customizable guardrails: mandatory planning gates, scoped file ownership, per-task QA, error recovery protocols
- Works alongside other plugins (Superpowers, custom agent packages) — `/discover-agents` retrofits existing agents into the structured workflow
- JSONL event tracking with concurrent instance support and crash recovery

[Install via marketplace](https://github.com/ParkerM2/claude-workflow-marketplace) | [Documentation](https://github.com/ParkerM2/create-claude-workflow)

### [Claude-UI](https://github.com/ParkerM2/Claude-UI)
**AI-Infused Desktop Command Center**

Desktop application built with TypeScript for managing personal and work tasks with AI assistance. Integrates Calendar, Spotify, Discord, GitHub, and project automation into a unified interface.

### [Syrnia-Tracker](https://github.com/ParkerM2/Syrnia-Tracker)
**Browser Extension for Gameplay Analytics**

Chrome extension for storing, formatting, analyzing, and exporting gameplay data — fully local, in-browser processing with no external dependencies.

---

## What I'm Working On

- Extending claude-workflow with official marketplace submission and deeper agent coordination
- Exploring structured progress tracking patterns for terminal-based AI agents
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
