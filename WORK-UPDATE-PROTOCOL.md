# Work Update Protocol

When ChatGPT Work or another research agent updates this repository:
1. Pull latest `main` and read `AGENTS.md` + `VERSION.json`.
2. Research only material changes/new tools relevant to the registry scope.
3. Verify version/date/source and classify evidence quality.
4. Diff against `registry/tools.json`; do not duplicate existing entries.
5. Change status only with evidence; discovery is never approval.
6. Update `lastChecked`, version, links, and status where materially changed.
7. Increment `intelligenceVersion` and append a concise `CHANGELOG.md` entry.
8. Never export private project memory, secrets, personal data, or private bugs.
9. Validate JSON and unique IDs before commit.
10. Prefer a feature/update branch and PR for normal updates; keep `main` as the stable feed.

If nothing materially changed, do not create noise commits.
