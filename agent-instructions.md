# Agent Instructions

This repository publishes the openEHR Developer Guide. Its first section is the openEHR tooling guide; implementation and conformance guidance will be added over time.

## Read First

- [README.md](README.md) - site purpose and local preview.
- [mkdocs.yml](mkdocs.yml) - site navigation and deployment URL.
- [house style documentation guidance](https://github.com/pacharanero/house-style/blob/main/docs.md) - Zensical and GitHub Pages conventions.

## Core Invariants

- Keep the site compatible with Zensical; do not add MkDocs or Material-only configuration.
- Keep every documentation page in the explicit navigation.
- Publish through the artifact-based GitHub Pages workflow. Do not create a `gh-pages` branch.
- Keep `docs/CNAME` set to `developer.openehr.org`.

## Workflow

- `python3 -m venv .venv && .venv/bin/pip install -r requirements.txt` - install the local site builder.
- `.venv/bin/zensical build --clean` - build the site.

## Before Every Commit

```sh
.venv/bin/zensical build --clean
```

## Git Workflow

- Use a branch and pull request for documentation changes unless an openEHR maintainer explicitly permits a direct update.

## Approval Required

- Ask before publishing releases, changing the custom domain, modifying GitHub Pages settings, or taking any other externally visible action.
