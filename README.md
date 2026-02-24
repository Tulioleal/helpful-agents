# Helpful Agents

A collection of specialized agents for [Claude Code](https://docs.anthropic.com/en/docs/claude-code).

## Overview

This repository contains agent definitions that can be used as sub-agents within Claude Code to provide focused, expert assistance on specific topics.

## Agents

| Agent | Description | Model |
|-------|-------------|-------|
| **html-syntax-advisor** | HTML tag choices, semantic correctness, and accessibility guidance | Haiku |
| **css-advisor** | Styling, layouts, responsive design, and animations | Haiku |
| **architecture-advisor** | Project structure, design patterns, and architectural decisions | Opus |

## Usage

Copy or symlink the agent files from `agents/` into your project's `.claude/agents/` directory, then invoke them through Claude Code.

## Contributing

Feel free to submit new agents via pull request. Each agent should be a Markdown file in the `agents/` directory following the existing format.

## License

MIT
# helpful-agents
