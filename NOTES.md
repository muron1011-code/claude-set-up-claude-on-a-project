# Claude Code Setup Notes

## CLAUDE.md

`CLAUDE.md` contains the project's purpose, frequently used commands, development conventions, and high-level architecture.

I deliberately left out detailed implementation information, long documentation, one-off task instructions, and sensitive information because `CLAUDE.md` should stay short and provide stable guidance that Claude can reuse across tasks.

## Permissions

The configuration allows `npm test` because running the test suite is a safe and useful development action.

Git push requires confirmation so changes are not uploaded unintentionally.

Reading `.env` is denied to protect environment variables and possible secrets.

Force-pushing to Git is denied because it can overwrite remote history and potentially remove other commits.

## Verification

The setup should be verified in a fresh Claude Code session using `/memory` to confirm that `CLAUDE.md` is loaded and `/permissions` to confirm the configured permission rules.

The Definition of Done includes both checks.
