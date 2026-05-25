# Reflective

Reflective is a memory-native coding harness for teams using AI agents in the
terminal.

Most coding agents can inspect a repository, run commands, and propose patches.
Reflective is built for the next layer of work: helping agents understand the
context a strong engineer would ask for before changing code.

That context includes decisions, incidents, ownership, local conventions, test
recipes, deployment constraints, failed attempts, and team-specific workflows.
Reflective brings that knowledge into the coding session in a way that is
reviewable, permission-aware, and reusable.

> Reflective is coming soon. Star this repo to follow public updates and beta
> availability.

[![Status](https://img.shields.io/badge/status-coming_soon-111827?style=flat-square)](#status)
[![Issues](https://img.shields.io/github/issues/ychampion/reflective-ai?style=flat-square)](https://github.com/ychampion/reflective-ai/issues)
[![Discussions](https://img.shields.io/badge/discussions-open-2563eb?style=flat-square)](https://github.com/ychampion/reflective-ai/discussions)

## Why Reflective

AI coding gets harder inside real teams. The agent needs to know more than the
current prompt and the current file tree.

Reflective is designed around five product principles:

- **Context before action**: compile the relevant repo, memory, decision, and
  test context before planning or editing.
- **Memory that compounds**: preserve useful lessons from previous work so the
  next session starts smarter.
- **Explicit workflows**: make repeatable team practices available as skills
  instead of relying on tribal knowledge.
- **Controlled automation**: use hooks, permissions, checkpoints, and traces so
  automated work stays inspectable.
- **Terminal-native execution**: keep the workflow close to the tools engineers
  already use to read code, run tests, and review diffs.

## CLI Experience

Reflective is intended to be a focused CLI experience:

```bash
refl
```

Inside a session, you describe the work in plain English. Reflective prepares
context, plans against the actual repository, uses approved tools, records what
happened, and reports verification evidence before calling work complete.

Example workflows:

- investigate a failing test with prior incident context;
- ask which files and owners are relevant before making a risky change;
- run a skill for release notes, migrations, or review prep;
- use hooks to enforce local policy before write tools run;
- turn a successful trace into reviewable team memory.

## Core Surfaces

| Surface | Purpose |
| --- | --- |
| `refl` | terminal entrypoint |
| Memory | reviewed knowledge from past sessions, decisions, and incidents |
| Skills | reusable workflows for common engineering tasks |
| Hooks | local lifecycle checks and context injection |
| Traces | evidence of actions, tool use, diffs, and verification |

## Status

Reflective is currently invite-only. Public installation is coming soon.

Public beta details, install commands, and release notes will be published in
this repository.

## Learn More

- [About Reflective](docs/about.md)
- [Install status](docs/install.md)
- [Skills and hooks](docs/skills-and-hooks.md)
- [Feedback guide](docs/feedback.md)
- [Changelog](CHANGELOG.md)

## Feedback

We are especially interested in workflows where existing coding agents lose
important team context.

- [Share feedback](https://github.com/ychampion/reflective-ai/issues/new?template=feedback.yml)
- [Request a workflow](https://github.com/ychampion/reflective-ai/issues/new?template=feature_request.yml)
- [Propose a skill or hook](https://github.com/ychampion/reflective-ai/issues/new?template=skill_or_hook.yml)
- [Start a discussion](https://github.com/ychampion/reflective-ai/discussions)
