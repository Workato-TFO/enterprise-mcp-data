# mcp-data

Customer-facing Enterprise MCP 202 lab guides, served through GitHub Pages.

## Visibility contract: designed public

This repository is **designed public**. It may remain private until promotion,
but every commit must already meet the public bar:

- No secrets, tokens, keys, or credentials.
- No internal URLs, employee names, or authoring discussion.
- Customer-facing register only; issues remain disabled.

Only vetted, self-contained HTML and the index page belong in `docs/`. Never
commit source manuscripts, authoring decisions, or unpublished working assets.

Do not edit lab HTML in place. Re-press from the internal authoring repository
and replace the complete `docs/` snapshot after review.

Run `bash scripts/publish-checks.sh` before every push. Do not change repository
visibility or promote Pages access without explicit release approval.
