# cll-pkg

**package manager** — part of [CLL](https://github.com/CLT-Wasim/CLL), the Conserving Logic Language.

> Read [`AGENTS.md`](./AGENTS.md) first. It points at the binding rules; this README is only a summary.

## Purpose

Manifest `cll.toml`, lockfile, and the capability audit that reports what a dependency asks for (network, filesystem, clock) before you install it. Scheduled after v1.

## Status

Pre-v1. Nothing here is shipped until a command produced the result and the result is in a
results table with the command that produced it. See the milestone list in
[`ROADMAP.md`](https://github.com/CLT-Wasim/CLL/blob/main/ROADMAP.md).

## Layout

* `src/`

## Language policy

Rust.

## License

Apache-2.0. See [`LICENSE`](./LICENSE).
