# Repository Agent Instructions

This repository is an **instruction-only Ponytail knowledge base**.

## Mandatory behavior

- Always use the canonical Ponytail skills when working on this repository.
- The single source of truth is `ponytail/skills/`.
- Read the applicable skill before changing it or changing repository instructions.
- Do not recreate platform-specific copies, plugin manifests, MCP server code,
  installation guides, build tooling, benchmarks, or deployment infrastructure.
- MCP behavior belongs in `ponytail/skills/ponytail-mcp/SKILL.md`; keep it as
  instructions only.
- Preserve the methodology, remove duplication, and prefer concise reusable
  instructions over explanatory or operational material.

## Repository scope

Keep only material that teaches an AI agent **how Ponytail should behave** or
how its canonical skills should be used. If a file does not contribute to that
purpose, it should not be added back.
