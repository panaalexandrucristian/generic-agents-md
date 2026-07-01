# Generic AGENTS.md

A generic `AGENTS.md` template for coding agents.

The file is intentionally stack-neutral. It does not assume a language, framework, package manager, build system, or repository architecture. Instead, it gives agents a reusable decision circuit:

- when to act directly;
- when to ask for clarification;
- when to plan first;
- what actions to avoid;
- how to verify work.

## Files

- `AGENTS.md` - shared instructions for coding agents that support the AGENTS.md convention.
- `CLAUDE.md` - imports `AGENTS.md` so Claude Code can use the same instructions.

## Usage

Copy `AGENTS.md` into the root of a repository. For Claude Code, also copy `CLAUDE.md` or create your own `CLAUDE.md` that imports `AGENTS.md`.

Add project-specific commands and conventions only when they are stable and useful in every session.
