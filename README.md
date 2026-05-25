# Reflective

Reflective is a memory-native terminal coding harness for engineering teams.

It is built around a simple belief: coding agents get much more useful when they
understand the way a team actually ships. Not just the files in the repo, but
the decisions, incidents, owners, deployment constraints, failed attempts, test
recipes, and local rules that shape engineering work.

> Public availability is coming soon. Star this repo to follow releases,
> installation instructions, public examples, and product updates.

[![Status](https://img.shields.io/badge/status-coming_soon-111827?style=flat-square)](#status)
[![Issues](https://img.shields.io/github/issues/ychampion/reflective-ai?style=flat-square)](https://github.com/ychampion/reflective-ai/issues)
[![Discussions](https://img.shields.io/badge/discussions-open-2563eb?style=flat-square)](https://github.com/ychampion/reflective-ai/discussions)

## What Reflective Is

Reflective is a CLI harness for agentic coding sessions. It is designed for
developers and teams that want a terminal-native agent workflow with stronger
context, safer execution, and reusable team knowledge.

Reflective focuses on:

- **Context before action**: compile permission-filtered context from the repo,
  approved memory, decisions, incidents, and test recipes before an agent plans
  or edits.
- **Team memory**: turn useful traces, conventions, and lessons into reviewable
  memory instead of losing them after each session.
- **Skills and hooks**: make repeatable workflows explicit, auditable, and
  shareable across a team.
- **Evidence-based execution**: keep traces, outcomes, checkpoints, and
  verification attached to work.
- **Terminal-first ergonomics**: keep the primary workflow in the CLI, where
  developers already inspect code, run tests, and review diffs.

## What This Repository Is

This is the public home for Reflective.

Use this repository to:

- follow release notes and changelogs;
- learn what Reflective is and how it is different;
- find installation instructions when public distribution opens;
- open bugs, feedback, feature requests, and adoption questions;
- share public skill and hook examples;
- discuss workflows that should become first-class Reflective patterns.

## What This Repository Is Not

This repository is not the private CLI source repository.

Please do not post:

- private code, logs, stack traces, secrets, or customer data;
- internal implementation details from your company;
- credentials, API keys, tokens, invite links, or private endpoints;
- requests that require access to Reflective's internal source tree.

Public examples in this repo should be generic, sanitized, and useful to teams
without exposing proprietary information.

## Status

Reflective is currently in private development and dogfooding. The public repo
is open now so developers can track the project, star it, ask questions, and
shape the public beta.

Public install commands will be published here when the beta opens.

```bash
# Coming soon
# refl
```

The intended command is `refl`.

## Repository Map

| Path | Purpose |
| --- | --- |
| [CHANGELOG.md](CHANGELOG.md) | Public release notes and notable updates |
| [ROADMAP.md](ROADMAP.md) | Near-term product direction and public milestones |
| [docs/overview.md](docs/overview.md) | Product thesis and core concepts |
| [docs/install.md](docs/install.md) | Install and beta access notes |
| [docs/skills-and-hooks.md](docs/skills-and-hooks.md) | Public explanation of skills and hooks |
| [docs/feedback.md](docs/feedback.md) | How to file useful feedback |
| [examples/skills](examples/skills) | Generic public skill examples |
| [examples/hooks](examples/hooks) | Generic public hook examples |

## Feedback

Use GitHub Issues for actionable reports and GitHub Discussions for broader
workflow questions.

- [Bug report](https://github.com/ychampion/reflective-ai/issues/new?template=bug_report.yml)
- [Feature request](https://github.com/ychampion/reflective-ai/issues/new?template=feature_request.yml)
- [Skill or hook proposal](https://github.com/ychampion/reflective-ai/issues/new?template=skill_or_hook.yml)
- [General feedback](https://github.com/ychampion/reflective-ai/issues/new?template=feedback.yml)
- [Discussions](https://github.com/ychampion/reflective-ai/discussions)

Good feedback describes the workflow, the current friction, the desired
outcome, and the constraints a real engineering team has to respect.

## Why Star This Repo

Star this repo if you want a serious terminal coding harness that is shaped
around team context, not just prompt text. Stars help us understand public
interest and make it easier for other developers to find Reflective when the
beta opens.
