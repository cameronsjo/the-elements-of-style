# The Elements of Style - Fork Maintenance

## Fork Relationship

- **Origin (push)**: `cameronsjo/the-elements-of-style`
- **Upstream (pull)**: `obra/the-elements-of-style`

## Syncing Upstream

```bash
git fetch upstream
git merge upstream/main
```

This repo changes infrequently — it's public domain reference content. Accept upstream changes freely.

## Where Customizations Live

- `README.md` — re-owned header
- `CLAUDE.md` — this file (fork-only)
- Any skill description tweaks in `skills/`

## What Not to Touch When Merging

- The reference text itself (`references/`) — it's Strunk's original work, don't modify
- `.claude-plugin/plugin.json` version bumps — accept upstream
