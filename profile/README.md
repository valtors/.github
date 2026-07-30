<div align="center">

# valtors

open source developer tools for the MCP ecosystem

nine tools. one philosophy: your data stays on your machine.

[![GitHub Org](https://img.shields.io/badge/GitHub-Valtors-181717?style=flat&logo=github)](https://github.com/valtors)
[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![No Telemetry](https://img.shields.io/badge/Telemetry-Never-red.svg)](#)

</div>

---

## the tools

| tool | what it does | lang | stars |
|------|-------------|------|-------|
| [relay](https://github.com/valtors/relay) | MCP server with 40 tools. memory, web fetch, search, file ops, screenshots, multi-agent coordination. one go binary. | Go | ![stars](https://img.shields.io/github/stars/valtors/relay?style=flat) |
| [reflow](https://github.com/valtors/reflow) | SSR-safe responsive toolkit for TypeScript. breakpoints, container queries, fluid typography. one API across 8 frameworks. | TS | ![stars](https://img.shields.io/github/stars/valtors/reflow?style=flat) |
| [observer](https://github.com/valtors/observer) | transparent MCP proxy for agent observability. logs every tool call, exposes trace history, reduces token overhead. | Go | ![stars](https://img.shields.io/github/stars/valtors/observer?style=flat) |
| [forge](https://github.com/valtors/forge) | local-first agent runtime. one binary. memory, sandboxing, observation, security, package management. agents run on top. | Go | ![stars](https://img.shields.io/github/stars/valtors/forge?style=flat) |
| [mcprobe](https://github.com/tamish560/mcprobe) | security scanner for MCP servers. detect injection patterns, find tool shadowing, baseline for drift. | Go | ![stars](https://img.shields.io/github/stars/tamish560/mcprobe?style=flat) |
| [vault](https://github.com/valtors/vault) | run your agent. it can't destroy your machine. | Go | ![stars](https://img.shields.io/github/stars/valtors/vault?style=flat) |
| [cairn](https://github.com/valtors/cairn) | agent wayfinding. temporal knowledge store in one sqlite file. no neo4j, no cloud, no lock-in. | Rust | ![stars](https://img.shields.io/github/stars/valtors/cairn?style=flat) |
| [smith](https://github.com/valtors/smith) | npm for MCP. install, compose, secure, and manage MCP servers. one binary. | Rust | ![stars](https://img.shields.io/github/stars/valtors/smith?style=flat) |
| [pulse](https://github.com/valtors/pulse) | connect everything. your ai does the rest. | Go | ![stars](https://img.shields.io/github/stars/valtors/pulse?style=flat) |

## packages

- **userelay** (npm) - [![npm](https://img.shields.io/npm/dm/userelay?label=downloads)](https://www.npmjs.com/package/userelay)
- **usereflow** (npm) - [![npm](https://img.shields.io/npm/dm/usereflow?label=downloads)](https://www.npmjs.com/package/usereflow)
- **smith-mcp** (crates.io) - [![crates](https://img.shields.io/crates/d/smith-mcp?label=downloads)](https://crates.io/crates/smith-mcp)
- **cairn-memory** (crates.io) - [![crates](https://img.shields.io/crates/d/cairn-memory?label=downloads)](https://crates.io/crates/cairn-memory)

## principles

- **MIT licensed** - everything, always
- **zero telemetry** - no analytics, no phone home, no tracking
- **boring tech** - go stdlib, sqlite, json. no frameworks you can't audit
- **local-first** - your data stays on your machine
- **human-in-the-loop** - agents assist, humans decide

## stats

- 1,036+ tests across all repos
- 624+ commits
- 8 contributors
- 1,959 monthly npm downloads
- all repos CI green

## contribute

Every repo has ARCHITECTURE.md, CONTRIBUTING.md, and SECURITY.md. Pick a repo, read the architecture doc, open a PR.

## license

MIT. everything. always.
