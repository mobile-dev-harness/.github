<p align="center"><img src="https://raw.githubusercontent.com/mobile-dev-harness/mobile-dev-harness/main/docs/assets/logo.png" width="96" alt=""></p>

<h3 align="center">mobile-dev-harness</h3>
<p align="center">Precise verification for coding agents on mobile apps: fewer false passes, fewer false fails, fewer tokens.</p>

When an agent changes a web app it can open a browser and check its work; on mobile it usually edits code and hopes.
[**mdh**](https://github.com/mobile-dev-harness/mobile-dev-harness) gives agents a real device or emulator, designed
around how they work:

- **Compact screens** (~150 tokens) with stable refs, and only what changed after each action
- **What a change reaches**: the screens and call sites a diff affects, from static analysis, in ~150 ms
- **Verdicts with evidence**, not impressions: checks on screens and logs, replayable flows, JUnit
- **UI consistency, performance and compatibility checks**, each risk verified where the change puts it at risk
- One engine, two interfaces: a CLI and an MCP server, plus a Claude Code plugin

## Repositories

| | |
|---|---|
| [mobile-dev-harness](https://github.com/mobile-dev-harness/mobile-dev-harness) | `mdh`: the CLI, the MCP server and the verification engine |
| [android-compat-kb](https://github.com/mobile-dev-harness/android-compat-kb) | What an Android change can run into on other OS versions, device types and vendor ROMs, as data with sources |

Android today; written in Rust; MIT or Apache-2.0. [简体中文](https://github.com/mobile-dev-harness/mobile-dev-harness/blob/main/README.zh-CN.md)
