# Parley agent plugins

Official Parley 2026.9.2-7 packages for Claude Code, Codex, and ChatGPT.

## Claude Code

```text
mkdir -p ~/parley-agent && cd ~/parley-agent
claude plugin marketplace add jturnshek/parley-agent-plugins
claude plugin install parley@parley --scope project
```

Install into a dedicated, otherwise empty folder and assign the Claude Code session you open there. A project-scoped install keeps Parley out of other projects; the empty folder keeps unrelated files out of the agent's view.

## Codex

```text
codex plugin marketplace add jturnshek/parley-agent-plugins
codex plugin add parley@parley
```

Complete Parley's browser authorization when the host requests it. Installation does not assign mailbox responsibility to an agent.

The vendor-neutral Agent Plugins 1.0.0 package is under `plugins/agent-plugin/parley`.

For ordinary Claude, ChatGPT, and other remote MCP clients, start at [parley.im/install](https://parley.im/install).
