# AGENTS.joeblew999.md — branch-local agent guide

Operational brief for any AI agent working on the `joeblew999` branch of `agentic-inbox`.

**Project guidance:** follow upstream project instructions and this branch-local guide.
The former shared mise library is retired; see [MISE-RETIREMENT.md](MISE-RETIREMENT.md).

## What this repo is

Cloudflare Worker — Email Routing + agentic inbox UI. Deploy via 10-deploy.

## Branch-local quirks

None branch-local.

## Mise wiring

[mise.toml](mise.toml) contains only local tasks. The shared pre-push `check`
wrapper has been retired; run the project checks appropriate to your changes.
