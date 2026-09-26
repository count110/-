# CAD Design and Drafting for Local CAD MCP

A standalone Codex skill for creating, inspecting, and revising CAD drawings through a local CAD MCP that is already available in the current Codex session.

This repository contains the skill instructions and its local MCP workflow reference. It does not install, configure, launch, or provide a CAD MCP server, CAD application, command-line runtime, account, or paid service. Users must connect their own local CAD MCP to Codex. The skill stops when the required MCP tools are unavailable.

## Install in Codex

1. Confirm that your Codex session has access to a local CAD MCP.
2. In Codex, invoke `$skill-installer` and ask it to install this skill from the public GitHub path:

   `https://github.com/count110/-/tree/main/skills/cad-design-and-drafting`
3. Start a new Codex turn and ask it to use `cad-design-and-drafting` for a local CAD drawing task.

The installer places the skill in the Codex skills directory. If it does not appear after installation, restart Codex and check the installed skills list.

## Included

- `skills/cad-design-and-drafting/SKILL.md` — skill entry point and operating boundaries.
- `skills/cad-design-and-drafting/references/local-cad-mcp-workflow.md` — preflight, Domain Profiles, entity handling, Scratchpad assembly, viewport review, saving, and delivery rules.

## License

The files in this repository are provided under the MIT License. See [`LICENSE`](LICENSE).
