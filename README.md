<p align="center">
  <img src="assets/profile-banner.png" width="100%" alt="Onour Impram, clinical psychologist and engineer. Accountable AI infrastructure for human stakes work: local-first memory, independent verification, and agent systems that answer unverifiable instead of guessing.">
</p>

I am a clinical psychologist and a PhD candidate in clinical and health psychology, and I build the parts of AI systems that have to answer for themselves once the stakes are human.

The question underneath all of it: **how can a system remember, reason and act without becoming opaque, uncorrectable, or unsafe when real people depend on it?**

## What I ship

Five projects, all public, all installable or readable today.

### [mneme](https://github.com/OnourImpram/mneme) — memory you can audit

Local-first memory for Claude Code and MCP clients, where Markdown stays the source of truth. No model runs on the Stop path. CI fails the build if a lifecycle hook imports the network. Retrieval is held to a locked benchmark baseline, and a pull request that drops below it does not merge.

```bash
pipx install mneme-cc-plugin && mneme install
```

### [Mergen Verdict](https://github.com/OnourImpram/mergen) — verification that is allowed to say no

An executor reporting *done* has made a claim, not a proof. Mergen re-derives the evidence from the repository itself, applies a risk floor that cannot be downgraded, and returns a fail-closed advancement decision. It never runs the next stage.

```bash
pip install mergen-verdict
```

### [routeledger](https://github.com/OnourImpram/routeledger) — what actually served your session

The model answering your Claude Code turn can change without an error: an alias override, the plan-mode boundary, a safety fallback. Work continues and nothing tells you. Your transcript already recorded it; this reads it back. Read-only, offline, writes nothing.

```bash
npx routeledger
```

### [VocationOS](https://github.com/OnourImpram/vocation-os) — decisions that need a human first

A local-first daemon for career actions that cannot be undone — send, submit, publish. Claim graphs, scoped human approval, reversibility gates, and an append-only ledger that records an action as done only against a trusted receipt. It ships no production auto-apply adapter, deliberately.

### [Claude Code for Social Scientists](https://github.com/OnourImpram/claude-code-for-social-scientists) — the handbook

A bilingual Turkish and English guide for researchers who want agentic tools without surrendering methodology, authorship transparency, or a reference list they can defend in review.

## Why a clinician builds infrastructure

Clinical training is, in large part, training to act under uncertainty without pretending it is absent. You learn to keep what you observed separate from what you inferred, to write down which is which, and to stay answerable for the difference long after the session ends.

Most of what I build is that habit turned into code. It is why these tools would rather return `unverifiable` than a confident guess, and why the interesting engineering usually sits in what the system refuses to assert.

## If you would rather check than believe

Every project carries CI, a license, tagged releases and a changelog. The packages are published on PyPI and npm. My academic identity is [ORCID 0000-0003-1076-3928](https://orcid.org/0000-0003-1076-3928). Where a claim could not be verified, the documentation says so rather than rounding it up.

If one of these is useful, starring it tells me which to keep working on.
