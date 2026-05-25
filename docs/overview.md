# Reflective Overview

Reflective is a terminal coding harness built for teams that need agentic
coding to respect real engineering context.

Most coding agents can read files, run commands, and produce patches. That is
useful, but it is not enough inside a company. Real work depends on context that
often lives outside the current prompt:

- why a past approach failed;
- which services are risky to touch;
- who owns a domain;
- which tests catch the relevant regression;
- what deployment constraints matter;
- which conventions are local, implicit, or undocumented.

Reflective's thesis is that this context should become part of the harness, not
just part of a longer prompt.

## Core Concepts

### Memory-Native Sessions

Reflective is designed to compile approved, permission-filtered memory into the
agent's working context before planning or editing. The goal is not to remember
everything. The goal is to make useful team knowledge reviewable, scoped, and
available when it changes the outcome.

### Skills

Skills are reusable workflow instructions. They can encode how a team handles a
release note, incident review, migration, code review, test plan, or domain
specific task.

Good skills are small, explicit, and auditable.

### Hooks

Hooks let teams run local checks or inject context at important lifecycle
points, such as before a tool runs or before a prompt is processed. Hooks are
powerful and should be treated like code.

### Evidence

Reflective favors traceable work: what changed, which commands ran, what tests
passed, what risks remain, and what should be remembered for next time.

## Public Boundary

This repository explains the product, collects public feedback, and hosts
generic examples. It does not contain Reflective's private implementation
source.
