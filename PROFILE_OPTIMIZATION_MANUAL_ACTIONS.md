# Profile Optimization Manual Actions

These actions require GitHub UI, registry UI, release ownership, or external account access. Do not treat them as completed until verified in the relevant service.

## GitHub Profile Fields

Recommended bio:

```text
Clinical psychologist building accountable AI memory, safer agent workflows, and evidence-grounded decision systems.
```

Optional shorter bio:

```text
Clinical psychologist turning duty of care into accountable AI infrastructure.
```

Manual cleanup:

1. Confirm the profile URL is `https://github.com/OnourImpram`.
2. Confirm the profile README renders from `OnourImpram/OnourImpram`.
3. Remove duplicate ORCID link if present.
4. Keep one ORCID link only.
5. Keep LinkedIn once.
6. Use `https://onourimpram.github.io` as website only after the portfolio homepage is ready.
7. Keep email public only if intentionally desired.
8. Do not add phone number or private address.

## Pin Order

1. `mneme`
2. `vocation-os`
3. `claude-code-for-social-scientists`
4. `mergen`

Do not pin forks, privacy policy repositories, the profile README repo, or weak placeholder repos.

## Repository Descriptions

```text
mneme
Local-first, audit-safe memory for Claude Code and MCP clients.

vocation-os
Human-supervised career decision safety with claim graphs, high-stakes gates, and append-only audit.

mergen
Risk-scaled execution harness for AI coding agents with workflow orchestration and adversarial verification.

claude-code-for-social-scientists
Bilingual Claude Code handbook for social scientists, with citation-audited workflows and AI disclosure templates.

onourimpram.github.io
Personal research software portfolio for accountable AI infrastructure and human-stakes AI.
```

## Topics

For `vocation-os`:

```text
vocation-os
career-guidance
career-development
vocational-psychology
decision-support
ai-safety
human-in-the-loop
llm-agent
typescript
cli
reversibility
evidence-based
claim-graph
audit-log
red-team
governance
responsible-ai
career-counseling
agent-safety
high-stakes-ai
```

For `mneme`, preserve existing topics and add:

```text
agent-memory
ai-agents
```

For `claude-code-for-social-scientists`, preserve existing topics and add:

```text
social-sciences
research-workflows
academic-ai
ai-disclosure
open-science
```

For `mergen`:

```text
ai-agents
agent-safety
coding-agents
workflow-orchestration
red-team
verification
python
execution-harness
automation-safety
research-software
```

## Discussions

Enable Discussions for:

1. `mneme`
2. `vocation-os`
3. `mergen`
4. `claude-code-for-social-scientists`, if appropriate

Suggested categories:

```text
Announcements
Q&A
Ideas
Use cases
Papers and references
Safety review
Show and tell
```

Suggested first discussions:

```text
VocationOS roadmap, what should be gated first?
mneme use cases, what should accountable AI memory remember and forget?
Claude Code for Social Scientists, which research workflow should be documented next?
```

## Releases

Create GitHub releases only where the repository has a stable enough state.

Priority:

1. `vocation-os`, release `v0.2.0` unless version is bumped first.
2. `mneme`, release only after npm and package metadata are confirmed.
3. `mergen`, release only if external user installation is validated.

Draft VocationOS release note:

```md
# VocationOS v0.2.0

Initial public safety release.

Includes strict TypeScript, AJV schema validation, claim graph, application packet validation, reversibility gates, high stakes gates, guarded auto apply decision engine, append only action ledger, synthetic demo profile, red team tests, privacy scan, brand scan, docs check, pack check, governance docs, safety docs, and the Decision Control Room microsite.
```

## Social Preview Upload

Upload the repository social preview images through GitHub repository settings after the SVG assets are committed.

Recommended copy:

```text
mneme
Local-first AI memory you can inspect, diff, redact, and correct.

VocationOS
Evidence-grounded career decision safety.
Claim graph. Reversibility. High-stakes gates. Human approval.

Claude Code for Social Scientists
Agentic coding for researchers without methodological collapse.

mergen
Risk-scaled execution harness for AI coding agents.
```

## Portfolio Homepage

Create or confirm `OnourImpram/onourimpram.github.io`.

Keep existing privacy policy repositories and URLs intact. If privacy pages are migrated later, add redirects first and verify app store or external links before removing any old route.
