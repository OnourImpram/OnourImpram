# Package Registry Migration Plan

Canonical owner: `OnourImpram`

The username change affects repository URLs, documentation URLs, badges, GitHub Packages namespaces, GitHub Pages URLs, and external indexes. It does not automatically rename packages on PyPI or npm.

| Package | Registry | Current package name | Contains legacy username? | Metadata URLs updated? | Publish required? | Deprecation required? | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| VocationOS | npm | `vocation-os` | No | Yes | Optional patch release after review | No | Keep unscoped package name. |
| mneme root workspace | npm workspace | `mneme` | No | Yes | No, root is private | No | Root package is private. |
| mneme MCP server | npm | `mneme-mcp-server` | No | Yes for repository URLs | Optional patch release | No | `mcpName` still needs compatibility decision. |
| mneme core packages | PyPI or local package metadata | `mneme-core`, `mneme-cc-plugin`, related packages | No | Yes for project URLs | Optional patch release after tests | No | Do not rename packages. |
| mneme MCP identity | MCP registry | `io.github.TheGoatPsy/mneme` | Yes | Not changed automatically | Manual decision required | Possibly | Changing this may break registry discovery or existing clients. |
| mergen | PyPI candidate | `mergen` | No | Repository docs updated | Optional patch release after validation | No | Keep package name. |
| mergen npm scope note | npm | `@thegoatpsy/mergen` note only | Yes | Not changed automatically | Manual decision required | Possibly | Only act if package exists and migration is desired. |
| social-cc-plugin | PyPI | `social-cc-plugin` | No | Project URLs updated | Patch release recommended | No | Update PyPI Trusted Publishing owner settings manually. |
| Claude Code plugin marketplace | Plugin marketplace | `social-cc-plugin@claude-code-for-social-scientists` | No | Repository URLs updated | Manual marketplace refresh | No | Marketplace owner references require external publishing route. |
| GitHub Pages | GitHub Pages | `thegoatpsy.github.io` and future `onourimpram.github.io` | Yes for old privacy repo | Preserve old privacy URLs | Manual site migration | No | Do not delete privacy policy routes. |

## PyPI Rules

1. Keep package names unless the package name itself contains the legacy username.
2. Update `Homepage`, `Repository`, `Documentation`, `Issues`, and `Changelog` project URLs to `https://github.com/OnourImpram/<repo>`.
3. Publish patch releases only after tests, build, and metadata inspection pass.
4. If Trusted Publishing is enabled, update PyPI project settings manually.
5. Never print or commit PyPI tokens.

## npm Rules

1. Keep unscoped packages if their package name does not contain the legacy username.
2. Update `repository`, `bugs`, `homepage`, README links, and package docs.
3. Run tests, build, and `npm pack --dry-run` before any publish.
4. Do not unpublish packages unless there is a security or privacy reason and explicit approval.

## External Indexes

Check manually:

1. npm package pages.
2. PyPI package pages.
3. GitHub Packages.
4. GHCR.
5. MCP marketplaces.
6. Read the Docs.
7. Zenodo or OSF.
8. ORCID works.
9. LinkedIn featured links.
10. Personal website links.
