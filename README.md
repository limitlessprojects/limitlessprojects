# limitlessprojects

We build **Go-Hybrid** — a hybrid language and toolchain that compiles a
Rust-checked, Go-shaped language (`hy`) to readable Go, with a loan checker
that rejects data races, use-after-free-shaped bugs, and unbuildable emissions
*before* `go build` ever runs.

## What's live

- **[Go-Hybrid](https://github.com/limitlessprojects/Go-Hybrid)** — compiler
  (`hyb check` / `hyb build` / `hyb generate`), corpus (122+ fixtures),
  differential harness, managed blocks, arm64 bridge, Docker images at
  `ghcr.io/limitlessprojects/go-hybrid`, and an open bounty program with
  published verdict windows.
- **Autoland** — an automation pipeline that independently verifies contributor
  PRs (repro on main, patched repro, full battery, corpus, differential) before
  landing them, so good fixes merge fast and bad ones get precise triage.
- **[ReadAny-App](https://github.com/limitlessprojects/ReadAny-App)** — mobile
  reading app with streaming LLM reading, TTFT badges, and Swahili voice.

## How we work with contributors

Every PR gets a real verification: the reported bug is reproduced on main, the
fix is probed against the repro *and* over-reach controls, and the full
battery must stay green. Same-fix duplicates are credit-closed with the
verification evidence spelled out — your work is named either way.

Bounty wildcards and capability proposals run through public discussions with
pre-registered review windows.
