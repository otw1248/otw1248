# AILLM - AI-Powered Development Tools

A curated collection of favorite AI-powered development tools and frameworks that enhance engineering workflows.

---

## Repositories

### 1. [gstack](https://github.com/garrytan/gstack)

> gstack transforms Claude Code into a virtual engineering team of 23 specialized AI agents, structured as slash commands that follow a complete software development sprint workflow: Think -> Plan -> Build -> Review -> Test -> Ship -> Reflect.

- **Stars:** 58.4k
- **License:** MIT
- **Language:** TypeScript (71%)
- **Key Features:**
  - 23 specialist skills including product review, bug detection, real browser testing, security audits, and automated PR creation
  - 8 power tools with cross-model review and safety guardrails
  - Parallel sprint support: run 10-15 concurrent AI sessions
  - Multi-agent compatibility: Claude Code, Codex, Gemini CLI, Cursor, and Factory Droid
  - Real Chrome browser integration for testing

Created by Garry Tan (CEO of Y Combinator), gstack enables solo developers to ship at team-level velocity with structured, rigorous AI-assisted development.

**Repository:** [https://github.com/garrytan/gstack](https://github.com/garrytan/gstack)

---

### 2. [compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin)

> The Compound Engineering Plugin is an AI-powered plugin marketplace and workflow system that makes each unit of engineering work easier than the last by front-loading planning and review (80%) while minimizing execution effort (20%).

- **Stars:** 12.1k
- **License:** MIT
- **Language:** TypeScript (78.5%)
- **Key Features:**
  - Structured workflow: Brainstorm -> Plan -> Work -> Review -> Compound
  - Slash commands for each phase (`/ce:brainstorm`, `/ce:plan`, `/ce:work`, `/ce:review`, `/ce:compound`)
  - Broad IDE/AI tool support: Claude Code, Cursor, Codex, Gemini CLI, GitHub Copilot, Windsurf, and more
  - CLI converter to port plugins across tools
  - 78 releases (latest: v2.59.0)

The plugin addresses technical debt accumulation by enforcing a disciplined cycle where each iteration actively reduces future effort through codified patterns and learnings.

**Repository:** [https://github.com/EveryInc/compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin)

---

### 3. [superpowers](https://github.com/obra/superpowers)

> Superpowers is a complete software development workflow framework for AI coding agents. Instead of agents immediately jumping into writing code, it forces a structured process: gathering requirements -> design review -> implementation planning -> execution with testing.

- **Stars:** 126k
- **License:** MIT
- **Key Features:**
  - 7-step automated pipeline: Brainstorming -> Git Worktrees -> Plan Writing -> Subagent-Driven Development -> TDD -> Code Review -> Branch Finishing
  - Breaks work into 2-5 minute micro-tasks dispatched to fresh agents
  - Enforces strict RED-GREEN-REFACTOR TDD cycle
  - Automated code review between tasks; critical issues block progress
  - Platform-agnostic: Claude Code, Cursor, Codex, OpenCode, Gemini CLI

Superpowers transforms AI coding agents from "code generators" into structured software developers that plan, test, and review systematically. It enables long autonomous work sessions (hours) without deviation from the plan.

**Repository:** [https://github.com/obra/superpowers](https://github.com/obra/superpowers)
