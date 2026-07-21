# Marina

> ⚠️ **Work in progress — alpha.** Expect rough edges and breaking changes.

A native macOS app for local container development on
[Colima](https://github.com/abiosoft/colima). One window for your whole local
stack — no Docker Desktop, no Electron, no telemetry.

- Containers & compose projects — live logs, shell, in-place file editing, stats
- Zero-config database browser (Postgres / MySQL / Redis) and S3 storage (MinIO & friends)
- VM management — create, switch, resize multiple Colima VMs from the UI
- Ports overview with one-click public tunnels, k6 load testing, built-in mail trap
- Command palette, dark/light theme, EN · DE · ES · LT

This repo is the release channel: builds live under
[Releases](../../releases), and `version.json` drives the in-app updater
(`latest` is set by the release workflow, `minSupported` is edited by hand).
The source repo stays private during the alpha.
