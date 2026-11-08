# Real World Effect

Production Effect applications and libraries collected as git submodules for research and comparison.

Use this file as the human-readable catalog of the repos included in this workspace. When you add a new submodule with `bin/add` (or `bin/add --lib`), add a matching entry under the right section.

- **Applications** (`apps/`) — products and services built with Effect
- **Libraries** (`libs/`) — frameworks and packages built on Effect, useful for studying library design and public API patterns

## Entry Template

```md
### repo-name
Short description of the application or service. [https://example.com](https://example.com)
[https://github.com/org/repo](https://github.com/org/repo)
```

## Applications

### t3code
T3 Code is a minimal web GUI for coding agents. Currently Codex-first, with Claude Code support coming soon.
[https://github.com/pingdotgg/t3code](https://github.com/pingdotgg/t3code)

### AnswerOverflow
Answer Overflow turns Discord knowledge into indexed pages for Google, ChatGPT, and AI agents. Used by 1M+ users. [https://www.answeroverflow.com/](https://www.answeroverflow.com/)
[https://github.com/AnswerOverflow/AnswerOverflow](https://github.com/AnswerOverflow/AnswerOverflow)

### course-video-manager
A tool for managing course video publishing workflows — editing metadata, generating descriptions, creating thumbnails, and posting to social platforms.
[https://github.com/mattpocock/course-video-manager](https://github.com/mattpocock/course-video-manager)

### better-context
btca is a source-grounded tool that lets AI agents answer questions by searching real code instead of stale docs. [https://btca.dev](https://btca.dev)
[https://github.com/davis7dotsh/better-context](https://github.com/davis7dotsh/better-context)

### expect
Let agents test your code in a real browser. [https://expect.dev](https://expect.dev)
[https://github.com/millionco/expect](https://github.com/millionco/expect)

### executor
The missing integration layer for AI agents. Lets them call OpenAPI, MCP, GraphQL, and custom JS tools in a secure environment. [https://executor.sh](https://executor.sh)
[https://github.com/UsefulSoftwareCo/executor](https://github.com/UsefulSoftwareCo/executor)

### rat-stack
An agentic TypeScript scaffold: Effect 4, XState 6 + @xstate/effect, Alchemy infra, and varlock config.
[https://github.com/joelhooks/rat-stack](https://github.com/joelhooks/rat-stack)

## Libraries

### foldkit
A frontend framework built on Effect that uses The Elm Architecture: one Model, a Message union, a pure update, and Commands that wrap Effects. [https://foldkit.dev](https://foldkit.dev)
[https://github.com/foldkit/foldkit](https://github.com/foldkit/foldkit)

### alchemy
Infrastructure as Effects: define and deploy cloud resources as Effect programs. [https://alchemy.run](https://alchemy.run)
[https://github.com/alchemy-run/alchemy](https://github.com/alchemy-run/alchemy)

### distilled
Effect-native SDKs for cloud providers. [https://distilled.cloud](https://distilled.cloud)
[https://github.com/alchemy-run/distilled](https://github.com/alchemy-run/distilled)

### livestore
A state management framework based on reactive SQLite with a built-in sync engine. [https://livestore.dev](https://livestore.dev)
[https://github.com/livestorejs/livestore](https://github.com/livestorejs/livestore)
