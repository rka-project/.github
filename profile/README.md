# Research should not lose its memory.

RKA Project is local-first research memory and evidence infrastructure for
researchers and AI agents. Keep using Codex or Claude Code; preserve the
decisions, evidence, and context that should survive your next session.

**Start here:** [Install Core](https://github.com/rka-project/rka-core/blob/main/INSTALL.md)
· [Backend quick start](https://github.com/rka-project/rka-core#quick-start)
· [Codex setup](https://github.com/rka-project/rka-core/blob/main/INSTALL.md#85--configure-codex)
· [Claude Code setup](https://github.com/rka-project/rka-core/blob/main/INSTALL.md#step-2--add-the-local-rka-marketplace-in-claude-code)

## Why keep a research record?

A fresh AI session suggests an approach you already ruled out. Instead of
reconstructing the decision from old chats and notebooks, ask the connected
agent to retrieve the decision, its linked experiment, and its scope from RKA.
Review the evidence before continuing. Retrieval supports your judgment; it
does not replace it.

- **Capture:** save observations, literature, experiments, decisions, and questions.
- **Connect:** keep claims and decisions linked to evidence, including uncertainty and revisions.
- **Reuse:** resume from relevant records across sessions and tools.

## Projects

| Project | Role | Current status |
|---|---|---|
| [RKA Core](https://github.com/rka-project/rka-core) | Durable records, provenance, retrieval, integrity, backup, and export through local MCP, REST, CLI, and a dashboard. | [3.0.0 released](https://github.com/rka-project/rka-core/releases/tag/v3.0.0). Start here. |
| [RKA App](https://github.com/rka-project/rka-app) | Installation, lifecycle supervision, and optional deployment adapters around released Core artifacts. | In development. Not required to use Core. |
| [RKA Writer](https://github.com/rka-project/rka-writer) | A separate researcher-controlled writing workbench built on the research record. | [Design phase](https://github.com/rka-project/rka-writer/blob/main/STATUS.md); no supported authoring release. |

Status checked September 14, 2026. Core runs independently of App and Writer.
Easier local setup is the immediate access priority. Fixed-sample read-only
demos and user-owned cloud templates are planned, not a shared hosted research
service. A desktop app is not a prerequisite.

## Local-first, with explicit boundaries

In a local setup, the research database stays in your installation. You manage
access, backup, and export; no RKA account is required. RKA Project does not host
a shared database of users' research.

Your AI client and embedding provider are separate boundaries: retrieved
context may be sent to your chosen model provider, and a remote embedding
backend may receive text. Choose settings that match your research's privacy
requirements. [Read the access boundary](https://github.com/rka-project/rka-core/blob/main/docs/REMOTE_ACCESS.md).

Keep evidence inspectable, preserve earlier decisions, and review consequential
changes. Local-first storage does not make AI interpretations automatically correct.

## Documentation and participation

- [Visit the project website](https://rka-project.github.io/)
- [Read Core documentation](https://github.com/rka-project/rka-core/tree/main/docs)
- [See Core releases](https://github.com/rka-project/rka-core/releases)
- [Report an issue or ask a question](https://github.com/rka-project/rka-core/issues)
- [Discuss Writer requirements](https://github.com/rka-project/rka-writer/issues)
- [Review Core contribution conventions](https://github.com/rka-project/rka-core/blob/main/CLAUDE.md)

RKA Project is developed by researchers for workflows where continuity,
provenance, and human judgment matter.
