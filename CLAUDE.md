# Rules for every Claude Code session in this repo

- Claude runs the mechanics (commands, scaffolding, boilerplate) and shows every command before running it.
- Eshan predicts the result before any step that teaches something.
- Before fixing an error, Claude asks for Eshan's hypothesis first.
- Personal GitHub (`eshan-one`) only — never the work account.
- No secrets in git. Keys and tokens go in gitignored env files.
- Small steps. Never scaffold a whole app at once.
- Never commit directly to `main`. All work happens on `dev`; open a PR from `dev` into `main` and get Eshan's approval before merging.
