# Real World Effect

This repository contains real-world open source Effect applications as git submodules.

- `apps/` — Full source code of Effect applications and services
- `repos.md` — Full list with descriptions
- `analyses/` — Git-ignored directory for local research (not committed)

## How to use this repo

Search across all apps to find how production codebases implement patterns. For example:

- Grep for dependency usage: search `package.json` and lockfiles across `apps/`
- Find runtime patterns: search for `Layer`, `Runtime`, `Context`, `ManagedRuntime`, and `Effect.gen`
- Compare approaches: look at how multiple apps solve the same problem
- Study schemas, services, workflows, queues, HTTP clients, testing, and deployment code

## Key details

- Submodules point to specific commits; run `bin/update` to get the latest
- Some apps may be large or polyglot — searches may take time
- The `analyses/` directory is git-ignored for storing local research
