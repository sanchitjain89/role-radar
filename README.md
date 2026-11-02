# RoleRadar

Research and planning for finding relevant software engineering jobs, starting with free discovery tools for remote work from Delhi, India.

This repository currently contains documentation only. It is not an implemented job-search application.

Start with the [conversation handoff](docs/handoffs/2026-11-02-job-search-handoff.md).

## Notes

- [Free job discovery](docs/notes/free-job-discovery.md): current scope, source comparison, GitHub candidates, and the simplest proposed starting approach.
- [Background and AI experience](docs/notes/background-and-ai-experience.md): experience versus learning goals, role fit, production LLM clarification, and the optional small-build example.
- [Earlier automation research](docs/notes/automation-research-archive.md): broader findings retained for context, outside the current discovery-only scope.
- [Repository evidence](docs/research/2026-11-01-github-evidence.txt): original static audit with inspected revisions, source paths, commits, issues, and limitations.

Research snapshots date from November 1-2, 2026. Product capabilities, pricing, platform policies, and repository maintenance can change. Code inspection is not a live integration test.

## Continuing on another laptop

Clone or pull this repository, open its root in Codex, and ask the new chat to read the handoff and its linked notes before continuing. No runtime, packages, API keys, or account connections are needed to read these documents.

The resume and separate learning repositories are external inputs, not bundled here. Their original paths and portable alternatives are documented in the handoff.

GitHub repository: [sanchitjain89/role-radar](https://github.com/sanchitjain89/role-radar). Use SSH for Git communication:

```sh
git clone git@github.com:sanchitjain89/role-radar.git
cd role-radar
```

On a laptop where the repository is already cloned, use `git pull --ff-only` after checking for local changes. The laptop needs an SSH key authorized for this GitHub account.

Keep future research and explanations under `docs/notes/`, dated handoffs under `docs/handoffs/`, and source evidence under `docs/research/`. Update existing topic notes rather than duplicating them in every handoff.
