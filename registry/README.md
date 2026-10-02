# Registry Schema

`tools.json` is machine-readable and intentionally compact.

Fields:
- `id`: stable unique identifier.
- `name`: display name.
- `kind`: tool, framework, service, plugin, skill, or MCP.
- `status`: `approved`, `candidate`, `watch`, `deprecated`, or `rejected`.
- `categories`: broad use domains.
- `version`: last known checked version/context; may be null when not verified.
- `lastChecked`: date of last verification; null means revalidation is required before reliance.
- `url` / `repo`: official or repository links when known.

`approved` means vetted for a category, never automatic default. Any entry with null `lastChecked` should be treated as discovery/candidate until verified.
