# Onour Impram

> Accountable AI infrastructure for human stakes work.

I am a clinical psychologist and AI researcher building accountable memory, safer agent workflows, and evidence grounded decision systems.

My central question is practical.

**How can AI systems remember, reason, and act without becoming opaque, uncorrectable, or unsafe when human stakes are real?**

My clinical background gives me a duty of care lens. My engineering work turns that lens into systems, local first memory, claim tracking, audit trails, reversibility gates, red team tests, and evidence aware workflows.

Clinical duty of care, translated into accountable AI infrastructure.

## Start here

### [mneme Record](https://github.com/OnourImpram/mneme)

Vault native, accountable memory for Claude Code and MCP clients.

Markdown is the source of truth. No LLM runs on the Stop path, and CI fails the build on any network import in a lifecycle hook. Derived stores are redacted before write. Production retrieval is SQLite FTS5 BM25, guarded by a benchmark that fails a pull request if quality drops below the locked baseline.

```bash
pipx install mneme-cc-plugin && mneme install
```

### [VocationOS](https://github.com/OnourImpram/vocation-os)

Evidence grounded career decision safety for high agency operators.

A human supervised decision system with claim graphs, packet validation, reversibility gates, high stakes certainty brakes, and append only action ledgers.

Read it as an architecture for what high stakes automation safety looks like, not as a tool that applies to jobs for you. It ships no production auto apply adapter; the compiled execution boundary permits only `local-fixture` with a synthetic profile.

```bash
git clone https://github.com/OnourImpram/vocation-os
```

### [Claude Code for Social Scientists](https://github.com/OnourImpram/claude-code-for-social-scientists)

A bilingual Turkish and English guide for using Claude Code in social science research without abandoning methodology, authorship transparency, or critical judgment.

### [Mergen Verdict](https://github.com/OnourImpram/mergen)

Independent milestone verification for agentic and human engineering workflows.

An executor saying work is complete is a completion claim, not proof. Mergen reproduces the evidence, applies a risk floor that cannot be downgraded, and returns a fail-closed advancement decision. It does not execute the next stage.

```bash
pip install mergen-verdict
```

## What I build

| Area | Focus |
| --- | --- |
| Accountable AI memory | Local first memory, redaction, retrieval, claim lifecycle, auditability |
| Agent safety | Reversibility, guarded automation, prompt injection resistance, red team tests |
| Research software | Citation audited workflows, reproducibility, academic disclosure, methodology |
| Human stakes AI | Mental health, career decisions, professional identity, consent, accountability |

## Current focus

1. Making AI memory inspectable, correctable, and safe.
2. Building agent workflows that scale judgment, not just automation.
3. Translating clinical duty of care into AI infrastructure.
4. Helping social scientists use agentic tools without methodological collapse.

## Background

Clinical psychologist, PhD candidate in Clinical and Health Psychology, AI and mental health researcher, educator, and builder of research software for human stakes domains.

My work connects clinical safety, research methodology, local first software, and agent governance. The goal is not more automation by default. The goal is automation that can be inspected, corrected, constrained, and held accountable.

## Principles

Correctness over appearance.

Auditability over mystique.

Care over scale theatre.

Local first when the stakes are human.

Every memory should be traceable, correctable, and accountable.

## Follow the work

If this work is useful, star the projects you want to revisit and follow [@OnourImpram](https://github.com/OnourImpram) for future releases on accountable AI memory, agent safety, career decision safety, and research workflows.
