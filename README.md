# Agent Loadout

A local tool for managing the skills, plugins, hooks, and MCP configuration used by Claude Code and Codex.

Agent setups grow across projects and tools. Agent Loadout brings their configuration into one place and provides agent-specific views, so users can see what is available, choose what to enable, and review changes before applying them.

## What it does

- Organizes shared configuration through a local hub.
- Manages global and project-level selections, subject to each agent's capabilities.
- Provides previews, backups, and restore commands for configuration changes.
- Checks for broken links, duplicate entries, and configuration drift.
- Supports conversion between agent formats where compatible and reports unsupported features.
- Offers command-line and local interface workflows.

## Design principles

- Keep a single source of configuration with agent-specific adapters.
- Make changes visible and reversible.
- Preserve the distinction between configuration, instructions, and execution permissions.
- Report compatibility limits rather than assuming identical behavior across agents.

## Publication status

This repository currently contains the project overview only. Source code, binaries, private configuration, usage records, and development history are not included.

Third-party tools and any separately obtained plugins remain subject to their respective licenses and terms. This overview does not grant rights to those materials or imply endorsement by their maintainers.
