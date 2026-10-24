# limitless projects

**We ship the things that shouldn't be possible — in public, with receipts.**

The AI revolution already happened. Code is free now; *attention and trust* are
what's scarce. Anyone can generate a repo. Almost nobody can prove their
software actually works. That proof is our product.

## What that means in practice

- **[Go-Hybrid](https://github.com/limitlessprojects/Go-Hybrid)** — a hybrid
  language and toolchain that compiles a Rust-checked, Go-shaped language
  (`hy`) to readable Go. The loan checker rejects data races,
  use-after-free-shaped bugs, and unbuildable emissions *before* `go build`
  ever runs. 127-fixture adversarial corpus, differential harness, arm64
  bridge, Docker images at `ghcr.io/limitlessprojects/go-hybrid`, published
  verdict windows.
- **Autoland** — contributor fixes are verified end-to-end (repro on main →
  patched repro with the exact expected error → full battery → corpus →
  differential loop) and landed by the machine, with evidence, while the
  humans sleep. The queue drains itself; every close gets a written reply;
  nothing merges without proof.
- **[ClockBench](https://github.com/limitlessprojects/ClockBench)** — the
  living, neutral, leakage-aware benchmark for epigenetic aging clocks: same
  clock, different packages, different ages — we measure it, with signed
  artifacts and a public leakage ledger.
- **Explainer films as code** — deterministic, rendered-from-source
  motion-graphics films about our own systems
  ([followbot-explainer](https://github.com/limitlessprojects/followbot-explainer)).

## The engineering wing — Codec Arena

[codec-arena](https://github.com/limitlessprojects/codec-arena) — an
evolutionary codec lab. A million bots (16-gene genomes controlling a real
Zig hybrid codec) fight over bits on 20 CI runners, scored
`PSNR − λ·bpp − complexity`, measured against x264 / x265 / SVT-AV1 / libaom
on the same corpus with the same instrument. The bar is external. The gap is
published. Every evaluation is a receipt.

## The contributor deal

Every PR gets a written reply — merged or not, no silent closes. Real
verification, not vibes: your reported bug is reproduced on main, your fix is
probed against the repro *and* over-reach controls, and the full battery must
stay green. Same-fix duplicates are credit-closed with the evidence spelled
out and your work named.

Bounties pay real money
([BOUNTY.md](https://github.com/limitlessprojects/Go-Hybrid/blob/main/BOUNTY.md)) —
including the **Wildcard Track**: contrarian, high-risk, "impossible" ideas.
Beautiful failures are published as learnings. And paid.

## The name is the promise

Projects, plural. Limits, none. We ship weekly, publish failures, and let
receipts do the marketing.

If that sounds like you: star
[Go-Hybrid](https://github.com/limitlessprojects/Go-Hybrid), take a
[good first issue](https://github.com/limitlessprojects/Go-Hybrid/labels/good%20first%20issue),
or fire a
[wildcard](https://github.com/limitlessprojects/Go-Hybrid/issues/new?template=wildcard.yml).
