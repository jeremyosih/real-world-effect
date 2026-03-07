---
name: real-world-effect
description: Research how production Effect applications solve architectural problems using the Real World Effect repository. Use when the user wants to know how other apps handle something, find patterns, or compare approaches. Triggers on "effect patterns", "how do other effect apps", "real world effect", "research how apps do".
---

# Effect Pattern Research

## What This Is

The **Real World Effect** repository is a collection of real-world Effect
application source code across multiple versions of the ecosystem. The `apps/`
directory contains the full source of each app — packages, runtimes, layers,
schemas, services, workflows, and supporting infrastructure.

## Locating the Repository

Look for a directory called `real-world-effect` with an `apps/` subdirectory.
Check the current working directory first, then `~/Developer/real-world-effect`,
then `~/src/real-world-effect`. If not found, ask the user where it lives.

## What To Do

The user gives you a topic. Spin up parallel agents to search the apps for
how real codebases implement that pattern. Read actual code — package
manifests, runtime setup, Layer composition, services, tags, Schema usage,
HTTP clients, workflows, tests, deployment code — not just file names.
Synthesize what you find into a clear analysis.

If the user's wording suggests they want help choosing a pattern for their
current project (words like "compare for us", "which fits best",
"adversarial", "debate", "evaluate for our project"), also spin up adversarial
agents that each argue for a different pattern in the context of the current
project's architecture and goals.
