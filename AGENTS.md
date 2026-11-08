# Real World Effect

This repository contains real-world open source Effect applications and libraries as git submodules.

- `apps/` — Full source code of Effect applications and services
- `libs/` — Full source code of libraries and frameworks built on Effect
- `repos.md` — Full list with descriptions
- `analyses/` — Git-ignored directory for local research (not committed)

## How to use this repo

Search `apps/` for how applications are built, and `libs/` for how libraries design their APIs. Search across both to find how production codebases implement patterns. For example:

- Grep for dependency usage: search `package.json` and lockfiles across `apps/` and `libs/`
- Find runtime patterns: search for `Layer`, `Runtime`, `Context`, `ManagedRuntime`, and `Effect.gen`
- Compare approaches: look at how multiple apps solve the same problem
- Study schemas, services, workflows, queues, HTTP clients, testing, and deployment code

## Key details

- Submodules point to specific commits; run `bin/update` to get the latest
- Some apps may be large or polyglot — searches may take time
- The `analyses/` directory is git-ignored for storing local research
