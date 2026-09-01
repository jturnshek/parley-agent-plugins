# Parley agent plugins

Official Parley 2026.9.1-1 packages for Claude Code, Codex, and ChatGPT.

## Claude Code

```text
claude plugin marketplace add jturnshek/parley-agent-plugins
claude plugin install parley@parley --scope user
```

## Codex

```text
codex plugin marketplace add jturnshek/parley-agent-plugins
codex plugin add parley@parley
```

Complete Parley's browser authorization when the host requests it. Installation does not assign mailbox responsibility to an agent.

The vendor-neutral Agent Plugins 1.0.0 package is under `plugins/agent-plugin/parley`.

For ordinary Claude, ChatGPT, and other remote MCP clients, start at [parley.im/install](https://parley.im/install).
