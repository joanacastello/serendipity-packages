# Serendipity packages

Immutable offline catalog packages for the Serendipity mobile app (Burning Man 2026).

## Layout

- `2026/latest.json` — mutable pointer the app polls on explicit download
- [Releases](https://github.com/joanacastello/serendipity-packages/releases) — one tag per `packageVersion`; SQLite assets are never rewritten

## Version history

Each GitHub Release tag equals one published package version (for example `2026.08.06-base.1`). Rolling back means pointing `latest.json` at a previous release asset; old releases stay available.

## Not affiliation

This repository redistributes derived, validated snapshots for an unofficial fan app. It is not affiliated with Burning Man Project.
