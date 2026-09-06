\# Claude Code — Recovery Cheat Sheet

&#x20;

\## Config won't load

\- Run /config to confirm project settings are loaded

\- Validate JSON: python -m json.tool .claude/settings.json

&#x20;

\## A permission is blocking you

\- Check the deny list in .claude/settings.json

\- Widen an allow rule, e.g. Edit(src/\*\*) -> Edit(\*\*)

&#x20;

\## Auth / login expired

\- /status to check the account, then re-login via /login

&#x20;

\## Roll back a bad change

\- git diff to review, git checkout -- <file> to revert

