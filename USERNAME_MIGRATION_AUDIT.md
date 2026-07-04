# Username Migration Audit

Canonical GitHub username: `OnourImpram`

Canonical profile URL: `https://github.com/OnourImpram`

Legacy username references are allowed only in this audit, migration checklists, redirect notes, package remediation notes, and historical compatibility decisions.

| Repository | File | Old reference | New reference or decision | Category | Notes |
| --- | --- | --- | --- | --- | --- |
| Profile README repo | `README.md` | Old owner links and old Pages links | Replaced with `https://github.com/OnourImpram/...` profile copy | `replace_now` | Public profile copy no longer centers the legacy username. |
| Profile README repo | Repository name | `OnourImpram/TheGoatPsy` | Rename to `OnourImpram/OnourImpram` | `manual_registry_update` | Required for GitHub profile README rendering. |
| `mneme` | `README.md`, `CONTRIBUTING.md`, `SECURITY.md`, `NOTICE`, `docs/GOVERNANCE.md` | Old GitHub owner URLs and maintainer handle | Replaced with `OnourImpram` URLs and handle | `replace_now` | Current navigation and maintainer references. |
| `mneme` | `.github/CODEOWNERS`, issue template config | `@TheGoatPsy` and old security/discussion URLs | Replaced with `@OnourImpram` and new URLs | `replace_now` | Current GitHub ownership surface. |
| `mneme` | `CITATION.cff`, root `package.json`, plugin manifests, package READMEs, package `pyproject.toml` files | Old repository, homepage, bugs, documentation URLs | Replaced with `https://github.com/OnourImpram/mneme` URLs | `replace_now` | Package names were not renamed. |
| `mneme` | `server.json`, `packages/mneme-mcp/package.json`, `tools/repo_integrity.py` | `io.github.TheGoatPsy/mneme` | Intentionally left for compatibility decision | `package_name_decision_required` | MCP server identity may be externally indexed. Rename only after registry compatibility review. Public install snippets now use `OnourImpram/mneme`. |
| `mergen` | `README.md`, `CONTRIBUTING.md`, `SECURITY.md`, `CODE_OF_CONDUCT.md`, `NOTICE`, schema `$id` fields | Old GitHub owner URLs and maintainer handle | Replaced with `OnourImpram` URLs and handle | `replace_now` | Current navigation and schema identity. |
| `mergen` | `CITATION.cff` | Old repository URL | Replaced with `https://github.com/OnourImpram/mergen` | `replace_now` | Citation metadata should follow current canonical repo. |
| `mergen` | `PROVENANCE.md` | Current repository and relationship references | Replaced with `OnourImpram` owner references, while seed lineage was kept owner-neutral | `replace_now` | Public provenance no longer presents the legacy owner as a current navigation surface. |
| `mergen` | npm scope notes | `@thegoatpsy/mergen` | Manual package decision | `package_name_decision_required` | No package rename without registry continuity plan. |
| `claude-code-for-social-scientists` | `README.md`, `README.tr.md`, `web/index.html`, `mkdocs.yml` | Old GitHub and Pages URLs | Replaced with `OnourImpram` URLs and new Pages domain | `replace_now` | Current public navigation. |
| `claude-code-for-social-scientists` | `.claude-plugin/*`, `pyproject.toml`, `meta/social-cc-plugin.md`, `CITATION.cff` | Old repository and documentation URLs | Replaced with `OnourImpram` URLs | `replace_now` | Package names were not renamed. |
| `claude-code-for-social-scientists` | `meta/pypi-pending-publisher.md` | Pending publisher owner field | Left for manual registry update | `manual_registry_update` | PyPI Trusted Publishing requires UI update. |
| `claude-code-for-social-scientists` | `provenance/timestamp.txt` | Historical repository snapshot | Intentionally left unchanged | `historical_do_not_edit` | Timestamped provenance artifact. |
| `thegoatpsy.github.io` | Repository name and privacy URLs | Legacy Pages repository | Intentionally preserved | `historical_do_not_edit` | Public privacy policy routes may be used by existing apps. |
| `vocation-os` | Public repo content | No current legacy owner references found | No replacement required | `replace_now` | Topics and citation/visibility assets still improved. |
