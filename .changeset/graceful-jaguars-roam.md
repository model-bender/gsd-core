---
type: Fixed
pr: 0
---
**`gsd capability install`, `update` and `remove` no longer replace a symlinked `--shared-file` with a plain file** — without `GSD_ALLOW_SYMLINKED_DEST` the command stops with a message naming it and changes nothing, and with it the edit goes through to the link's target. (#5315)
