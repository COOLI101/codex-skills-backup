# Codex Skills Backup

Private backup of the user-installed Codex skills from:

`C:\Users\hxgsh\.codex\skills`

Backup date: 2026-10-13 (Asia/Hong_Kong)

## Contents

- `skills/`: 29 user-installed skills, each with its original `SKILL.md` and supporting files.
- `manifests/skills-inventory.csv`: file counts, sizes, timestamps, and `SKILL.md` SHA-256 hashes.
- `manifests/skills-source-map.csv`: original GitHub repositories and repository subpaths recovered from installation history.
- `manifests/repository-locations.csv`: historical local clones that still existed when the backup was made.

The client-managed `.system` skills are intentionally excluded because they are bundled with the Codex installation and may change with client updates.

## Restore

Close Codex before restoring. Copy the desired directories from `skills/` into:

`C:\Users\<Windows-user>\.codex\skills`

Do not overwrite an existing skill until its current directory has been backed up. Reopen Codex after copying so skills are rediscovered.

## Provenance

These files retain their original upstream content. See `manifests/skills-source-map.csv` for the source repository of each skill. Upstream licenses and notices continue to apply.
