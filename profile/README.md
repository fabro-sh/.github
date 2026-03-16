![Header](header.png?raw=true)

## AI-powered workflow orchestration

Fabro is an AI-powered workflow orchestration platform. Define workflows as graphs, where each node is a stage — agent, prompt, command, conditional, human-in-the-loop, parallel, and more — executed by the workflow engine.

Learn more in the [Documentation](https://fabro.sh/docs).

## Get Started

Install the Fabro CLI:

```bash
# With Claude Code
curl -fsSL https://fabro.sh/install.md | claude

# With Codex
codex "$(curl -fsSL https://fabro.sh/install.md)"

# With Bash
curl -fsSL https://fabro.sh/install.sh | bash
```

Then initialize and run your first workflow:

```bash
cd my-repo/
fabro init
fabro run hello
```
