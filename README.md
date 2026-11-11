# daniel-agents

Personal Claude Code plugin marketplace. Contains one plugin, `dev-agents`, with 14 subagents.

## Install
```
/plugin marketplace add YOUR_GITHUB_USERNAME/daniel-agents
/plugin install dev-agents@daniel-agents
```

## Update agents
Edit files in `plugins/dev-agents/agents/`, bump `version` in both JSON files, commit, push, then run `/plugin marketplace update daniel-agents`.

## Agents
backtest-auditor, code-debugger, code-designer, code-tester, code-tester-checker, doc-writer, game-dev-researcher, game-systems-designer, git-release-manager, perf-profiler, planner, product-researcher, security-reviewer, ui-designer
