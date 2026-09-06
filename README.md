<p align="center">
  <img src="assets/profile-banner.png" width="100%" alt="Onour Impram, clinical psychologist, AI researcher, and engineer. Inspectable memory, verifiable systems, and human approval for consequential decisions.">
</p>

I study and build AI systems designed around people, with inspectable memory, verifiable claims, and human approval for consequential action.

## Onour Impram Ventures Ltd

[![SPONSORED BY E2B FOR STARTUPS](https://img.shields.io/badge/SPONSORED%20BY-E2B%20FOR%20STARTUPS-ff3001?style=for-the-badge&labelColor=black)](https://e2b.dev/startups)

**Supported by E2B for Startups.** We are grateful to E2B for supporting our AI research and agent infrastructure work with E2B credits and sandbox infrastructure.

## The problem I work on

Clinical work and agent engineering share a difficult requirement. A system must act under uncertainty without hiding what it remembers, overstating what its evidence supports, or taking an irreversible step on its own. My research examines the human mechanisms. My software turns those requirements into explicit controls.

## Three lines of evidence

### Research

I study clinical safety, calibrated reliance, emotional regulation, attachment, reinforcement, and human agency in interaction with AI.

### Systems

I build local memory, routing audit, independent verification, claim provenance, and decision control systems whose behavior can be inspected.

### Human approval

I keep consequential actions behind scoped approval, current evidence, and receipts tied to the action that actually occurred.

## Selected projects

### [mneme](https://github.com/OnourImpram/mneme)

**Problem.** Long projects lose context across sessions or bury it in stores that users cannot inspect.

**Mechanism.** Plain Markdown remains the source of truth. Local retrieval, redaction before storage, and human approval for durable edits keep provenance visible.

**Verification.** [`v4.1.0`](https://github.com/OnourImpram/mneme/releases/tag/v4.1.0) is the current public release under `Apache-2.0`, published to npm as `mneme-mcp-server` and listed in the Model Context Protocol registry as `io.github.OnourImpram/mneme`. At commit [`de0712c`](https://github.com/OnourImpram/mneme/commit/de0712ca8e00cec52e77fa215329f31d11254be2), repository integrity, the seven-surface benchmark gate, the Neo4j knowledge-graph integration, CodeQL, and the Python 3.11 through 3.14 and Node 22 and 24 matrices on Ubuntu, macOS, and Windows were all successful.

**Limit.** Production retrieval uses FTS5 BM25. Semantic embedding remains on the roadmap, and the published numbers are synthetic regression anchors rather than measurements of quality in real settings.

### [Mergen Verdict](https://github.com/OnourImpram/mergen)

**Problem.** A completion claim is not proof that the named artifact exists, the tests passed, or the evidence is current.

**Mechanism.** Mergen rederives repository evidence and returns `pass`, `conditional_pass`, `fail`, or `unverifiable`. Human approval can be bound to the exact bytes of the verification report.

**Verification.** [`v2.1.3`](https://github.com/OnourImpram/mergen/releases/tag/v2.1.3) is the current public release under `Apache-2.0`. At commit [`2e64f62`](https://github.com/OnourImpram/mergen/commit/2e64f62a07c6ee5be6a45f45636dc45afb9bd54e), Python and Windows tests, strict mypy, ruff, coverage, CodeQL, and secret scan checks passed.

**Limit.** The bundled supervisor currently covers Mergen software task reports. It returns a decision but does not modify the judged artifact or start the next stage.

### [routeledger](https://github.com/OnourImpram/routeledger)

**Problem.** A configured model name does not prove which model actually served a turn.

**Mechanism.** routeledger reads local session records, compares declared and served models where evidence exists, and reports drift without writing files or sending data over a network.

**Verification.** [`v0.3.1`](https://github.com/OnourImpram/routeledger/releases/tag/v0.3.1) is the current public release under `MIT`. At commit [`75a2d4b`](https://github.com/OnourImpram/routeledger/commit/75a2d4b6c4bd67e4b38cfd0b56dde0d78be008d9), its Node 20 and Node 22 test matrix passed on Ubuntu and Windows.

**Limit.** routeledger cannot reconstruct environment variables or configuration in force at session time. Missing evidence becomes `unverifiable`, never a clean result.

### [VocationOS](https://github.com/OnourImpram/vocation-os)

**Problem.** A submission, outreach message, or licensing action can be difficult to reverse, while an agent can report completion without trusted proof.

**Mechanism.** VocationOS binds claims to evidence, consequential actions to scoped human approval, and completion to a trusted receipt. Its signed checkpoints detect changes to prior entries in the audit trail.

**Verification.** [`v0.6.2`](https://github.com/OnourImpram/vocation-os/releases/tag/v0.6.2) is the current release, distributed primarily as source under `MIT`. At commit [`5d73e93`](https://github.com/OnourImpram/vocation-os/commit/5d73e93be0260ea77efa792de421aee91b83a32e), build, Ubuntu, Windows, CodeQL, and deployment checks passed.

**Limit.** The release does not include a production adapter for automatically submitting job applications. The only executable adapter is a local synthetic fixture.

### [Claude Code for Social Scientists](https://github.com/OnourImpram/claude-code-for-social-scientists)

**Problem.** Social scientists need practical AI workflows that preserve research integrity, source verification, confidentiality, and bilingual conceptual parity.

**Mechanism.** The project combines a Turkish and English curriculum for Claude Code with 32 narrow research skills that can be installed for Claude Code or Codex.

**Verification.** [`v5.0.0`](https://github.com/OnourImpram/claude-code-for-social-scientists/releases/tag/v5.0.0) is the current public release. Its code is licensed under `Apache-2.0`, and its prose under `CC-BY-NC-SA-4.0`. It has the Zenodo DOI [`10.5281/zenodo.20289687`](https://doi.org/10.5281/zenodo.20289687). At commit [`1674b12`](https://github.com/OnourImpram/claude-code-for-social-scientists/commit/1674b12c2c41462d03ef1dd594ebda77bfdc227b), repository, DOI, external link, and secret scan checks passed.

**Limit.** The build checks declared citation status and repository consistency. Underlying sources still require human verification at claim level, and the human researcher retains scientific, ethical, clinical, and professional authority.

## Research and books

**Research agenda.** I organize the work around context, mechanism, evidence, and limits. Current themes include clinical safety, calibrated reliance, regulation in interactions between people and AI, attachment, reinforcement, problematic involvement, and meaningful human oversight. More detail is available on the [research page](https://onourimpram.com/en/research).

**Book.** [*Üretken Yapay Zekâ ve Ruh Sağlığı*](https://www.kitapyurdu.com/kitap/uretken-yapay-zeka-ve-ruh-sagligi/755202.html). My monograph was published by Nobel Akademik in 2026. It examines generative AI across psychotherapy, psychoeducation, assessment, and crisis intervention. ISBN `9786253642419`.

**Book chapters.** [*Pozitif Psikoloji*](https://www.kitapyurdu.com/kitap/pozitif-psikoloji/748917.html). I contributed chapters on overcoming difficult times, strengths, meaning, mindfulness, and positive relationships. Ibn Haldun University Press, 2026. ISBN `9786259302348`.

**Published research.** A 2024 article examining the feasibility of using therapy involving animals to treat depression, published in *Current Approaches in Psychiatry*, 16(3). [DOI 10.18863/pgy.1373976](https://doi.org/10.18863/pgy.1373976).

**Research resource.** The mental health booklet series [*A Closer Look at Mental Health*](https://doi.org/10.5281/zenodo.21768233) is available under `CC BY-NC-ND 4.0`.

**Academic identity.** [ORCID 0000-0003-1076-3928](https://orcid.org/0000-0003-1076-3928).

## Upstream contributions

Public status verified on August 18, 2026.

**pytest-cov.** [Pull request 751](https://github.com/pytest-dev/pytest-cov/pull/751) makes the `fail-under` summary agree with the exit code. Status: open.

**anthropics/skills.** [Pull request 1147](https://github.com/anthropics/skills/pull/1147) adds a Turkish academic writing skill. Status: open.

**fableplan.** [Pull request 1](https://github.com/tylerlaprade/fableplan/pull/1) adds PowerShell support. Status: open.

## Collaboration

If you are working on clinical AI safety, research integrity, or verifiable agent systems, I welcome a focused collaboration proposal through [onourimpram.com](https://onourimpram.com).
