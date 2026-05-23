# sample-codespace

GitHub Codespaces sample repository configured for Claude Code.

## What this repository includes

- `.devcontainer/devcontainer.json` installs Claude Code in the Codespace using Anthropic's Dev Container Feature.
- `CLAUDE.md` gives Claude Code project-specific operating instructions.
- Claude Code user settings and authentication state are persisted under `~/.claude` through a dev container volume mount.

## How to use

1. Open this repository on GitHub.
2. Select **Code** → **Codespaces** → **Create codespace on main**.
3. Wait for the dev container build to finish.
4. In the Codespace terminal, run:

```bash
claude --version
claude doctor
claude
```

5. Follow the Claude Code authentication prompt.

If browser login cannot return to the Codespace, copy the code shown in the browser and paste it back into the terminal prompt.

## Optional: API key authentication

For API key based usage, store `ANTHROPIC_API_KEY` as a GitHub Codespaces secret. Do not commit API keys or OAuth tokens to this repository.

## Files

```text
.devcontainer/devcontainer.json
CLAUDE.md
README.md
```

## References

- Claude Code development containers: https://code.claude.com/docs/en/devcontainer
- Claude Code setup: https://code.claude.com/docs/en/setup
- GitHub Codespaces dev containers: https://docs.github.com/en/codespaces/setting-up-your-project-for-codespaces/introduction-to-dev-containers
