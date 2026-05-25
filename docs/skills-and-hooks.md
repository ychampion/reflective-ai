# Skills And Hooks

Reflective is designed around explicit, reusable workflow surfaces.

## Skills

A skill is a small workflow guide that can be loaded when a task matches its
purpose. Skills are useful for repeatable team practices such as:

- debugging a known class of incident;
- preparing a pull request;
- writing release notes;
- reviewing migrations;
- selecting regression tests;
- following a domain-specific checklist.

Good skills are:

- scoped to one workflow;
- easy to review;
- honest about risk;
- grounded in public or team-approved knowledge;
- free of secrets and proprietary examples when shared publicly.

See [examples/skills](../examples/skills).

## Hooks

Hooks run commands or inject context at defined session events. They can help
teams enforce local rules or provide context at the right time.

Examples:

- add context before a prompt is processed;
- block risky tools in sensitive paths;
- run a local policy check before edits;
- append verification notes after a test command.

Hooks are powerful because they can execute commands. Review them like code and
keep public examples generic.

See [examples/hooks](../examples/hooks).

## Public Example Standard

Public skills and hooks in this repository should never contain private
company-specific details. Use placeholders and generic scenarios.
