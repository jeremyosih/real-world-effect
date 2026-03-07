# Real World Effect

> Real World Effect applications and their open source codebases for developers to learn from

This project brings real-world, open source Effect apps and services together in one repository. Having production codebases aggregated in a single place is valuable for learning on its own, but it becomes dramatically more useful when you can aim AI coding agents across the whole corpus.

> [!IMPORTANT]
> Huge shoutout to [Steve Clarke's Real World Rails](https://github.com/steveclarke/real-world-rails), which is itself an actively maintained continuation of [eliotsykes/real-world-rails](https://github.com/eliotsykes/real-world-rails). `real-world-effect` is a direct adaptation of that idea and scaffold for the Effect ecosystem.

See [repos.md](repos.md) for the full list of included apps with descriptions.

## Why this matters now

When collections like this were first assembled, you had to manually grep through code or write one-off scripts to find patterns across apps. AI coding agents change that completely.

With these codebases in one directory, you can point an agent at real Effect applications and ask questions like:

- "How do these apps structure Layers, services, and runtime bootstrapping?"
- "Show me different approaches to Schema validation and decoding across these apps"
- "What patterns do apps use for workflows, retries, queues, and background processing?"
- "Find how apps handle HTTP clients, error mapping, and observability"
- "Compare authentication and session management patterns across full-stack Effect apps"

An agent can search, read, and cross-reference code across every app quickly, which makes `real-world-effect` a practical resource for researching how production Effect codebases solve problems.

### Storing your analyses

The `analyses/` directory is git-ignored — a safe place to store your own research:

- Markdown files, notes, pattern comparisons, or any documentation
- Won't be committed or show up in pull requests
- Keeps your workspace clean while working alongside the codebases

## Getting started

> [!NOTE]
> Running `bin/setup` clones all configured repositories as git submodules. Disk usage depends on how many apps you add.

Some downstream repositories may use Git LFS. Install it if a repo you add requires it: https://git-lfs.com

```bash
git clone <your-real-world-effect-repo>
cd real-world-effect/
bin/setup
```

## Staying up to date

Submodules can be updated automatically via a GitHub Action that runs weekly and opens a PR. Once merged, you just need to pull:

```bash
git pull
git submodule update
```

If you want to update all configured submodules to the latest remote commits right now, run `bin/update`.

## Scripts

- **`bin/setup`** — Initialize and download all configured submodules
- **`bin/update`** — Pull latest changes when an upstream exists and update all submodules to their latest remote commits
- **`bin/status`** — Show how many apps are configured and initialized
- **`bin/add`** — Add a new app by GitHub URL (e.g. `bin/add https://github.com/user/repo`)

## Contributing

Know of a great open source Effect app or service that should be in here? Open an issue with the GitHub URL and a short note about why it belongs.

If you already have the repo cloned, you can also add it directly:

```bash
bin/add https://github.com/githubuser/foo
# then update repos.md, commit, and open a pull request
```

#### Criteria for adding apps

Apps should:
- Be open source and publicly available on GitHub
- Use Effect meaningfully, across any major version of the ecosystem
- Be actively maintained or represent quality code worth studying
- Be real-world applications or services (not just demos, templates, or tutorials)

## Agent Skill

This repo includes a `/real-world-effect` skill for AI coding agents. It teaches your agent to search across the collected codebases to research how production Effect apps solve architectural problems.

Use the local skill in `skills/real-world-effect/` with your agent tooling, then ask questions like "how do Effect apps structure layers?" or "research workflow patterns across real world effect apps".

## Other Real World Codebase Collections

- [Real World Rails](https://github.com/steveclarke/real-world-rails)
- [Real World Ruby Apps](https://github.com/jeromedalbert/real-world-ruby-apps)
- [Real World Sinatra](https://github.com/jeromedalbert/real-world-sinatra)
- [Real World Django](https://github.com/ckrybus/real-world-django)
