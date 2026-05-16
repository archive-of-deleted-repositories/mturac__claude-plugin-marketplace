# mturac Claude Code Marketplace

A single `marketplace.json` registry of every Claude Code plugin under [mturac/tools](https://github.com/mturac/tools).

## Install

```text
/plugin marketplace add mturac/claude-plugin-marketplace
```

Then browse and install individual plugins:

```text
/plugin install argus-audit
/plugin install commit-narrator
/plugin install moooom
# …
```

## Plugins

| Plugin | Category | Description |
|---|---|---|
| `argus-audit` | security | Scope-gated white-hat security audit + pentest orchestrator |
| `commit-narrator` | developer-tools | Conventional commit message generator |
| `pr-storyteller` | developer-tools | PR title + body + test plan from diff |
| `test-gap` | testing | Surface diff lines not covered by tests |
| `deps-doctor` | security | Dependency vuln/audit across npm/pip/cargo/go |
| `standup-gen` | developer-tools | Daily standup from git activity |
| `todo-harvest` | developer-tools | TODO/FIXME with author + age via git blame |
| `env-lint` | developer-tools | `.env` vs `.env.example` parity |
| `secret-guard` | security | Pre-commit secret scanner (regex + entropy) |
| `flaky-detector` | testing | Run tests N times, report flakiness % |
| `changelog-forge` | developer-tools | Conventional-commits → CHANGELOG + semver |
| `claude-roundtable` | ai-infrastructure | Multi-agent council governance |
| `skill-hunter` | ai-infrastructure | Pre-execution skill discovery hook |
| `promptguard` | ai-infrastructure | Prompt-contract auditor |
| `moooom` | wellness | 10 cultures of moms nagging your agent |

Every plugin lives in its own repo with its own LICENSE, tests, and release tags. See [mturac/tools](https://github.com/mturac/tools) for the hub.

## License

MIT — see each plugin's `LICENSE` for its own copy.
