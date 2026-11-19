# Ccboat is now AgentBoat

> [!IMPORTANT]
> **Ccboat has been renamed to AgentBoat** and lives on at
> **[github.com/yash-desai-naik/agentboat](https://github.com/yash-desai-naik/agentboat)**.
> This repository is kept for its history and to hand installed copies over to AgentBoat. It gets
> no new versions.

Same app (a read-only, IDE-style view of a Claude Code session, live or replayed step by step),
new name. Version 0.6.0 is the first AgentBoat release.

## Already using Ccboat?

You don't need to do anything.

1. Ccboat offers one last update: version 0.6.0 (it tells you itself, or use **Ccboat ▾ → Check
   for updates**). **Install and restart** installs AgentBoat and opens it.
2. On its first start, AgentBoat moves you in:
   - your view settings, the last session you opened and your saved status line come along;
   - **Answer prompts** and **Show usage limits** stay on if you had them on: their entries in
     Claude Code's `settings.json` are pointed at AgentBoat, with the same port and token;
   - Ccboat is uninstalled, and AgentBoat takes its place in the Start menu (and on the desktop, if
     Ccboat was there).

After that, re-pin AgentBoat to the taskbar if you had Ccboat pinned. Ccboat's old data folder,
`%LOCALAPPDATA%\app.ccboat`, is left in place; you can delete it once AgentBoat looks right.

## New here?

Download AgentBoat from its
**[Releases page](https://github.com/yash-desai-naik/agentboat/releases/latest)**
(`AgentBoat_x.y.z_x64-setup.exe`).

Installing AgentBoat by hand over an existing Ccboat works too: start it once and it does the same
move-in as the update.

## Links

| | Ccboat (this repo) | AgentBoat |
|---|---|---|
| Code | archived history, up to 0.5.1 | [yash-desai-naik/agentboat](https://github.com/yash-desai-naik/agentboat) |
| Releases | [0.1.0 – 0.5.1](https://github.com/yash-desai-naik/ccboat/releases) | [latest](https://github.com/yash-desai-naik/agentboat/releases/latest) |
| Issues | please report new ones on AgentBoat | [open an issue](https://github.com/yash-desai-naik/agentboat/issues) |
| Changelog | [CHANGELOG.md](CHANGELOG.md) | [CHANGELOG.md](https://github.com/yash-desai-naik/agentboat/blob/main/CHANGELOG.md) |

## License

MIT, as before: see [LICENSE](LICENSE).
