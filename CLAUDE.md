# Claude Code Instructions

## Project overview

This repository is a minimal GitHub Codespaces environment prepared for Claude Code.

## Environment

- Runtime environment: GitHub Codespaces
- Dev container: `.devcontainer/devcontainer.json`
- Claude Code configuration directory: `/home/vscode/.claude`

## Operating rules for Claude Code

- Inspect the repository before making changes.
- Explain the intended change before editing files.
- Keep changes small and easy to review.
- Do not commit secrets, API keys, tokens, or private credentials.
- Prefer explicit commands over implicit assumptions.
- When changing files, summarize the changed paths and the reason for each change.

## Useful commands

```bash
claude --version
claude doctor
claude
```

## Authentication notes

Use browser authentication or an `ANTHROPIC_API_KEY` provided through GitHub Codespaces secrets. Do not store credentials in the repository.
