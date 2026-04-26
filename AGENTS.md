# Agent instructions

This file tells AI coding agents (Codex, Claude, etc.) how to work in this repo.

## Commit messages

Follow **Gitmoji + Conventional Commits** format:

    <emoji> <type>: <imperative summary>

### Examples

- 📝 docs: update intro section in README
- ✨ feat: add TryHackMe badge to profile
- 🔧 chore: add GitHub Actions workflow for badge update
- 💄 style: reformat projects section layout
- 🗑️ remove: remove GitHub stats card

### Rules

- Use imperative mood — "add" not "added", "fix" not "fixes"
- Keep the subject line under 72 characters
- Always include the emoji matching the type
- One logical change per commit

### Emoji → type reference

- 📝 docs — README content changes
- ✨ feat — new section, badge, or visual element
- 💄 style — formatting, layout, structure changes (no content change)
- 🔧 chore — config, tooling, workflows, maintenance
- 🗑️ remove — removing sections or files
- ⏪ revert — reverting a previous commit