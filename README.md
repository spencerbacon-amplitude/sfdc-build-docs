# sfdc-build-docs

Reference documentation for a Claude Code-driven Salesforce build system: workflow shapes, entry-path matrix, coding playbook, and per-worker step-by-step lifecycles.

Hosted via GitHub Pages → [open the site](https://spencerbacon-amplitude.github.io/sfdc-build-docs/) once Pages is enabled.

## What's here

| Page | Source |
|---|---|
| Build Process | mirrored from `~/.claude/BUILD-PROCESS.html` |
| Playbook | rendered from `spencerdev/docs/sfdc-playbook.md` |
| Hooks | mirrored from `~/.claude/HOOKS.html` |
| Skills | mirrored from `~/.claude/SKILLS.html` |
| Shapes & Tiers | mirrored from `~/.claude/SHAPES.html` |
| Worker workflows (index + per-worker + combined) | mirrored from `spencerdev/docs/worker-workflows/` and `spencerdev/docs/worker-workflows.html` |

## Refreshing

Source files live outside this repo. Updates are not automatic.

1. Edit the source files (in `~/.claude/` or via a `spencerdev` worktree).
2. Re-run the assembly script (kept locally in `~/AppData/Local/Temp/assemble-public-repo.py` during the initial publish; promote to a checked-in `_scripts/` location later if refresh frequency justifies it).
3. Commit + push.

## Local preview

Open `index.html` directly in a browser — works via `file://` since all paths are relative.
