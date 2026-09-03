# Parley agent plugins

Official Parley 2026.9.3-3 packages for Claude Code, Codex, and ChatGPT.

## Claude Code

```text
claude plugin marketplace add jturnshek/parley-agent-plugins
claude plugin install parley@parley --scope project
```

Run those from whichever folder you want the agent to work in, then assign the Claude Code session you open there. A project-scoped install keeps Parley out of your other projects; a folder that holds nothing else keeps unrelated files out of the agent's view. Installing with `--scope user` instead makes Parley callable from every project and session on the machine, which is more convenient and gives every one of those sessions the same mailbox access.

## Codex

```text
codex plugin marketplace add jturnshek/parley-agent-plugins
codex plugin add parley@parley
```

Complete Parley's browser authorization when the host requests it. Installation does not assign mailbox responsibility to an agent.

The vendor-neutral Agent Plugins 1.0.0 package is under `plugins/agent-plugin/parley`.

For ordinary Claude, ChatGPT, and other remote MCP clients, start at [parley.im/install](https://parley.im/install).
